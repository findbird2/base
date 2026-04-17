# neural-network-hydroaccustic-signal-classification

This project represents a neural network for classifying hydroaccustic signals.

Hydroaccustic signals are represented by the spectre of the signal

Deeplearning4J used

   private OsnKafkaSmsResponseStatus waitForStatus(CompletableFuture<OsnKafkaSmsResponseStatus> statusFuture,
                                                    String requestId)
            throws InterruptedException, ExecutionException {
        Duration timeout = afsKafkaSmsConnectionProperties.getDelayForStatusFromOsn();
        long timeoutMs = (timeout == null || timeout.isNegative() || timeout.isZero())
                ? 1000L
                : timeout.toMillis();
        try {
            //TODO Здесь не дождались статуса из Kafka
            return statusFuture.get(timeoutMs, TimeUnit.MILLISECONDS);
        } catch (TimeoutException e) {
            log.warn("[{}][{}] Не дождались статуса из Kafka за {} мс.",
                     LogTag.KAFKA_SMS,
                     requestId,
                     timeoutMs);
            return OsnKafkaSmsResponseStatus.UNKNOWN;
        }
    }
