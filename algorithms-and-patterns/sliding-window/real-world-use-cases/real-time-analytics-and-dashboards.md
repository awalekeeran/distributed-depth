# Real‑Time Analytics & Dashboards
Any system that shows “last 1 min/5 mins/1 hour” metrics uses sliding windows.

Examples
- Grafana dashboards
- Prometheus rate() and increase()
- Datadog rolling metrics
- ELK (Elasticsearch) rolling log aggregation

Use cases
- Count errors in last 5 minutes
- Average latency in last 1 minute
- Active users in last 10 minutes
- CPU/memory average in last X seconds
