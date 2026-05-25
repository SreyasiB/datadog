# GCP Cloud Run, Bigtable Observability with Datadog

## Overview

This project demonstrates an observability setup for monitoring a containerized application deployed on Google Cloud Run with Google Cloud Bigtable as the backend datastore.

The monitoring solution was built using Datadog dashboards and alerting mechanisms to improve operational visibility, reliability, and performance tracking.

---

## Architecture

Client Request → Cloud Run Service → Bigtable → Datadog Monitoring & Alerting

---

## Technologies Used

- Google Cloud Platform (GCP)
- Cloud Run
- Bigtable
- Datadog

---

## Prerequisites

- Datadog integration with GCP project where the Cloud Run service is hosted

---

## Dashboard Features

### Cloud Run Monitoring
- Request count
- Error count
- Request latency (P95/P99)
- CPU utilization
- Memory utilization
- Container instance scaling
- Max concurren requests

### Bigtable Monitoring
- Read/write request count
- Error count
- Read/write latency (P95/P99)
- CPU usage
- Storage utilization

### Operational Insights
- Service health visibility
- Performance bottleneck identification
- Traffic pattern analysis
- Alert-driven incident response

---

## Alerting Strategy

| Alert | Threshold |
|------|------|
| High 5xx Error Rate | > 2% |
| High Latency | P95 > 1 second |
| CPU Saturation | > 80% |
| Bigtable Throttling | Spike detection |

---

## Key Learnings

- Designing effective dashboards
- Creating actionable alerts
- Monitoring serverless workloads
- Correlating application and datastore metrics
- Improving observability for distributed systems

---

## Disclaimer

This repository is a generalized and sanitized implementation created for learning and portfolio purposes. No client-sensitive information, infrastructure identifiers, or proprietary configurations are included.
