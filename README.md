<p align="center">
  <img src="https://raw.githubusercontent.com/DoTruongPhat/DoTruongPhat/main/assets/profile/hero-animatic-preview.gif" alt="PHAT DO - Fullstack Developer" />
</p>

<h1 align="center">PHAT DO</h1>
<h3 align="center">Fullstack Developer | Java • Spring Boot • Angular • React</h3>

<p align="center">
  Building scalable, secure, and observable fullstack systems.
</p>

<p align="center">
  <a href="https://github.com/DoTruongPhat?tab=repositories">
    <img src="https://img.shields.io/badge/GitHub-DoTruongPhat-181717?style=for-the-badge&logo=github" alt="GitHub" />
  </a>
</p>

---

## About Me

I am a fullstack developer focused on building modern web applications with Java, Spring Boot, Angular, and React. I care about clean API design, secure authentication, event-driven systems, reporting, and observability.

- Building fullstack systems from UI to backend services.
- Designing REST APIs, authentication flows, and service boundaries.
- Working with relational databases, cache, messaging, reports, and monitoring.
- Improving architecture with Docker, Kafka, Redis, OpenTelemetry, and clean code practices.

## Tech Stack

| Area | Technologies |
| --- | --- |
| Backend | Java, Spring Boot, Spring Security, REST API |
| Frontend | Angular, React, JavaScript, TypeScript, HTML5, CSS3/SCSS |
| Database | PostgreSQL, SQL Server, Redis |
| Messaging | Kafka |
| DevOps / Observability | Docker, Git, GitHub, OpenTelemetry |
| Tools | IntelliJ IDEA, Visual Studio, VS Code, Postman |

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,angular,react,js,ts,html,css,postgres,redis,kafka,docker,git,github,idea,vscode,postman&perline=9" alt="Tech stack icons" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server" />
  <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white" alt="OpenTelemetry" />
</p>

## Featured Projects

### 01. Booking System

Fullstack hotel reservation system built with a production-style microservice architecture.

- Angular customer/admin/host UI.
- Java Spring Boot services behind an API Gateway.
- Keycloak authentication, JWT, role-based access, and optional 2FA.
- PostgreSQL data layer, Redis cache, Kafka events, and Docker Compose.
- JasperReports for booking, revenue, receipt, and export flows.
- Observability with OpenTelemetry, Grafana, Prometheus, Loki, Promtail, and Tempo.

**Stack:** Angular, TypeScript, Java, Spring Boot, PostgreSQL, Kafka, Redis, Docker, OpenTelemetry

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

```mermaid
flowchart LR
    UI[Angular / React UI] --> API[API Gateway]
    API --> AUTH[Auth Service]
    API --> CORE[Booking Service]
    API --> PAY[Payment Service]
    API --> WF[Workflow Service]

    AUTH --> DB[(PostgreSQL)]
    CORE --> DB
    PAY --> DB

    CORE <--> KAFKA[Kafka]
    PAY <--> KAFKA
    CORE --> REDIS[(Redis)]
    AUTH --> REDIS

    CORE --> REPORT[JasperReports]
    API --> OTEL[OpenTelemetry]
    OTEL --> OBS[Grafana / Loki / Tempo / Prometheus]
```

## GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=DoTruongPhat&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DoTruongPhat&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=DoTruongPhat&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>

## Current Focus

- Fullstack architecture with Java, Spring Boot, Angular, and React.
- Secure authentication and authorization flows.
- Event-driven backend systems with Kafka and Redis.
- Observability, tracing, logs, metrics, and operational dashboards.
- Clean API design and maintainable service boundaries.

## Contact

<p align="center">
  <a href="mailto:dotruongphat9@gmail.com">
    <img src="https://img.shields.io/badge/Email-dotruongphat9%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/DoTruongPhat">
    <img src="https://img.shields.io/badge/GitHub-DoTruongPhat-181717?style=for-the-badge&logo=github" alt="GitHub" />
  </a>
</p>
