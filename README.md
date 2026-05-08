# Homelab Monitoring Stack

## Overview
Designed and deployed a monitoring and observability stack within a segmented Proxmox homelab environment.

## Technologies Used
- Proxmox
- Docker
- Grafana
- Prometheus
- Uptime Kuma
- SNMP Exporter
-  pfSense

## Goals
- Improve infrastructure visibility
- Monitor service uptime and resource utilization
- Learn enterprise-style observability concepts
- Implement segmented and security-conscious architecture

## Current Focus
- Grafana dashboard refinement
- SNMP monitoring expansion
- Service health monitoring
- Network visibility

## Security Considerations
- Services segmented across VLANS
- Internal-only service exposure
- Reverse proxy architecture utilized for centralized access
- Unprivileged container deployment strategy
