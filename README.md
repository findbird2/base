# neural-network-hydroaccustic-signal-classification

This project represents a neural network for classifying hydroaccustic signals.

Hydroaccustic signals are represented by the spectre of the signal

Deeplearning4J used

docker network create kafka-net && docker run -d --name my_zookeeper --network kafka-net -p 32181:2181 -e ZOOKEEPER_CLIENT_PORT=2181 confluentinc/cp-zookeeper:7.5.0 && docker run -d --name my_kafka --network kafka-net -p 39092:39092 -v C:\Books\store:/etc/kafka/secrets -e KAFKA_BROKER_ID=1 -e KAFKA_ZOOKEEPER_CONNECT=my_zookeeper:2181 -e KAFKA_LISTENERS=SSL://0.0.0.0:39092 -e KAFKA_ADVERTISED_LISTENERS=SSL://localhost:39092 -e KAFKA_LISTENER_SECURITY_PROTOCOL_MAP=SSL:SSL -e KAFKA_SSL_KEYSTORE_FILENAME=parb-server-keystore.jks -e KAFKA_SSL_KEYSTORE_CREDENTIALS=keystore_creds -e KAFKA_SSL_KEY_CREDENTIALS=key_creds -e KAFKA_SSL_TRUSTSTORE_FILENAME=parb-truststore.jks -e KAFKA_SSL_TRUSTSTORE_CREDENTIALS=truststore_creds -e KAFKA_SSL_CLIENT_AUTH=required confluentinc/cp-kafka:7.5.0
