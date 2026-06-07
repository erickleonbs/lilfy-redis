# 📂 Lilfy Redis

A Docker-ready Redis container configuration tailored for the Lilfy ecosystem, featuring custom memory limits, persistence setups, and optimized configs.

## ✨ Features

- **Custom Configuration**: Tailored `redis.conf` for optimized production/development usage.
- **Dockerized Deployment**: Includes a Dockerfile to bundle configuration.
- **Compose Setup**: Ready-to-go `docker-compose.yml` for multi-container coordination.

## 🛠️ Tech Stack

- **Datastore**: Redis
- **Containerization**: Docker, Docker Compose

## 🚀 Getting Started

### Prerequisites

- Docker
- Docker Compose

### Running Redis

Run the container using Docker Compose:

```bash
docker-compose up -d
```

This will run Redis in the background, bound to port `6379` by default (or the custom port configured inside your `docker-compose.yml`).
