
# Redpanda Docker Setup

A lightweight Docker Compose configuration for running Redpanda, a Kafka-compatible streaming platform.

## About Redpanda

Redpanda is a modern streaming platform designed as a Kafka alternative. It offers:
- **High Performance**: Written in C++ for low latency and high throughput
- **Kafka Compatible**: Drop-in replacement for Apache Kafka
- **Lightweight**: Lower resource consumption than Kafka
- **Simple Operations**: Easier to deploy and manage

## Quick Start

### Prerequisites
- Docker and Docker Compose installed

### Running Redpanda

```bash
docker-compose up -d
```

This will start a Redpanda broker accessible at `localhost:9092`.

### Stopping Redpanda

```bash
docker-compose down
```

## Configuration

Edit `docker-compose.yml` to customize:
- Broker ports
- Storage volumes
- Environment variables
- Resource limits

## Accessing Redpanda

- **Kafka API**: `localhost:9092`
- **Admin API**: `localhost:8081` (if configured)

## Documentation

- [Redpanda Docs](https://docs.redpanda.com)
- [Docker Compose Reference](https://docs.docker.com/compose/)
