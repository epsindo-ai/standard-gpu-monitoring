# GPU Monitoring with Prometheus, Grafana, and DCGM Exporter

This repository provides a Docker Compose setup to monitor NVIDIA GPU metrics using Prometheus, Grafana, and DCGM Exporter.

## Prerequisites

- Docker
- NVIDIA drivers installed on the host machine
- `nvidia-docker2` installed to support GPU containers

## Setup Instructions

1. Clone the repository.
2. Ensure that the `nvidia-docker2` runtime is properly installed to allow GPU access for the DCGM Exporter container.
3. Run the following command to start Prometheus, Grafana, and the DCGM Exporter:

   ```bash
   docker-compose up -d
