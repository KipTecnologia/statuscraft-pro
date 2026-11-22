# StatusCraft Pro — Enterprise Uptime, SSL & Cron Monitoring Micro-SaaS

> **Interactive Evaluation Demo & Showcase by [Kip Tecnologia](https://github.com/KipTecnologia)**  
> **Live Demo:** [https://kiptecnologia.github.io/statuscraft-pro/](https://kiptecnologia.github.io/statuscraft-pro/)  
> **Commercial Source Code (Next.js 15 + Prisma + Stripe + Docker):** [https://kiptecnologia.gumroad.com](https://kiptecnologia.gumroad.com)

---

## Why StatusCraft Pro?

Replace expensive recurring subscriptions (**BetterStack, UptimeRobot, Atlassian Statuspage**) with a turnkey, white-label micro-SaaS platform you own 100%.

### Production Differentiators
- **Live HTTP/HTTPS Synthetic Probing + Anti-Flapping Engine:** Automatic double-check retry + configurable consecutive failure threshold before opening incidents (eliminates 3 AM false alarms).
- **Real TLS/SSL Certificate Expiry Inspector:** Native TLS inspection tracks exact X.509 expiration days & CA issuer and dispatches `SSL_EXPIRING_SOON` alerts 14 days in advance.
- **Cron Job & Heartbeat Monitoring (`/api/heartbeat/[token]`):** Unique check-in URLs for database backups, ETL pipelines, and scheduled scripts; opens incidents automatically if a job misses its window.
- **White-Label Public Status Page (`/status/[slug]`) + Email Subscribers + Live SVG Badge:** Customer-facing status page with email subscription form, 30-check uptime bars, SSL badges, and embeddable SVG status badge.
- **Real Webhook, Slack & Discord Alerting:** Instant payloads on downtime, SSL expiry, missed heartbeats, and recovery.
- **Stripe 3-Tier SaaS Monetization:** Real API quota enforcement per plan (`Starter $19/mo`, `Pro $49/mo`, `Scale $129/mo`).
- **1-Command Production Deploy:** Multi-stage `Dockerfile`, `docker-compose.yml` (Next.js 15 + PostgreSQL 16 + automated Probe Worker), and GitHub Actions serverless cron workflow.
- **100% Bilingual (EN 🇺🇸 / PT-BR 🇧🇷) + Warm Alabaster Light & Carbon Graphite Dark Modes + RBAC & SOC2 Audit Trail.**

---

## Stack (Full Commercial Source)
- **Framework:** Next.js 15 (App Router) + React 19 + TypeScript Strict
- **Database:** Prisma ORM (Zero-config SQLite local dev / PostgreSQL 16 production)
- **Billing:** Stripe Checkout + Signed Webhook Sync
- **Deployment:** `docker compose up -d --build` or Vercel + Neon

---

## License
Kip Tecnologia Commercial & Evaluation License (v2.0) — see [LICENSE](./LICENSE).
