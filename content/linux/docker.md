---
title: Docker Basics
tags:
  - linux
  - docker
---

# Docker

Docker is a platform for packaging applications into containers.

## Why Docker?

Benefits:

- Reproducible environments
- Easy deployment
- Dependency isolation

## Basic Commands

### Pull Image

```bash
docker pull nginx
```

### Run Container

```bash
docker run -d -p 80:80 nginx
```

### List Containers

```bash
docker ps
```

### Remove Container

```bash
docker rm -f container_id
```

## Volumes

Volumes allow data persistence.

```bash
docker volume create mydata
```

Mount volume:

```bash
docker run -v mydata:/data nginx
```

## Related Notes

- [[../ai/rag]]