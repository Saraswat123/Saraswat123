# Saraswat Das

Tech lead building multi-agent infrastructure and the products around it. 

Know more about my work: **https://saraswat123.github.io/**

---

## What I build

I take frontier LLMs and agent frameworks and turn them into systems a team uses every day: the agent loop, the tool layer, the guardrails, the traces and the handover.

| Layer         | What I work with                                                                        |
| ------------- | --------------------------------------------------------------------------------------- |
| Agents        | LangGraph, CrewAI, LangChain deepagents, Claude Code headless runs, approval gates      |
| Tool layer    | MCP servers in Rust (rmcp) and Python                                                   |
| Safety        | token ceilings, egress allowlists, halt switch, post-checks, hash-chained action ledger |
| Observability | OpenTelemetry, Phoenix, per-run token and cost audit from transcripts                   |
| Data          | PostgreSQL, SQLite, DuckDB, Redis, ChromaDB, fastembed                                  |
| Product       | FastAPI, Next.js, React, Docker, Vercel, Supabase                                       |

## Projects

### Networking Agent: [Networking-Agent.md-](https://github.com/Saraswat123/Networking-Agent.md-)

A Rust MCP server with 56 tools for prospect research, scoring, email verification and a sent log. Outreach goes through an OAuth-based sender, not an API key.

### Rysen Learning System: [Rysen-Learning-System](https://github.com/Saraswat123/Rysen-Learning-System)

LMS covering onboarding, training, testing, certification and live tracking, with an in-product agent (Rysen AI) that runs a 15-tool loop. Next.js, Groq, PostgreSQL, Prisma. 78 test cases (counted statically from the repo). Built for 15 campuses and 50+ educators.

### Document AI pipeline: [rysen-lpc-ocr](https://github.com/Saraswat123/rysen-lpc-ocr)

Async pipeline for scanned forms: FastAPI, Celery, Redis, PostgreSQL and a vision LLM, multi-tenant across 15 locations.

### Vault Harness (private repo, design public)

A harness that lets an agent complete a purchase without ever seeing the card: sealed card (X25519, HKDF, AES-GCM), enclave swap, WebAuthn approval, a guard pipeline, Stripe in test mode. 219 tests, 36 of 36 on the eval set. AWS Nitro deployment is designed, not run. Diagrams and trust zones: https://saraswat123.github.io/work/vault-harness/

## Open source

Merged in [moltis-org/moltis](https://github.com/moltis-org/moltis), a Rust agent gateway:

- [#1247](https://github.com/moltis-org/moltis/pull/1247) fix(sandbox): drop DMI sysfs masks on arm64 Docker daemons
- [#1249](https://github.com/moltis-org/moltis/pull/1249) fix(auth): let Docker loopback-only deployments count as local
- [#1252](https://github.com/moltis-org/moltis/pull/1252) docs(docker): document the bind-mount permission fix for fresh deploys

## How I work

- Every number on my portfolio is labelled: counted from files, verified by photo or badge, or self-reported. See https://saraswat123.github.io/numbers/
- Each case study says what is tested, what is live and what is only designed.
- I hand over with a runbook: what it does, how to run it, how to tell it worked, what breaks first.

## Contact

[Portfolio](https://saraswat123.github.io/) · [LinkedIn](https://www.linkedin.com/in/saraswat-das/)
