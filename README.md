# VK-Paints Helm Charts

## Description
Infrastructure as Code (IaC) repository containing Helm charts for all services.

## Structure
- charts/: Independent charts for each microservice.
- helm/vk-paints/: Umbrella chart for global infrastructure (Postgres, RabbitMQ, Gateway).

## Key Features
- **InitContainers**: Automated dependency waiting.
- **StartupProbes**: Reliable service initialization.
- **Sync Waves**: Ordered deployments (Infra -> Backend -> Frontend).
