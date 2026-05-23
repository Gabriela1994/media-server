# Media Server & Observabilidad con Docker

Este proyecto consiste en una infraestructura de media server y monitoreo centralizado desplegada con Docker Compose, integrando múltiples servicios para automatizar la descarga, organización y reproducción de contenido multimedia, además de incorporar observabilidad completa del entorno.

La arquitectura conecta servicios de streaming y automatización como Jellyfin, Radarr, Prowlarr y qBittorrent, permitiendo gestionar películas y descargas de forma automatizada mediante indexers y clientes torrent.

Además, el proyecto implementa una stack de monitoreo y métricas utilizando Grafana, Prometheus y cAdvisor para visualizar el estado de los contenedores, consumo de CPU, memoria, red y almacenamiento en tiempo real.

Para el enrutamiento y acceso a los servicios se utiliza Traefik como reverse proxy, permitiendo manejar dominios locales, routing dinámico y exposición centralizada de todos los servicios de la infraestructura.

---

# Servicios Integrados

## Media Server

- **Jellyfin** → Servidor multimedia autohospedado
- **Radarr** → Gestión automática de películas
- **Prowlarr** → Administración de indexers
- **qBittorrent** → Cliente torrent para descargas automatizadas

---

## Observabilidad y Monitoreo

- **Grafana** → Visualización de métricas y dashboards
- **Prometheus** → Recolección y almacenamiento de métricas
- **cAdvisor** → Monitoreo de recursos de contenedores Docker

---

## Networking & Reverse Proxy

- **Traefik** → Reverse proxy y enrutamiento dinámico entre servicios

---

# Características Principales

- Infraestructura completamente dockerizada con Docker Compose
- Automatización de descargas y organización multimedia
- Monitoreo en tiempo real de contenedores Docker
- Dashboards personalizados en Grafana
- Routing dinámico mediante Traefik
- Comunicación interna entre servicios mediante redes Docker
- Acceso centralizado mediante dominios locales
- Arquitectura orientada a prácticas DevOps y self-hosting

---

# Objetivo del Proyecto

El objetivo principal es construir una infraestructura moderna de self-hosting que combine:

- Automatización de contenido multimedia
- Centralización de servicios
- Observabilidad y monitoreo
- Networking interno entre contenedores
- Buenas prácticas DevOps utilizando Docker y reverse proxies

Este proyecto sirve como práctica de integración de servicios, networking entre contenedores, monitoreo de infraestructura y despliegue de aplicaciones autohospedadas.

---

# Tecnologías Utilizadas

- Docker
- Docker Compose
- Traefik
- Jellyfin
- Radarr
- Prowlarr
- qBittorrent
- Grafana
- Prometheus
- cAdvisor

---
