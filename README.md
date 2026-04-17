# neural-network-hydroaccustic-signal-classification

This project represents a neural network for classifying hydroaccustic signals.

Hydroaccustic signals are represented by the spectre of the signal

Deeplearning4J used

import com.fasterxml.jackson.databind.ObjectMapper;
import lombok.RequiredArgsConstructor;
import lombok.extern.slf4j.Slf4j;
import org.springframework.kafka.annotation.KafkaListener;
import org.springframework.kafka.support.Acknowledgment;
import org.springframework.stereotype.Service;
import org.springframework.util.StringUtils;
import ru.vtb.spm.afsnotificationadapter.config.kafka.osn.OsnKafkaProperties;
import ru.vtb.spm.afsnotificationadapter.dto.kafka.osn.resp.OsnKafkaResponseDto;
import ru.vtb.spm.afsnotificationadapter.enums.OsnPrefix;
import ru.vtb.spm.afsnotificationadapter.service.OsnService;
import ru.vtb.spm.afsnotificationadapter.util.logger.LogUtils;
import ru.vtb.spm.afsnotificationadapter.util.metrics.MetricUtil;

import static ru.vtb.spm.afsnotificationadapter.util.logger.LogTag.OSN_IN_1378;

@Slf4j
@Service
@RequiredArgsConstructor
public class OsnKafkaConsumerService {

    private final ObjectMapper mapper;
    private final OsnKafkaProperties properties;
    private final OsnService osnService;

    @KafkaListener(
        topics = "${osn.kafka.sms.consumer.topic}",
        groupId = "#{@osnKafkaProperties.consumer.groupId + '-' + @osnKafkaProperties.consumer.instanceId}",
        containerFactory = "osnKafkaListenerContainerFactory"
    )
    public void receiveOsnResponse(String message, Acknowledgment ack) {
        String topic = properties.getConsumer().getTopic();

        try {
            OsnKafkaResponseDto osnResponse = mapper.readValue(message, OsnKafkaResponseDto.class);
            if (StringUtils.hasText(osnResponse.getId())
                && osnResponse.getId().startsWith(OsnPrefix.AFS.toString()))
            {
                LogUtils.kafkaReceiveMessageSuccess(OSN_IN_1378, topic, osnResponse.getId(), osnResponse);
                osnService.receiveResponse(osnResponse);
                MetricUtil.kafkaReadOsnSuccessCounter.increment();
                ack.acknowledge();
            } else {
                log.debug("Пропускаем сообщение из топика {}: id не относится к AFS, id={}",
                          topic,
                          osnResponse.getId());
                ack.acknowledge();
            }
        } catch (Exception e) {
            LogUtils.kafkaReceiveMessageError(OSN_IN_1378, topic, e);
            MetricUtil.kafkaReadOsnErrorCounter.increment();
            throw new IllegalStateException("Ошибка обработки сообщения из Kafka топика " + topic, e);
        }
    }
}
