# NôngTrạm

**AI Agricultural Marketplace for Vietnamese Farm Products**

NôngTrạm is a full-stack platform connecting farmers, cooperatives, and agricultural producers with buyers. The project focuses on Vietnamese agricultural products such as coffee, pepper, and other local products, with product management, ordering, traceability, and AI-assisted listing.

## Repository Structure

```text
nongtram/
├── backend/          # Java + Spring Boot REST API
├── frontend/         # Next.js + React + TypeScript UI
├── database/         # Schema, seed data and migrations
├── docs/              # Architecture, API, database and development docs
├── .github/           # CI/CD, issue and pull-request templates
├── docker/            # Container definitions
├── docker-compose.yml
├── .gitignore
└── README.md
```

## Technology Stack

### Backend
- Java 21
- Spring Boot
- Spring Web
- Spring Data JPA / Hibernate
- Spring Security + JWT
- MySQL
- Jakarta Validation
- OpenAPI / Swagger

### Frontend
- TypeScript
- React
- Next.js
- Tailwind CSS

### Engineering / DevOps
- Git + GitHub
- Maven
- Docker / Docker Compose
- GitHub Actions

### Planned Integrations
- AI API
- QR Code traceability
- Payment gateway
- Redis
- RabbitMQ
- WebSocket
- Maps / GPS

## Git Workflow

```text
main       ← stable / release-ready
  ↑
develop    ← integration
  ↑
feature/*  ← individual work

hotfix/* → main and develop
```

Changes should normally go through a Pull Request. Keep `main` stable and use short-lived feature branches.

## Local Development

```text
Backend  → http://localhost:8080
Frontend → http://localhost:3000
```

Detailed setup and engineering documentation lives under `docs/`.

## Project Status

🚧 **In development**

The project is being developed incrementally, starting with the backend foundation, authentication, product management, and frontend integration before adding advanced services.
