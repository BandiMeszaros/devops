# Homelab

This is a backup repository for my homeserver setup, storing the Docker Compose configurations for my self-hosted services.

> **Note:** These files are tailored to my local environment, host paths, and network setup, and are meant purely as a personal backup rather than a plug-and-play template.

## Services

- `filebrowser_compose.yaml` — [FileBrowser](https://filebrowser.org/) for web-based access to local media storage
- `mqtt.yaml` — [Eclipse Mosquitto](https://mosquitto.org/) MQTT broker
- `tailscale_compose.yaml` — [Tailscale](https://tailscale.com/) client, Nginx reverse proxy, and [Plex](https://www.plex.tv/) media server
- `transmission_compose.yaml` — [Transmission](https://transmissionbt.com/) BitTorrent client

## Hardware & Environment

- **Hardware:** [Raspberry Pi 5](https://www.raspberrypi.com/products/raspberry-pi-5/)
- **Storage:** NVMe SSD via SSD Extension Hat
- **Orchestration:** [Coolify](https://coolify.io/)

## Notes

Each `.yaml` file is a standalone Docker Compose configuration managed through Coolify, with secrets and environment variables configured outside of this repository.
