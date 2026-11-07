# homelab - anhtungcanhmo

My personal self-hosted homelab on a repurposed desktop, running services covering
media management, photo backup, cloud storage, game servers, and remote access.

[![OS](https://img.shields.io/badge/OS-CachyOS_%28Arch%29-00C7B7?logo=archlinux&logoColor=white)](https://cachyos.org)
[![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)](https://www.docker.com)
[![Tailscale](https://img.shields.io/badge/Tailscale-242424?logo=tailscale&logoColor=white)](https://tailscale.com)
[![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white)](https://www.cloudflare.com)

---

## Hardware

| Component | Spec |
|-----------|------|
| CPU | Intel Core i7-4770 (4/8 Haswell) |
| RAM | 16 GB DDR3 1600MHz (+15.5 GB swap) |
| GPU | Intel HD Graphics 4600 + ~~NVIDIA GeForce GT 730~~|
| OS disk | 120 GB SSD (btrfs) |
| Media | 3 TB merged (2 TB + 1 TB HDDs) |
| Backup | 500 GB HDD |

## Services

### Media Streaming & Managing
`Jellyfin` · `Radarr` · `Sonarr` · `Bazarr` · `Prowlarr` · `qBittorrent` ·
`Jellyseerr` · `Jellystat` · `Lingarr`

A fully automated *arr stack that covers: requests, downloads, subtitle translation, and delivery to
Jellyfin with hardware-accelerated transcoding.

### Photos & Cloud
`Immich` · `Nextcloud` · `Filebrowser` · `Samba`

Photo library backup and a personal cloud drive.

### Game Server
`Crafty Controller` · `Minecraft`

Minecraft server management with scheduled backups.

### Security & Remote Access
`Vaultwarden` · `AdGuard` · `Nginx PM` · `Cloudflare Tunnel` · `Tailscale`

Password management, DNS-level ad blocking, and remote access via VPN mesh and
public tunnel.

### Monitoring & Dashboard
`Homepage` · `Beszel` · `Uptime Kuma`

Service dashboard, system metrics, and uptime monitoring.
