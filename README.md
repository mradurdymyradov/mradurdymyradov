# Hi, I'm Myrat Durdymyradov 👋

### AI-Assisted Product & Automation Builder | GTM Operations

[![Focus](https://img.shields.io/badge/Focus-AI_Automation_%7C_GTM_Operations_%7C_Product_Ops-blue.svg)](#-primary-proof-of-work)
[![US Visa Pathway](https://img.shields.io/badge/US_Visa_Pathway-Potential_BridgeUSA_J--1_Intern-success.svg)](#-us-placement-pathway)
[![Pavel Case Study](https://img.shields.io/badge/Production_Proof-Pavel_Community_Case_Study-purple.svg)](https://github.com/mradurdymyradov/fastapi-telegram-subscription-starter/blob/main/CASE_STUDY.md)

I turn operating problems into deployed systems. With a Business and Management background, I use AI coding agents (Claude Code, OpenAI Codex, and Antigravity) for implementation while I own requirements, acceptance criteria, architecture choices, release validation, launch operations, and iteration. I do not claim to hand-write the underlying codebase.

---

## 🌟 Primary Proof of Work

### 1. [Subscription Community Platform & Billing Engine (Pavel Community)](https://github.com/mradurdymyradov/fastapi-telegram-subscription-starter)
*Production full-stack membership SaaS with automated billing, Telegram bot access control, and Next.js admin.*

> 📊 **Operator-reported launch-week volume:** **€1,648 EUR**, **₽251,500 RUB**, and **$4,306 USD** in the original currencies. The figures are not converted or combined and are not independently audited. Read the full **[Production Case Study](https://github.com/mradurdymyradov/fastapi-telegram-subscription-starter/blob/main/CASE_STUDY.md)**.

- **FastAPI 18-Router Backend:** Async SQLAlchemy 2 + Alembic (28 PostgreSQL models), JWT authentication with TOTP 2FA, and structured telemetry.
- **Idempotent Multi-Provider Fulfillment:** Unified `fulfill_payment` engine supporting Stripe recurring subscriptions and on-chain USDT crypto verification (TronGrid TRC-20 and Etherscan ERC-20 with 3-block confirmations).
- **Autonomous Lifecycle Bot (`aiogram 3`):** Generates single-use invite tokens, tracks referral attributions (`?start=ref_<code>`), issues portal magic links, and handles background access revocation upon non-renewal.
- **Next.js 14 Admin Panel:** Real-time MRR, subscriber retention metrics, manual payment review queue, and segment broadcasts.
- **Verification:** **938 backend tests** and **8 deployment-helper tests** pass in CI alongside both frontend builds and Docker image smoke builds.

---

### 2. [AI Book Platform](https://github.com/mradurdymyradov/ai-book-platform)
*Multi-agent writing & synthesis engine with real-time execution trace.*

- **6-Agent Sequential Pipeline:** Orchestration → Search (BM25) → Writing → Style → Harmonization → Enforcing.
- **Live Agent Trace Interface:** Transparent timeline visualizing intermediate agent prompts, completions, latencies, and execution status per stage.
- **Single-Process Stack:** Next.js 16 + React 19 + Prisma 7 + SQLite with in-process BM25 retrieval.
- **Zero-Config Evaluation:** Ships with a deterministic in-process mock provider enabled by default (`AGENT_PROVIDER=mock`) for immediate end-to-end evaluation without API keys.

---

### 3. [Speed to Lead Inbound Engine](https://github.com/mradurdymyradov/speed-to-lead)
*Importable n8n workflow template for Twilio SMS and Vapi Voice AI dispatch.*

- **Parallel Dispatch Path:** Captures a documented webhook payload, cleans phone formatting, and triggers Twilio SMS and Vapi.ai voice-call branches after CRM logging.
- **CRM Sync:** Appends structured contact records, form IDs, and submission timestamps directly to Google Sheets CRM.

---

### 4. [Multi-Source Market Data Harvester](https://github.com/mradurdymyradov/multi-source-job-harvester)
*Modular web extraction pipeline with thread-pool orchestration and Excel reporting.*

- **Concurrent Extraction:** Thread-pool worker orchestration querying 6 active zero-auth platforms (RemoteOK, DailyRemote, Jobicy, The Muse, WeWorkRemotely, Remotive) with domain-specific rate limits and backoff.
- **Reporting Engine:** Deduplicates cross-board listings and compiles styled multi-sheet Excel reports and streaming JSONL datasets.

---

## 🛠️ Technical Competencies & Workflow

| Dimension | Capabilities & Tools |
| :--- | :--- |
| **Product & Operations** | Requirements Scoping, System Architecture, Payment Flows, Retention & Churn Analytics, GTM Workflows |
| **AI Agent Orchestration** | Claude Code, OpenAI Codex, Antigravity, Multi-Agent Pipelines, Evaluation Guardrails, Prompt Engineering |
| **Systems used in agent-assisted projects** | FastAPI, Python 3.11, PostgreSQL, Redis, Next.js, TypeScript, Prisma, Docker, GitHub Actions |
| **Frontend & Dashboards** | Next.js 16/14 (App Router), React 19, TypeScript, Tailwind CSS, TanStack Query, Recharts |
| **Workflow Automation** | n8n (Production workflows), Webhook Listeners, Twilio SMS, Vapi.ai Voice API, Google Sheets API |
| **DevOps & Infrastructure** | Docker, Docker Compose, Caddy 2 (Auto SSL), GitHub Actions CI, Linux, Git |

---

## 🇺🇸 US Placement Pathway

> **Potential BridgeUSA J-1 Intern candidate (Business and Management graduate, June 2026).**
> Seeking structured, supervised placements in **AI Automation, GTM Operations, Founder Associate, or Product Operations** in San Francisco or New York. Eligibility and placement require a designated sponsor, a qualifying host organization, an approved DS-7002 training plan, DS-2019 issuance, and visa approval.

---

## 📬 Connect

- **GitHub:** [@mradurdymyradov](https://github.com/mradurdymyradov)
- **Email:** [myrat.durdymyradov.dev@gmail.com](mailto:myrat.durdymyradov.dev@gmail.com)
- **Location:** Ashgabat (GMT+5) · Open to relocation to San Francisco or New York
