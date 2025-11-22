# 🏠 My Homelab

Welcome to my personal homelab! This repository contains the Docker Compose for my docker stacks.

---

## ⚙️ Core Infrastructure

These are the essential services that form the backbone of the homelab, handling networking, security, automation, and monitoring.

| Service | Description |
| :--- | :--- |
| **Traefik** | A modern reverse proxy and load balancer that handles all incoming traffic and routes it to the correct service. |
| **Authelia** | Provides single sign-on (SSO) and two-factor authentication to secure access to the services. |
| **Homepage** | A simple and clean application dashboard that gives me easy access to all my services from one place. |
| **Home Assistant** | The heart of my smart home, automating and connecting all my IoT devices for local and private control. |
| **Zigbee2MQTT** | Bridges my Zigbee devices to the network, allowing for local control without proprietary hubs. |
| **Mosquitto (MQTT)** | A lightweight MQTT message broker that enables communication between my IoT devices and Home Assistant. |
| **Node Exporter** | A Prometheus exporter for hardware and OS metrics, keeping an eye on the health of the server. |

---

## 🚀 Media and Content Suite

This collection of services is focused on media management, streaming, and acquisition.

| Service | Description |
| :--- | :--- |
| **Jellyfin** | A free software media system that lets me manage and stream my movies, shows, music, and photos. |
| **Jellyseerr** | A request management and media discovery tool for the Jellyfin ecosystem. |
| **The *Arr Stack** | A suite of tools for managing and automatically downloading content: |
| &nbsp;&nbsp; • **Radarr** | Manages my movie collection. |
| &nbsp;&nbsp; • **Sonarr** | Manages my TV show and anime collections. |
| &nbsp;&nbsp; • **Prowlarr** | Manages indexers for the other *Arr services. |
| &nbsp;&nbsp; • **Profilarr** | Syncs settings and profiles across the *Arr stack. |
| &nbsp;&nbsp; • **Suggestarr** | Provides content suggestions and recommendations. |
| **qBittorrent** | A reliable and lightweight BitTorrent client for acquiring content. |
| **MeTube** | A web GUI for downloading video and audio from YouTube and other sites. |

---

## 🛠️ Applications & Utilities

A collection of powerful tools and applications that I find useful.

| Service | Description |
| :--- | :--- |
| **Immich** | A self-hosted solution for backing up and viewing photos and videos, keeping my memories private. |
| **n8n** | A powerful workflow automation tool that connects different services and APIs to create custom automations. |
| **pgAdmin4** | A web-based administration tool for PostgreSQL databases, providing a powerful interface for database management. |
| **Stirling-PDF** | A versatile web-based tool for all kinds of PDF manipulation. |
| **File Browser** | A simple and effective web-based file manager. |
| **Frigate** | A smart Network Video Recorder (NVR) with real-time AI object detection for my security cameras. |
| **IT-Tools** | A handy collection of online tools for developers, all hosted locally. |
| **Piper** | A fast, local neural text-to-speech system, often used with Home Assistant. |
| **Morphos** | A web-based tool for quick and easy file conversions. |

---

This setup is my digital playground, and I'm always experimenting with new and exciting self-hosted applications.

