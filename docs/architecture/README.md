# Architecture

NôngTrạm follows a modular-monolith backend architecture with a separate web frontend.

```text
Browser
   │
   ▼
Next.js / React / TypeScript
   │ REST / HTTP
   ▼
Spring Boot / Java
   │
   ├── Auth
   ├── User
   ├── Product
   ├── Order
   ├── Payment
   ├── Traceability
   ├── Review
   ├── Chat
   ├── AI
   └── Admin
   │
   ▼
MySQL
```

Advanced infrastructure such as Redis, RabbitMQ, WebSocket and external services will be added only when the corresponding feature requires them.
