# DEEPESH RATHOD

> **Founding Engineer · Tech Lead · Backend & Cloud Architecture**
> *If the product isn't moving, move it yourself.*

```
INPUT  →  PROCESS  →  DATA CONTEXT  →  OUTPUT
```

[**Portfolio**](https://v1.deepesh-engg.in) ·
[**Résumé (PDF)**](https://v1.deepesh-engg.in/Deepesh_Rathod_Resume.pdf) ·
[**LinkedIn**](https://www.linkedin.com/in/deepesh-rathod-315152198/) ·
[`deepeshd03938@gmail.com`](mailto:deepeshd03938@gmail.com) ·
Bengaluru, India

---

## What I'm doing now

**Founding Engineer / Tech Lead at Zoca** *(Jan 2025 — Present)*

- Defined the foundational AWS ECS / Fargate architecture for a multi-tenant SaaS that scaled from **90 → 1,500 customers (1,000+ paying, $1M+ ARR)**.
- Consolidated 3 servers + 50 — 60 Lambdas into **6 autoscaling services + 10 workers + 10 Lambdas**.
- Led **zero-failure migration** of all legacy users — no data loss, no production incidents, no rollbacks.
- Built an **AI-native engineering toolchain** (Claude Code + custom Metabase MCP + AWS CLI) that compresses outage and customer-issue RCAs from **2 — 3 hours → ~5 minutes** — a 25 — 35× speedup that compounds across every incident.
- Designed **tenant isolation + database-layer audit logging** as the foundation for SOC2 / HIPAA readiness across all tenant operations.
- Helped scale engineering from **2 — 3 → 15 — 18 engineers** — ran 20+ technical interviews, served as Senior Buddy for 4+ engineers (mentees shipping bug fixes in week 1, end-to-end features in their first month).

> Earlier: Founding Engineer at Zoca (formerly Chrone), Jun 2023 — Dec 2024 — distributed media pipeline (1,000+ uploads/day across 900+ GB S3), full AWS ownership through a leadership transition, Scheduling v1 end-to-end.

## Recent open work

| Repo | What it is |
| --- | --- |
| [**v1.deepesh-engg.in**](https://v1.deepesh-engg.in) | Brutalist "Boring Markdown" portfolio. Zero build, zero framework. One HTML, one CSS, one JS file, plain Markdown. Served behind Cloudflare Tunnel. |
| [`resume-bot`](https://github.com/deepesh-01/resume-bot) | Telegram bot that tailors résumés to job descriptions using the Claude Code CLI. |
| [`job-intake`](https://github.com/deepesh-01/job-intake) | Daily job-board scraper → Google Sheet → polished triage + tailoring webapp. Sibling to `resume-bot`. |

## Weekend architectural exploration

- **AI-Powered PR Review** — Slack + Git + Claude pipeline running LLM-powered sentiment analysis and technical review on PRs. Reviewed 30 PRs in the first 3 days vs. ~15 baseline manually — 2× throughput with improved consistency.
- **WeLog** *(in UAT)* — collaborative real-time journaling for partners: auth, signup, encrypted private data, real-time shared entries with per-user data isolation.
- **MarketSignal AI** — real-time trading automation engine ingesting Angel One market data on a 15-min cron, evaluating conditions, delivering Telegram alerts. Full pipeline on local infra, no third-party orchestration.
- **Private Cloud on Raspberry Pi** — self-hosted server stack via Cloudflare Tunnels (no public IPs, no port forwarding); 2+ months continuous uptime, 3 — 5s cold boot.

## Stack I actually ship

**Backend:** TypeScript · JavaScript · Node.js · NestJS · Express · Python · Django · Django REST Framework
**Frontend:** React · Redux
**Cloud / Infra:** AWS (ECS, Fargate, EC2, SES, CloudTrail, SQS, IAM) · Docker · CI/CD pipelines
**Data:** PostgreSQL · MongoDB
**AI / Automation:** Claude Code · custom MCP servers · Retell / Voice AI · AI-agent observability
**Architecture:** Multi-tenant SaaS · microservices · monorepo · zero-downtime migrations · tenant isolation & RBAC

## How to read this profile

Most of the older repos here are coursework, interview assignments, and forks from when I was learning the trade. The work I'd actually point at lives behind the company (Zoca / Chrone) and on the portfolio site.

→ Start at [**v1.deepesh-engg.in**](https://v1.deepesh-engg.in) for the long-form story.
→ Or read the [**Résumé**](https://v1.deepesh-engg.in/Deepesh_Rathod_Resume.pdf) for the executive version.
