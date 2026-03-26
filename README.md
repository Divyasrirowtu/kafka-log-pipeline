@"
# Kafka Log Aggregation Pipeline

## Overview
This project implements a production-style log aggregation system using Kafka, Fluentd, and OpenTelemetry.

## Architecture
- Kafka as log bus
- Fluentd for log collection
- Microservices generating logs
- Processor for alerting and trace grouping
- Backend for dashboard APIs

## Setup
Run:
docker-compose up --build

## Features
- Structured logging
- Distributed tracing
- Real-time alerts
- WebSocket log streaming
"@ | Out-File README.md
