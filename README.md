# Authentication Module

Production-grade authentication module for NestJS applications.

Part of the [Systems Blueprints](https://github.com/nwangasam/systems-blueprints) series.

---

## What This Module Covers

- Registration with email verification
- Login with JWT (access + refresh token strategy)
- OAuth 2.0 (Google, GitHub, Apple)
- Two-Factor Authentication (TOTP, SMS, WebAuthn)
- Session management and device tracking
- Password reset and recovery flows
- Account management and security logs
- Admin operations
- Rate limiting and brute force protection

---

## Stack

- **Framework** — NestJS
- **Database** — PostgreSQL (TypeORM)
- **Cache** — Redis
- **Auth** — JWT (RS256), OAuth 2.0, TOTP
- **Container** — Docker

---

## Quick Start
```bash
# Clone
git clone https://github.com/nwangasam/authentication
cd authentication

# Install
npm install

# Configure
cp .env.example .env
# Fill in your .env values

# Run
docker-compose up
```

---

## Documentation

- [Architecture](./docs/ARCHITECTURE.md)
- [API Reference](./docs/API.md)
- [Scaling](./docs/SCALING.md)
- [Security](./docs/SECURITY.md)
- [Runbook](./docs/RUNBOOK.md)
- [ADRs](./docs/adrs/)

---

## Design

This module was designed following a full Low Level Design process
before any implementation. See [Architecture](./docs/ARCHITECTURE.md)
for the complete design documentation including data model,
component map, flow diagrams and decision records.

---

## License

MIT