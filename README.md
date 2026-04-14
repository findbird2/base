# neural-network-hydroaccustic-signal-classification

This project represents a neural network for classifying hydroaccustic signals.

Hydroaccustic signals are represented by the spectre of the signal

Deeplearning4J used

@Service
@Slf4j
@RequiredArgsConstructor
public class ServerMetricsExecutor {
    private final CpuUsageService cpuUsageService;
    private final MemoryUsageService memoryUsageService;
    private final DiskUsageService diskUsageService;
    private final NetworkDownloadingUnloadingSpeedService networkDownloadingUnloadingSpeedService;
    private final ApplicationService applicationService;

    private final ApplicationDiscovery applicationDiscovery;

    @PostConstruct
    public void getCpuUsage() {
        var app =  applicationDiscovery.getResultCommand();
        var cpu = cpuUsageService.getResultCommand();
        var mem = memoryUsageService.getResultCommand();
        var disk = diskUsageService.getResultCommand();
        log.info("Тест запроса: " + app.toString());
        log.info(cpu.toString());
        log.info(mem.toString());
        log.info(disk.toString());
    }
}
