# Sliding Window in System Design

## System Design Use-Cases
- ### API Rate Limiting
  Patterns:
  - fixed window counter
  - sliding log
  - sliding window rate limiter
- ### Real-time Monitoring / Analytics
  - number of failed logins in last 10 mins
  - CPU average in last 5 mins
  - Requests per minute(RPM)
- ### Stream Processing (Kafka, Spark, Flink)
  Sliding window computes
  - rolling sums
  - rolling counts
  - anomaly detection
  
  Used in:
  - Streaming ETL jobs
  - Clickstream analytics
  - fraud detection
