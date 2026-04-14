# neural-network-hydroaccustic-signal-classification

This project represents a neural network for classifying hydroaccustic signals.

Hydroaccustic signals are represented by the spectre of the signal

Deeplearning4J used

@Slf4j
@Service
@RequiredArgsConstructor
public class ApplicationDiscovery implements ConsoleCommand {
    private final ObjectMapper objectMapper = new ObjectMapper();
    private final ScriptConfig scriptConfig;

    @Override
    public ApplicationDiscoveryConsole getResultCommand() {
        var discoveryResult = executeCommand(
                ExecuteCommandTypeUtils.getExecuteCommandType(), scriptConfig.getDiscoveryCommand()
        );
        log.info("Discovery result: {}", discoveryResult.getOutput());
        ApplicationDiscoveryConsole discoveryConsole = new ApplicationDiscoveryConsole();
        try {
            return discoveryConsole.convertToObject(discoveryResult, objectMapper);
        } catch (JsonProcessingException e) {
            throw new ConversionException("Не получилось сделать объект из json", e);
        }
    }
}
        log.info(mem.toString());
        log.info(disk.toString());
    }
}
