# Мониторинг и наблюдаемость

## Навигация

- **[← Главная](README.md)** - обзор тестового задания
- **[Требования](REQUIREMENTS.md)** - функциональные и нефункциональные требования
- **[Архитектура](ARCHITECTURE.md)** - компоненты системы и их взаимодействие  
- **[Качества системы](SQA.md)** - масштабирование, отказоустойчивость, производительность
- **Мониторинг** - метрики, логирование, алерты
- **[Вопросы](QUESTIONS.md)** - список вопросов для детализации требований

---

## Метрики (Prometheus)
```
# Пропускная способность
events_received_total
events_processed_total
reactions_executed_total

# Производительность
event_processing_duration_seconds
api_request_duration_seconds
queue_lag

# Ошибки
failed_events_total
circuit_breaker_state
external_api_errors_total
```

## Логирование (ELK Stack)
- Structured logging (JSON)
- Correlation IDs для трассировки
- Real-time alerting

## Трассировка (OpenTelemetry)
- Distributed tracing
- Latency analysis
- Performance bottleneck identification
