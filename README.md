# neural-network-hydroaccustic-signal-classification

This project represents a neural network for classifying hydroaccustic signals.

Hydroaccustic signals are represented by the spectre of the signal

Deeplearning4J used

    private void saveResponse(String clientId, OsnKafkaResponseDto osnKafkaResponseDto) {
        //TODO Проверить наличие элементов в osnKafkaResponseDto
        DateTimeFormatter formatter = DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss");

        SmsStatusEntity smsStatusEntity = new SmsStatusEntity();
        smsStatusEntity.setXMessageIdSms(osnKafkaResponseDto.getId());
        smsStatusEntity.setStatus(osnKafkaResponseDto.getStatus());
        smsStatusEntity.setDeliveryMethod(osnKafkaResponseDto.getDeliveryMethod());
        smsStatusEntity.setSource(osnKafkaResponseDto.getSource());
        smsStatusEntity.setClientId(osnKafkaResponseDto.getClientId());
        smsStatusEntity.setPhone(osnKafkaResponseDto.getPhone());
        smsStatusEntity.setCreated(LocalDateTime.now());
        smsStatusEntity.setTimeDelivery(
                LocalDateTime.parse(osnKafkaResponseDto.getTimeDelivery(), formatter));

        smsStatusRepository.save(smsStatusEntity);

    }
