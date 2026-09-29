<h1 align="center">PHAT DO</h1>
<h3 align="center">Fullstack Developer | Java • Spring Boot • Angular • React</h3>

<p align="center">
  Building scalable, secure, and observable fullstack systems.
</p>

<p align="center">
  <a href="https://github.com/DoTruongPhat?tab=repositories">GitHub: DoTruongPhat</a>
</p>

---

## About Me

I am a fullstack developer focused on building modern web applications with Java, Spring Boot, Angular, and React. I care about clean API design, secure authentication, event-driven systems, reporting, and observability.

- Building fullstack systems from UI to backend services.
- Designing REST APIs, authentication flows, and service boundaries.
- Working with relational databases, cache, messaging, reports, and monitoring.
- Improving architecture with Docker, Kafka, Redis, OpenTelemetry, and clean code practices.

## Tech Stack

| Group | Technologies |
| --- | --- |
| Backend | Java, Spring Boot, Spring Security, REST API |
| Frontend | Angular, React, TypeScript, JavaScript, HTML5, CSS3/SCSS |
| Database | PostgreSQL, SQL Server, Redis |
| Messaging | Kafka |
| DevOps / Observability | Docker, OpenTelemetry, Git, GitHub |
| Tools | IntelliJ IDEA, Visual Studio / VS Code |

## Featured Projects

### 01. Booking System

Fullstack hotel reservation system built with a production-style microservice architecture.

- Angular customer/admin/host UI.
- Java Spring Boot services behind an API Gateway.
- Keycloak authentication, JWT, role-based access, and optional 2FA.
- PostgreSQL and SQL Server data layer, Redis cache, Kafka events, and Docker Compose.
- JasperReports for booking, revenue, receipt, and export flows.
- Observability with OpenTelemetry, Grafana, Prometheus, Loki, Promtail, and Tempo.

**Stack:** Angular, TypeScript, Java, Spring Boot, PostgreSQL, SQL Server, Kafka, Redis, Docker, OpenTelemetry

[View Repository](https://github.com/DoTruongPhat/Booking-System)

### 02. Payment / Reporting System

Payment and reporting module focused on reliable payment state, async processing, and operational visibility.

- Payment initialization, callback handling, cancellation, manual sync, and refund flow.
- Kafka-based async payment/report events.
- JasperReports templates for revenue and booking exports.
- Service logs, metrics, tracing, and dashboard-ready observability.

**Stack:** Java, Spring Boot, PostgreSQL, Kafka, JasperReports, OpenTelemetry

[View Payment Service](https://github.com/DoTruongPhat/Booking-System/tree/main/payment-service) ·
[View Reporting Flow](https://github.com/DoTruongPhat/Booking-System/tree/main/booking-service)

## System Architecture

```text
Angular / React UI
        |
        v
API Gateway
        |
        +--> Auth Service -----> PostgreSQL / SQL Server
        +--> Booking Service --> PostgreSQL / SQL Server
        +--> Payment Service --> PostgreSQL / SQL Server
        +--> Workflow Service

Booking Service <--> Kafka <--> Payment Service
Booking/Auth    <--> Redis
Booking Service ---> JasperReports
Services        ---> OpenTelemetry ---> Grafana / Loki / Tempo / Prometheus
```

## GitHub Stats

- Main profile: [DoTruongPhat](https://github.com/DoTruongPhat)
- Featured repository: [Booking-System](https://github.com/DoTruongPhat/Booking-System)
- Focus languages: Java, TypeScript, JavaScript, SQL

## Current Focus

- Fullstack architecture with Java, Spring Boot, Angular, and React.
- Secure authentication and authorization flows.
- Event-driven backend systems with Kafka and Redis.
- Observability, tracing, logs, metrics, and operational dashboards.
- Clean API design and maintainable service boundaries.

## Contact

- Email: [dotruongphat9@gmail.com](mailto:dotruongphat9@gmail.com)
- GitHub: [github.com/DoTruongPhat](https://github.com/DoTruongPhat)
