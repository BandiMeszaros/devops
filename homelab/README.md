# Homelab Services

This repository contains the Docker Compose configurations for the services running on my self-hosted homelab server.

## Hardware & Environment
* **Hardware:** [Raspberry Pi 5](https://www.raspberrypi.com/products/raspberry-pi-5/)
* **Storage:** NVMe SSD via SSD Extension Hat
* **Orchestration:** [Coolify](https://coolify.io/) — a self-hosted, open-source platform-as-a-service (PaaS) used to orchestrate and manage all services.

## Deployment Setup
Each `.yaml` file in this directory represents a standalone Docker Compose configuration managed by Coolify. Coolify connects to this Git repository, automatically pulls changes, and redeploys the services, ensuring a clean GitOps workflow.

## Key Links
* [Coolify Documentation](https://coolify.io/docs)
* [Raspberry Pi 5 Hardware Specs](https://www.raspberrypi.com/products/raspberry-pi-5/)
* [Docker Compose Reference](https://docs.docker.com/compose/)
