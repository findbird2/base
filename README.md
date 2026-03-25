# neural-network-hydroaccustic-signal-classification

This project represents a neural network for classifying hydroaccustic signals.

Hydroaccustic signals are represented by the spectre of the signal

Deeplearning4J used

    private FindIdApiGetByPeriodPost200ResponseResults getByPeriod(LocalDateTime dateFrom,
                                                                  LocalDateTime dateTo) {
        var offset = LocalDateTime.now()
                                  .atZone(ZoneId.systemDefault())
                                  .getOffset();
        var request = new FindIdApiGetByPeriodPostRequest();
        request.dateFrom(dateFrom.atOffset(offset));
        request.dateTo(dateTo.atOffset(offset));

        log.info("[{}] Requesting data for the period from {} to {}", LogTag.FID_MESSAGE, dateFrom, dateTo);
        return auditSender.sendResult(AUDIT_GETBYPERIOD, () -> getData(request));
    }

