# neural-network-hydroaccustic-signal-classification

This project represents a neural network for classifying hydroaccustic signals.

Hydroaccustic signals are represented by the spectre of the signal

Deeplearning4J used

import java.util.LinkedHashMap;
import java.util.Locale;
import java.util.Map;
import java.util.Set;
import lombok.RequiredArgsConstructor;
import lombok.extern.slf4j.Slf4j;
import org.springframework.stereotype.Service;
import ru.vtb.spm.afsnotificationadapter.dto.kafka.osn.resp.OsnKafkaResponseDto;
import ru.vtb.spm.afsnotificationadapter.enums.LogTag;
import ru.vtb.spm.afsnotificationadapter.enums.OsnKafkaSmsResponseStatus;
import ru.vtb.spm.afsnotificationadapter.enums.OsnPrefix;
import ru.vtb.spm.afsnotificationadapter.service.kafkaSms.KafkaSmsStatusAwaiter;

@Slf4j
@Service
@RequiredArgsConstructor
public class OsnService {
    private static final Set<String> DELIVERED_STATUSES =
            Set.of("DELIVRD", "DELIVERED", "PROVIDER_DELIVERED", "ДОСТАВЛЕНО");
    private static final String TEMPLATE_NOT_FOUND_STATUS = "UNP_GW_SOURCE";

    private final KafkaSmsStatusAwaiter kafkaSmsStatusAwaiter;

    public void receiveResponse(OsnKafkaResponseDto osnKafkaResponseDto) {
        String messageId = osnKafkaResponseDto.getId();
        String clientId = removePrefix(messageId);
        validateRequiredFields(clientId, osnKafkaResponseDto);

        OsnKafkaSmsResponseStatus status = toResponseStatus(osnKafkaResponseDto.getStatus());
        if (status == OsnKafkaSmsResponseStatus.UNKNOWN) {
            log.warn("[{}][{}] Получен нетерминальный статус от ОСН: {}",
                     LogTag.KAFKA_SMS,
                     clientId,
                     osnKafkaResponseDto.getStatus());
            return;
        }

        boolean completed = kafkaSmsStatusAwaiter.complete(messageId, status);
        if (completed) {
            log.info("[{}][{}] Статус '{}' передан ожидающему запросу.", LogTag.KAFKA_SMS, clientId, status);
            return;
        }

        log.debug("[{}][{}] Для id нет ожидающего запроса (возможно, уже таймаут/завершён): {}",
                  LogTag.KAFKA_SMS,
                  clientId,
                  messageId);
    }

    private void validateRequiredFields(String clientId, OsnKafkaResponseDto osnKafkaResponseDto) {
        Map<String, Object> requiredFields = new LinkedHashMap<>();
        requiredFields.put("id", osnKafkaResponseDto.getId());
        requiredFields.put("status", osnKafkaResponseDto.getStatus());
        requiredFields.put("deliveryMethod", osnKafkaResponseDto.getDeliveryMethod());
        requiredFields.put("source", osnKafkaResponseDto.getSource());

        requiredFields.entrySet()
                      .stream()
                      .filter(e -> e.getValue() == null
                              || (e.getValue() instanceof String stringValue && stringValue.isBlank()))
                      .findFirst()
                      .ifPresent(e -> {
                          log.error("[{}][{}] В ответе ОСН поле пустое или null: {}",
                                    LogTag.KAFKA_SMS,
                                    clientId,
                                    e.getKey());

                          throw new IllegalArgumentException(
                                  "В ответе OSN " + clientId + " поле " + e.getKey() + " пустое или null");
                      });
    }

    private OsnKafkaSmsResponseStatus toResponseStatus(String rawStatus) {
        if (rawStatus == null || rawStatus.isBlank()) {
            return OsnKafkaSmsResponseStatus.UNKNOWN;
        }
        String normalizedStatus = rawStatus.trim().toUpperCase(Locale.ROOT);
        if (DELIVERED_STATUSES.contains(normalizedStatus)) {
            return OsnKafkaSmsResponseStatus.DELIVERED;
        }
        if (TEMPLATE_NOT_FOUND_STATUS.equals(normalizedStatus)) {
            return OsnKafkaSmsResponseStatus.UNP_GW_SOURCE;
        }
        return OsnKafkaSmsResponseStatus.UNKNOWN;
    }

    private static String removePrefix(String input) {
        String prefix = OsnPrefix.AFS + "_";
        if (input != null && input.startsWith(prefix)) {
            return input.substring(prefix.length());
        }
        return input;
    }
}

