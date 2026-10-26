# 🐕 Watchdog - Homelab Monitoring Node

## Overview

Watchdog is a dedicated monitoring node built on an Orange Pi 3 LTS. It provides visibility into homelab service availability and system health, helping me monitor infrastructure independently of the services being monitored.

## Hardware & Technologies

- **Hardware:** Orange Pi 3 LTS
- **Monitoring:** Uptime Kuma
- **System metrics:** Glances
- **Notifications:** Discord
- **Environment:** Linux and homelab infrastructure

## Monitoring & Observability

### Uptime Kuma

Uptime Kuma provides service availability monitoring, allowing me to check whether configured services and endpoints are responding.

### Glances

Glances provides system-level monitoring and visibility into resource usage on systems where it is configured and accessible.

### Discord Notifications

Discord is used as a notification channel for monitoring events, making it easier to receive alerts without continuously checking the monitoring dashboard.

## Design & Purpose

Watchdog is designed as a dedicated monitoring node, separating monitoring responsibilities from the applications and services being monitored.

This setup helps me develop practical experience with:

- Service availability monitoring.
- System resource monitoring.
- Alerting and notification integrations.
- Dedicated monitoring infrastructure.
- Troubleshooting service outages and connectivity issues.

## Screenshots & Evidence

See [Watchdog - Evidence](Screenshots/Watchdog-monitoring.md) for screenshots of the monitoring dashboard, system metrics, and service availability.

## Key Takeaway

Watchdog demonstrates how a small single-board computer can provide a dedicated monitoring and alerting layer for a self-hosted infrastructure environment.
