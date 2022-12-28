Bootstrap traefik with docker compose
=====================================

## Setup

```bash
docker network create --internal reverse_proxy
docker compose -f docker-compose.yml -f docker-compose.debug.yml up
```

## Debug

```bash
docker compose -f docker-compose.yml -f docker-compose.debug.yml up
```
