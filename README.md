# Hi, I'm Sharjeel Sohail 👋

**Senior Backend Engineer** · Python · Distributed Systems · AI-Assisted Engineering

[![LinkedIn](https://img.shields.io/badge/LinkedIn-shijisohail-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/shijisohail/)
[![Portfolio](https://img.shields.io/badge/Portfolio-shijisohail.github.io-111827?style=flat&logo=githubpages)](https://shijisohail.github.io/Portfolio/)
[![Email](https://img.shields.io/badge/Email-shijisohail786@gmail.com-EA4335?style=flat&logo=gmail)](mailto:shijisohail786@gmail.com)

---

## Summary

Senior Backend Engineer with 5+ years building production-grade distributed systems. At **Uforia (Leadpages)**, I independently architected the full Analytics Service (FastAPI + TimescaleDB), Global Scripts infrastructure, HTMLPub platform features, and five third-party CRM integrations. I work extensively with AI-assisted engineering — using **Cursor** and **Claude Code** with MCP integrations to multiply delivery throughput across multi-repo features.

---

## Tech Stack

| Category | Technologies |
|---|---|
| **Languages** | Python (expert), TypeScript / JavaScript, SQL, Lua |
| **Frameworks** | FastAPI, Django, DRF, NestJS, Flask, Next.js |
| **Databases** | PostgreSQL, TimescaleDB, MongoDB, Redis, MySQL |
| **Messaging** | RabbitMQ, Apache Kafka, Google Cloud Pub/Sub, BullMQ, Celery |
| **Cloud / Infra** | GCP (GKE, GCS, Cloud Build, BigQuery), AWS (S3, EC2), Docker, Kubernetes |
| **Integrations** | Paragon, REST APIs, OAuth 2.0, HMAC-SHA256, Webhooks |
| **Testing** | pytest, pytest-asyncio, HTTPX, Jest, Vitest, TDD |
| **AI Tooling** | Cursor, Claude Code, MCP Integrations, Agentic Workflows |

---

## Key Achievements

- **93% query latency reduction** — cut analytics dashboard load from 2–4s to under 200ms on 1.4M rows using TimescaleDB continuous aggregates.
- **Zero-deployment integration onboarding** — replaced a static hardcoded registry with a DB-backed JSONB table + admin UI, reducing new provider onboarding from a full deploy cycle to a 5-minute operation.
- **Parallel async query layer** — built a 10-concurrent-query API using `asyncio.gather` with global filter propagation, CVR, and period-over-period comparison.
- **Cross-stack delivery** — shipped production features across Python, TypeScript, Lua, SQL, and GCP/K8s infra, all within a single role.
- **Pioneered AI-assisted workflows** at Uforia using Claude Code + Cursor with MCP integrations (Linear, Notion, Slack), configuring subagents and persistent rules to accelerate multi-repo delivery.

---

## Notable Projects

### 📊 Analytics Service — Uforia / Leadpages
`FastAPI` `TimescaleDB` `asyncio` `MaxMind GeoLite2` `GCP` `BigQuery`

End-to-end analytics backend built from scratch. 10-step enrichment pipeline covering SHA-256 visitor fingerprinting, GDPR IP anonymization, zero-latency GeoIP lookup, bot detection, device parsing, and UTM extraction. 5 continuous aggregates replacing raw hypertable scans. Daily BigQuery sync via Cloud Build + Cloud Scheduler.

---

### ⚙️ Global Scripts Infrastructure — Uforia / Leadpages
`NestJS` `TypeScript` `GCS` `RabbitMQ` `Lua` `Kubernetes`

Owner-scoped manifests published to GCS on every script change. Manifest-loader injected on every published page with environment-aware domain resolution. Includes Lua routing patch, CORS fix, and Kubernetes Helm feature-flag rollout across dev/staging/prod.

---

### 🔗 HTMLPub Integration Registry — Uforia / Leadpages
`Next.js` `Drizzle ORM` `PostgreSQL` `Paragon` `BullMQ` `Railway`

Replaced a hardcoded integration registry with a DB-backed JSONB table, 5-min TTL cache, and admin CRUD UI. New integrations go live in under 5 minutes with zero deployment. Includes opt-in email notifications for form submissions with per-account preferences.

---

### 🤝 5 CRM Integrations — Uforia / Leadpages
`Python` `Paragon iPaaS` `OAuth 2.0` `GraphQL`

Delivered Salesforce, Pipedrive, Shopify, AWeber, and Constant Contact end-to-end: OAuth 2.0 flows, action config APIs, per-provider retry logic, AWeber 60s rate-limit backoff, and Shopify GraphQL upsert.

---

### 🚢 AT&T Shipment Tracking — Merik Solutions
`FastAPI` `Celery` `Redis` `AWS` `Docker` `Kubernetes`

Real-time tracking system integrating multiple cargo ports and logistics carriers. Celery/Redis async processing, deployed on AWS with Docker/Kubernetes for high availability.

---

### 🏢 Smart Building & Surveillance Platform — HyperNym
`Django` `DRF` `Apache Kafka` `PostgreSQL` `IoT`

IoT building management system for Vodafone Qatar and MTN Nigeria. Sensors for water leakage, fire alarm, humidity, and temperature with real-time notifications across microservices via Apache Kafka.

---

## Experience

```
Software Engineer III   │ Uforia (Leadpages, Canada)   │ Aug 2025 – Present   │ Remote
Python Developer        │ Merik Solutions               │ Jun 2024 – Jan 2026  │ Islamabad
Python Developer        │ HyperNym                      │ Sep 2022 – Jun 2024  │ Islamabad
Back End Developer      │ Cyber Recon & Combat Center   │ Oct 2021 – Jul 2022  │ Islamabad
```

---

## Education

**B.Sc. Computer Science** — Bahria University Islamabad (2018–2022)

---

*Open to remote roles and opportunities in the Gulf region & Pakistan.*
