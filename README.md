# Spring Cloud Commerce Platform

Plataforma de comercio electrónico basada en una arquitectura distribuida
de microservicios, desarrollada con Spring Boot y Spring Cloud.

El sistema administra productos, inventario, pedidos y notificaciones mediante
servicios independientes. Implementa comunicación síncrona y asíncrona,
seguridad centralizada, tolerancia a fallos, consistencia eventual,
observabilidad y despliegue en contenedores.

## Key Features

- Product, inventory, order and notification microservices
- API Gateway as the system entry point
- Service discovery and centralized configuration
- OAuth2 and JWT security with Keycloak
- Asynchronous communication with RabbitMQ
- Saga and Transactional Outbox patterns
- Circuit Breaker, Retry and Timeout with Resilience4j
- Distributed tracing and metrics
- Docker Compose local environment
- Kubernetes deployment manifests
