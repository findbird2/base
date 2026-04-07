# neural-network-hydroaccustic-signal-classification

This project represents a neural network for classifying hydroaccustic signals.

Hydroaccustic signals are represented by the spectre of the signal

Deeplearning4J used

package ru.vtb.spm.afsnotificationadapter.config.redis;

import jakarta.validation.constraints.NotBlank;
import jakarta.validation.constraints.NotNull;
import java.util.List;
import lombok.Data;
import org.springframework.boot.context.properties.ConfigurationProperties;
import org.springframework.context.annotation.Configuration;
import org.springframework.validation.annotation.Validated;

@Configuration
@ConfigurationProperties(prefix = "redis")
@Data
@Validated
public class RedisProperties {

    @NotBlank(message = "Необходимо указать имя мастер-ноды")
    private String master;
    @NotNull(message = "Необходимо указать адреса сентинел-нод")
    private List<String> sentinelNodes;
    @NotBlank(message = "Необходимо указать имя пользователя")
    private String username;
    @NotBlank(message = "Необходимо указать пароль пользователя")
    private String password;
}
