# Apurv Adarsh — Product Manager

**Internal Tools · Ops Automation · GenAI Products**

Ex-PM intern at a Amazon (Munich, Pan-EU retail team). Ex-engineer at DXC Technology (4 years, enterprise delivery). HHL MBA. Available immediately — India and Germany.

I build analytics systems, workflow OS tools, and GenAI-assisted products that ops teams actually adopt. I measure adoption, not just delivery.

---

## What's here

### 🔍 [Job Search Automation](https://github.com/apurv912/job-search-automation)
End-to-end automated job search pipeline built for high-volume, targeted outreach — scrapes listings, filters by role/location criteria, tracks application status, and surfaces daily digests.

- Automated job board scraping and deduplication
- Role + location filtering with configurable criteria
- Application tracker with status pipeline
- Daily digest output — zero manual triage

> *Why this matters:* Built to solve a real ops bottleneck in job searching. Same pattern as enterprise workflow automation — observe the manual process, eliminate the repetitive layer, measure output.

---

### 🍔 [WhatsApp Swiggy Agent](https://github.com/apurv912/whatsapp-swiggy-agent)
Conversational AI agent that lets you order food from Swiggy entirely over WhatsApp — no app switching, no UI friction.

- WhatsApp as the interface (Twilio / WhatsApp Business API)
- Natural language order placement and modification
- Menu search, recommendations, and order tracking via chat
- Built with Python + LLM function calling

> *Why this matters:* Proves the pattern of embedding AI into channels users already live in — same principle as enterprise GenAI adoption: meet users where they are, reduce friction, measure completion rates.

---

### 🤖 [DocuRAG — RAG Microbuild Ladder](https://github.com/apurv912/AI_Projects)
PM-framed portfolio of production-grade AI builds, each shipped as a shippable artifact with acceptance criteria, eval notes, and proof docs.

- **Build 2** — Baseline RAG Q&A engine
- **Build 2.1** — Caching + similarity guardrail (cost/latency reduction)
- **Build 2.2** — Citations + citation validator (trust layer)
- **Build 2.3** — 2-stage retrieval: embedding top-N → LLM rerank → top-K + graceful 429 degradation
- **Build 2.4** — Evaluation + A/B scorecard (rerank OFF vs ON, regression prevention)
- **Build 2.5** — Telemetry + Ops dashboard: p50/p95 latency, error rates, citation validity, last 20 runs
- **Build 2.6** — Safety guardrails: prompt injection detection, grounding fail-closed, risky-domain routing, PII redaction

> *Why this matters as PM evidence:* Each build is a product decision — what to build next, what tradeoff to make, how to measure it, when it's shippable. This is what product judgment looks like in code.

---

### 📋 [comm-ops-os — Communication Ops OS](https://github.com/apurv912/comm-ops-os)
A local-first workflow OS for outreach operators — PR teams, partnership leads, early-stage GTM. Born from real workflow observation.

- Interaction CRM with full history timeline
- Deterministic extraction pipeline (Interaction → ExtractedFields)
- Task queue built from extraction context
- Template manager with local preview
- SQLite + SQLModel + Streamlit — runs locally, inspectable, portable

> *Why this matters:* This is the product I'm actively building toward. The code repo is the prototype layer. The discovery research (PR OS) is [documented separately](https://apurvadarsh.com/case-study-pr-os.html).

---

### 🌸 [bloom-pr — PR Workflow Front-end](https://github.com/apurv912/bloom-pr)
React + TypeScript + Tailwind + shadcn/ui front-end prototype for the PR OS product. Built with Vite. Playwright tests included.

---

## Key proof points

| Project | What I did | Impact |
|---|---|---|
| Global e-commerce (Retail PM intern) | Designed Overstock Probability KPI + dashboard system | +30% forecast accuracy, −10% markdown, 4→30+ adoption |
| Global e-commerce (Retail PM intern) | Built GenAI + RAG banner creation workflow | 35–40 min → 5–10 min, cost −40–50%, QA 65→80–85% |
| Global e-commerce (Retail PM intern) | Automated email/receipt ingestion → daily digest | ~30 min/user/day saved, scaled 3→30–40 users |
| DXC Technology (Acting Product Owner) | Consolidated 50+ requirements into €2M modernisation roadmap | Sprint velocity +30%, deploy time −40%, errors −30% |
| PR OS (Active) | Full product discovery — India-first PR workflow OS | Pilot-ready MVP, ₹1k/user/mo indicated WTP |

---

## Stack I've worked with

**PM work:** Product discovery, user interviews, PRDs, RICE prioritisation, KPI design, dashboard adoption, A/B testing, rollout planning

**AI/GenAI:** RAG pipelines, agentic workflow,prompt engineering, model evaluation, guardrails, telemetry, LangChain, Amazon Bedrock, n8n

**Analytics:** SQL, funnel analysis, KPI trees, QuickSight, GA4, Mixpanel

**Build:** Python, Streamlit, SQLite, TypeScript, React, Tailwind

---

## Connect

📧 apurvadarsh3483@gmail.com  
💼 [linkedin.com/in/apurv-adarsh](https://linkedin.com/in/apurv-adarsh)  
🌐 [Portfolio](https://apurvadarsh.com)
