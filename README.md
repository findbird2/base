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

audit:
  default-resolver:
    channel: chanel
    sub: sub
  kafka:
    bootstrap-servers: localhost:9092
    properties:
      security.protocol: ${AUDIT_KAFKA_SECURITY_PROTOCOL:PLAINTEXT}
    consumer:
      properties:
        security.protocol: ${AUDIT_KAFKA_SECURITY_PROTOCOL:PLAINTEXT}
    producer:
      properties:
        security.protocol: ${AUDIT_KAFKA_SECURITY_PROTOCOL:PLAINTEXT}
    # Для SSL AUDIT_KAFKA_SECURITY_PROTOCOL
#    ssl:
#      key-store-location: file:///opt/get-device-id/keys/audit.client.keystore.pfx
#      key-store-password: password
#      key-store-type: PKCS12
#      key-password: password
#      trust-store-location: file:///opt/get-device-id/keys/audit.client.truststore.pfx
#      trust-store-password: password
#      trust-store-type: PKCS12
  standinKafka:
    bootstrap-servers: localhost:9092
    properties:
      security.protocol: ${AUDIT_STANDIN_KAFKA_SECURITY_PROTOCOL:PLAINTEXT}
    consumer:
      properties:
        security.protocol: ${AUDIT_STANDIN_KAFKA_SECURITY_PROTOCOL:PLAINTEXT}
    producer:
      properties:
        security.protocol: ${AUDIT_STANDIN_KAFKA_SECURITY_PROTOCOL:PLAINTEXT}
    # Для SSL AUDIT_STANDIN_KAFKA_SECURITY_PROTOCOL
#    ssl:
#      key-store-location: file:///opt/get-device-id/keys/audit.standin.client.keystore.pfx
#      key-store-password: password
#      key-store-type: PKCS12
#      key-password: password
#      trust-store-location: file:///opt/get-device-id/keys/audit.standin.client.truststore.pfx
#      trust-store-password: password
#      trust-store-type: PKCS12

audit-events:
  auditEventCodeList:
    - event-code: "AFS_AUDIT_FINDID_NSPK_LOGIN"
      resolvers: ChannelPropertiesTsauResolver, LoginPropertiesTsauResolver
      list-resolvers: MsPropertiesResolverList
      schema: "administration"
      audit-event-start:
        oper_name: "Найди.ID; Старт логики метода авторизации на платформе НСПК"
      audit-event-success:
        oper_name: "Найди.ID; Выполнение логики метода авторизации на платформе НСПК завершилось успешно"
      audit-event-failure:
        oper_name: "Найди.ID; Выполнение логики метода авторизации на платформе НСПК завершилось с ошибкой"

    - event-code: "AFS_AUDIT_FINDID_NSPK_VALIDATE"
      resolvers: ChannelPropertiesTsauResolver, LoginPropertiesTsauResolver
      list-resolvers: MsPropertiesResolverList
      schema: "administration"
      audit-event-start:
        oper_name: "Найди.ID; Старт логики метода валидации токена авторизации на платформе НСПК"
      audit-event-success:
        oper_name: "Найди.ID; Выполнение логики метода валидации токена авторизации на платформе НСПК завершилось успешно"
      audit-event-failure:
        oper_name: "Найди.ID; Выполнение логики метода валидации токена авторизации на платформе НСПК завершилось с ошибкой"

    - event-code: "AFS_AUDIT_FINDID_NSPK_GETBYPERIOD"
      resolvers: ChannelPropertiesTsauResolver, LoginPropertiesTsauResolver
      list-resolvers: MsPropertiesResolverList
      schema: "administration"
      audit-event-start:
        oper_name: "Найди.ID; Старт логики метода получения записей из справочника подозрительных устройств на платформе НСПК"
      audit-event-success:
        oper_name: "Найди.ID; Выполнение логики метода получения записей из справочника подозрительных устройств на платформе НСПК завершилось успешно"
      audit-event-failure:
        oper_name: "Найди.ID; Выполнение логики метода получения записей из справочника подозрительных устройств на платформе НСПК завершилось с ошибкой"




