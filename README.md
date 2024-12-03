# Boarding House Management System

A full-stack application for managing boarding house operations.

## Prerequisites

- Docker Engine 20.10.0+
- Docker Compose v2.0.0+
- Git

## Getting Started

1. Clone with submodules:
```
git clone --recursive <repo-url>
```

2. Configure environment:
```
cp .env.example .env
```

3. Start services:
```
docker-compose --env-file .env up -d
```