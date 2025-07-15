# Tech Context: OpenTelemetry Demo

## Technologies Used
- OpenTelemetry (tracing, metrics, logging)
- Docker, Docker Compose, Kubernetes
- Languages: Go, .NET, Java, Node.js, Python, Ruby, C++
- Observability tools: Jaeger, Grafana, Prometheus
- Kafka, Postgres, Valkey (Redis alternative)

## Development Setup
- Requires: Git, Make, Docker, Docker Compose
- Environment variables managed via .env file
- Build and orchestration via Makefile and Docker Compose

## Technical Constraints
- Multi-platform support (amd64, arm64)
- Consistent instrumentation across languages
- Maintainability and extensibility for new integrations

## Dependencies
- OpenTelemetry SDKs and Collector
- Third-party observability and database tools 