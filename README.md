# Arya Banking Service Registry

Netflix Eureka server for service discovery. All microservices register here and discover each other dynamically.

## Quick Start

```powershell
mvn clean package -DskipTests
docker build -t arya-banking-service-registry .
docker run -p 8761:8761 arya-banking-service-registry
```

Or run via the [infra Docker Compose stack](https://github.com/Event-Based-Banking-Application/arya-banking-infra).

## Links

- [Local Development Setup](https://event-based-banking-application.github.io/arya-banking/docs/local-development/)
- [Service Registry Docs](https://event-based-banking-application.github.io/arya-banking/docs/service-registry/)
