# neural-network-hydroaccustic-signal-classification

This project represents a neural network for classifying hydroaccustic signals.

Hydroaccustic signals are represented by the spectre of the signal

Deeplearning4J used

Для audit Kafka можно использовать стандартный SSL-блок Spring Kafka:

audit:
  kafka:
    properties:
      security.protocol: SSL
    ssl:
      key-store-location: file:///opt/get-device-id/keys/audit.client.keystore.pfx
      key-store-password: ${AUDIT_KAFKA_SSL_KEY_STORE_PASSWORD}
      key-store-type: PKCS12
      key-password: ${AUDIT_KAFKA_SSL_KEY_PASSWORD}
      trust-store-location: file:///opt/get-device-id/keys/audit.client.truststore.pfx
      trust-store-password: ${AUDIT_KAFKA_SSL_TRUST_STORE_PASSWORD}
      trust-store-type: PKCS12
Для standby-канала аналогично: audit.standinKafka.ssl.* и AUDIT_STANDIN_KAFKA_SECURITY_PROTOCOL=SSL

