# neural-network-hydroaccustic-signal-classification

This project represents a neural network for classifying hydroaccustic signals.

Hydroaccustic signals are represented by the spectre of the signal

Deeplearning4J used

    public Future<SpmResponseDto> process(SpmRequestDto dto) {
       return executorService.submit(() -> {
                transactionMilestoneManagerKafkaSms.commitData(dto);
                return SpmResponseDto.builder()
                        .success(true)
                        .httpStatus(HttpStatus.OK)
                        .message(REQUEST_SUCCESSFUL)
                        .xMessageId(dto.getXMessageID())
                        .build();
        });
    }
