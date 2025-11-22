# Odoo 16 Docker Setup

This repository contains a Docker setup for **Odoo 16** with custom addons and PostgreSQL.  
It allows you to run Odoo in a containerized environment and optionally push the image to Docker Hub.

---

## Contents

- `Dockerfile` – builds a custom Odoo 16 image with your addons
- `docker-compose.yml` – orchestrates Odoo + PostgreSQL containers
- `.env` – environment variables for Odoo and PostgreSQL
- `README.md` – setup guide

---

## Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)
- Docker Hub account (if you want to push the image)

---

## Setup Instructions

### 1. Build the custom Odoo image
Make sure your custom addons are in the `addons/` folder.

```bash
docker build -t abdallahmekky/odoo16:latest .
```
