# neural-network-hydroaccustic-signal-classification

This project represents a neural network for classifying hydroaccustic signals.

Hydroaccustic signals are represented by the spectre of the signal

Deeplearning4J used

@Service
public class KafkaSmsStatusAwaiter {

    private final ConcurrentMap<String, CompletableFuture<OsnKafkaSmsResponseStatus>> awaitingStatuses =
            new ConcurrentHashMap<>();

    public CompletableFuture<OsnKafkaSmsResponseStatus> register(String messageId) {
        CompletableFuture<OsnKafkaSmsResponseStatus> future = new CompletableFuture<>();
        CompletableFuture<OsnKafkaSmsResponseStatus> previous = awaitingStatuses.put(messageId, future);
        if (previous != null) {
            previous.complete(OsnKafkaSmsResponseStatus.UNKNOWN);
        }
        return future;
    }

