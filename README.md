# neural-network-hydroaccustic-signal-classification

This project represents a neural network for classifying hydroaccustic signals.

Hydroaccustic signals are represented by the spectre of the signal

Deeplearning4J used

package com.vtb.spm.proxy.configuration.theus;

import com.vtb.spm.proxy.configuration.kafka.KafkaSSLConfiguration;
import io.github.agebhar1.micrometer.security.cert.*;
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.boot.autoconfigure.web.ServerProperties;
import org.springframework.context.annotation.Bean;
import org.springframework.context.annotation.Configuration;

@Configuration
public class CertMonConfiguration {

    private final KafkaSSLConfiguration kafkaSSLConfiguration;
    private final ServerProperties serverProperties;

    public CertMonConfiguration(@Autowired(required = false) KafkaSSLConfiguration kafkaSSLConfiguration,
                                @Autowired(required = false) ServerProperties serverProperties) {
        this.kafkaSSLConfiguration = kafkaSSLConfiguration;
        this.serverProperties = serverProperties;
    }

    @Bean
    public X509CertificateExpirationMetrics x509CertificateExpirationMetrics() {
        var tagFactory = new DefaultX509CertificateMetricTagFactory();
        final X509CertificateSource sourceGlobal = X509CertificateSourceComposite.of(new CustomGlobalTrustStoreX509Certificates());
        X509CertificateSource sourceSslApp = null;
        if (serverProperties != null && serverProperties.getSsl() != null && serverProperties.getSsl().isEnabled()) {
            var serverSsl = serverProperties.getSsl();
            sourceSslApp = X509CertificateSourceComposite.of(
                    new CustomGlobalTrustStoreX509Certificates(),
                    new TrustStoreCertificateSource(serverSsl.getTrustStoreType(),
                                                    serverSsl.getTrustStore(),
                                                    serverSsl.getTrustStorePassword()),
                    new TrustStoreCertificateSource(serverSsl.getKeyStoreType(),
                                                    serverSsl.getKeyStore(),
                                                    serverSsl.getKeyStorePassword())
            );
        }
        X509CertificateSource sourceFinal;
        if (kafkaSSLConfiguration != null && kafkaSSLConfiguration.isEnabled()) {
            var sourceCustom = X509CertificateSourceComposite.of(
                    new TrustStoreCertificateSource(
                            kafkaSSLConfiguration.getTrustStoreType(),
                            kafkaSSLConfiguration.getTrustStoreLocation(),
                            kafkaSSLConfiguration.getTrustStorePassword()
                    ),
                    new TrustStoreCertificateSource(
                            kafkaSSLConfiguration.getKeyStoreType(),
                            kafkaSSLConfiguration.getKeyStoreLocation(),
                            kafkaSSLConfiguration.getKeyStorePassword()
                    )
            );
            if (sourceSslApp != null) {
                sourceFinal = X509CertificateSourceComposite.of(sourceGlobal,
                                                                sourceSslApp,
                                                                sourceCustom);
            } else {
                sourceFinal = X509CertificateSourceComposite.of(sourceGlobal,
                                                                sourceCustom);
            }

        } else {
            if (sourceSslApp != null) {
                sourceFinal = X509CertificateSourceComposite.of(sourceGlobal, sourceSslApp);
            } else {
                sourceFinal = X509CertificateSourceComposite.of(sourceGlobal);
            }
        }

        return new X509CertificateExpirationMetrics(tagFactory,
                                                    sourceFinal);
    }
}

