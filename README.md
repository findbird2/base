# neural-network-hydroaccustic-signal-classification

This project represents a neural network for classifying hydroaccustic signals.

Hydroaccustic signals are represented by the spectre of the signal

Deeplearning4J used

    package ru.vtb.spm.afsnotificationadapter.config.kafka.osn;

import jakarta.validation.Valid;
import jakarta.validation.constraints.NotNull;
import lombok.Data;
import org.springframework.boot.context.properties.ConfigurationProperties;
import org.springframework.context.annotation.Configuration;
import org.springframework.validation.annotation.Validated;

@Configuration
@ConfigurationProperties(prefix = "osn.kafka.sms")
@Data
@Validated
public class OsnKafkaProperties {

    @Valid
    private Consumer consumer;

    @Data
    public static class Consumer {

        @NotNull(message = "Необходимо указать хост для консьюмера Kafka OSN (1378)")
        private String bootstrap;
        @NotNull(message = "Необходимо указать ID группы консьюмеров для Kafka OSN (1378)")
        private String groupId;
        @NotNull(message = "Необходимо указать топик для консьюмера Kafka OSN (1378)")
        private String topic;
        private Ssl ssl;

        @Data
        public static class Ssl {

            private boolean enabled;
            private String trustStorePath;
            private String trustStorePassword;
            private String keyStorePath;
            private String keyStorePassword;
        }
    }


}
