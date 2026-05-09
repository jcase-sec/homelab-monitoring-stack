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

## Architecture

The monitoring environment was designed around segmented infrastructure and service isolation principles.

### Core Components
- Proxmox host running dedicated LXCs
- Docker-based service deployment
- Prometheus for metric collection
- Grafana for visualization and dashboards
- Uptime Kuma for service health monitoring
- SNMP Exporter for network device telemetry
- pfSense-based VLAN segmentation

### Monitoring Goals
- Infrastructure visibility
- Resource utilization tracking
- Network device monitoring
- Service uptime validation
- Operational observability

### Network Design Considerations
- Monitoring services isolated within dedicated server infrastructure
- Internal-only access model
- Reverse proxy architecture for centralized service access
- Segmented VLAN approach to reduce blast radius

## Security Considerations
- Services segmented across VLANS
- Internal-only service exposure
- Reverse proxy architecture utilized for centralized access
- Unprivileged container deployment strategy
