## Overview

This project demonstrates the deployment of an infrastructure monitoring platform using Docker, Prometheus, and Grafana on Ubuntu Linux.

The monitoring stack was deployed inside a VirtualBox Ubuntu virtual machine.

# Architecture Diagram

+-------------------------+
| Windows Host Machine    |
|                         |
|  Cisco Packet Tracer    |
|                         |
|  VirtualBox             |
|      │                  |
|      ▼                  |
| Ubuntu Linux VM         |
|                         |
| Docker                  |
| ├── Prometheus          |
| └── Grafana             |
+-------------------------+

# Components

## Ubuntu Linux

Ubuntu serves as the operating system hosting Docker and all monitoring services.

Responsibilities:

- Operating System
- Package Management
- Docker Runtime

## Docker

Docker runs each monitoring application inside isolated containers.

Containers used:

- Prometheus
- Grafana

Benefits:

- Easy deployment
- Lightweight
- Portable
- Simple management

## Prometheus

Prometheus collects and stores metrics.

Responsibilities:

- Metric collection
- Time-series database
- Target monitoring

## Grafana

Grafana visualizes the metrics collected by Prometheus.

Responsibilities:

- Dashboards
- Charts
- Performance visualization

# Current Workflow

Current implementation:

Ubuntu

↓

Docker

↓

Prometheus

↓

Grafana Dashboard


# Planned Workflow

Future implementation:

Cisco Router/Switch

↓

SNMP Exporter

↓

Prometheus

↓

Grafana

↓

Network Administrator


# Project Limitation

Cisco Packet Tracer could not be directly integrated with Prometheus because Packet Tracer is a simulator and does not expose metrics through exporters or SNMP in the same way as real devices.

Therefore, this project focused on successfully deploying the monitoring platform while preparing for future integration with real network devices.
