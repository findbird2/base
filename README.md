# neural-network-hydroaccustic-signal-classification

This project represents a neural network for classifying hydroaccustic signals.

Hydroaccustic signals are represented by the spectre of the signal

Deeplearning4J used

    public boolean complete(String messageId, OsnKafkaSmsResponseStatus status) {
        CompletableFuture<OsnKafkaSmsResponseStatus> future = awaitingStatuses.get(messageId);
        if (future == null) {
            return false;
        }
        boolean completed = future.complete(status);
        if (completed) {
            awaitingStatuses.remove(messageId, future);
        }
        return completed;
    }

