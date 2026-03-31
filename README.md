# neural-network-hydroaccustic-signal-classification

This project represents a neural network for classifying hydroaccustic signals.

Hydroaccustic signals are represented by the spectre of the signal

Deeplearning4J used

[2026-03-31 12:57:46,085] ERROR Exiting Kafka due to fatal exception (kafka.Kafka$)

java.lang.IllegalArgumentException: requirement failed: inter.broker.listener.name must be a listener name defined in advertised.listeners. The valid options based on currently configured listeners are SSL

	at scala.Predef$.require(Predef.scala:337)

	at kafka.server.KafkaConfig.validateValues(KafkaConfig.scala:2315)

	at kafka.server.KafkaConfig.<init>(KafkaConfig.scala:2160)

	at kafka.server.KafkaConfig.<init>(KafkaConfig.scala:1569)

	at kafka.Kafka$.buildServer(Kafka.scala:72)

	at kafka.Kafka$.main(Kafka.scala:91)

	at kafka.Kafka.main(Kafka.scala)
