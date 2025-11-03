# 🌐 .NET Microservices with Aspire

A **modern, cloud-native microservices application** built with **.NET Aspire**, designed to showcase scalable, modular, and production-ready architecture patterns.
Inspired by the architectural philosophy of platforms like Stack Overflow, this project emphasizes **service decomposition**, **event-driven communication**, and **clean system boundaries** — prioritizing architectural integrity over feature mimicry.

---

## 🧩 Tech Stack

### ⚙️ Core Technologies

- **.NET Aspire** — service orchestration and cloud-native microservice composition
- **Next.js** — reactive, high-performance front-end framework
- **Keycloak** — enterprise-grade identity and access management (OAuth2 / OpenID Connect)
- **Entity Framework Core** — ORM for robust data persistence and migrations
- **PostgreSQL** — reliable and scalable relational database
- **RabbitMQ** — message broker for asynchronous communication
- **WolverineFx** — transactional outbox and message bus orchestration
- **YARP** — reverse proxy and API gateway layer
- **OpenTelemetry** — distributed tracing and observability framework
- **Docker** — containerized deployment and isolated service environments
- **GitHub Actions** — CI/CD automation for continuous integration and deployment

### 🧰 Supporting Libraries

- **Typesense** — fast, typo-tolerant search engine
- **Tiptap** — flexible and modern rich-text editor

---

## 🏗️ Architecture Overview

This project follows a **domain-driven, event-driven microservices architecture** that ensures:

- 🧱 **Independent deployability** — each service runs, scales, and evolves autonomously
- 🔄 **Asynchronous messaging** — RabbitMQ + WolverineFx ensure resilience and high throughput
- 🌉 **Unified API access** — orchestrated via YARP Gateway
- 👁️ **Consistent observability and configuration** — powered by .NET Aspire and **OpenTelemetry**
- 🔐 **Centralized security** — managed via Keycloak for unified authentication and authorization

All services are instrumented with **OpenTelemetry**, providing distributed traces, metrics, and logs to simplify debugging and performance monitoring across the ecosystem. This guarantees **deep observability**, **faster incident response**, and **data-driven optimization**.

The result is a **loosely coupled**, **highly maintainable**, and **developer-friendly ecosystem**, enabling rapid iteration without sacrificing architectural rigor.

---

## 🚀 Getting Started

### 🧱 Prerequisites

Ensure the following dependencies are installed locally:

- [.NET 8 SDK](https://dotnet.microsoft.com/download)
- [Node.js 20+](https://nodejs.org/)
- [Docker](https://www.docker.com/)
- [PostgreSQL](https://www.postgresql.org/)

### ▶️ Run with Aspire

To bootstrap the environment:

```bash
dotnet run --project ./Overflow.AppHost
```

This command automatically orchestrates all dependent services — including the database, broker, and search engine — within the Aspire environment.

---

## 🧠 Key Highlights

- ✅ **End-to-end microservice orchestration** with .NET Aspire
- 🔐 **Centralized authentication & authorization** via Keycloak
- 🔄 **Resilient event-driven workflows** leveraging WolverineFx Outbox Pattern
- 🧭 **Comprehensive observability and tracing** powered by OpenTelemetry
- 📦 **Fully containerized architecture** for local and cloud environments
- 🔍 **High-performance search** powered by Typesense
- 🖋️ **Modern content editing** with Tiptap
- 🚦 **CI/CD automation** via GitHub Actions
