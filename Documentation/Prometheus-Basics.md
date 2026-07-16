## What is Prometheus?

Prometheus is an open-source monitoring and alerting toolkit that collects metrics from configured targets and stores them as time-series data.

It is widely used for monitoring servers, containers, cloud infrastructure, and network devices.

# Why Prometheus?

Prometheus provides:

- Powerful metric collection
- Time-series storage
- Query language (PromQL)
- Easy integration with Grafana
- Flexible monitoring architecture

# Key Components

## Targets

Systems from which Prometheus collects metrics.

Examples:

- Linux servers
- Docker containers
- Network devices (using exporters)

## Metrics

Numerical values representing system performance.

Examples:

- CPU usage
- Memory usage
- Disk usage
- Network traffic

## Scraping

The process by which Prometheus periodically collects metrics from configured targets.

## PromQL

PromQL (Prometheus Query Language) is used to retrieve and analyze collected metrics.

# Project Implementation

In this project:

- Prometheus was deployed using Docker.
- The web interface was successfully accessed.
- Basic configuration was performed.
- Prometheus was prepared for future integration with exporters.

# Skills Learned

- Monitoring concepts
- Metrics collection
- Target configuration
- Prometheus architecture
