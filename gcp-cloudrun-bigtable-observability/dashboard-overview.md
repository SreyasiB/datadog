## Dashboard Objectives

The dashboard was designed to provide:

- Service health visibility
- Application performance monitoring
- Infrastructure utilization tracking
- Error detection
- Capacity monitoring
- Incident troubleshooting support
- Operational insights for autoscaling workloads

It also implements template variable "Project_id" using which we can reuse the same dashboard for other GCP projects.

<img width="1600" height="538" alt="Image" src="https://github.com/user-attachments/assets/de488d51-94bd-4e8f-8f94-95b15f1a2773" />

## Metrics used in Datadog

#### Cloud Run 
```text
gcp.run.request_count
gcp.run.request_latencies
gcp.run.container.cpu.utilizations
gcp.run.container.memory.utilizations
gcp.run.container.containers
gcp.run.container.max_request_concurrencies.avg
```
#### Cloud Bigtable
```text
gcp.bigtable.server.request_count
gcp.bigtable.server.error_count
gcp.bigtable.server.latencies
gcp.bigtable.cluster.cpu_load
gcp.bigtable.cluster.storage_utilization
```
