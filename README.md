# Ahmad Salman Khan

**Principal AI Orchestrator · Forward-Deployed AI Engineer · ex-Founder/CTO (VC-backed fintech)**

I embed inside a business, find the manual work that is quietly costing it money, and ship the agentic system that removes it. One seat from diagnosis to production: business analysis, architecture, engineering, deployment, and the stakeholder management in between.

Currently deployed by [Creative Chaos](https://creativechaos.co/ai-orchestrator/) as a forward-deployed engineer for US enterprise clients.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmad-salman-khan/) [![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/13083814/ahmad-salman-khan?tab=profile) [![X](https://img.shields.io/badge/X-%23000000.svg?logo=X&logoColor=white)](https://twitter.com/_Ahmad_Salman1)

---

## Selected work

**Operational reporting platform for a US construction firm** (~$300M revenue, ~2,000 people) — *2026, solo forward-deployed engineer*
Built and shipped the system that gave the company its first fully complete labor report in its history: delivered five days after period end, 99.9% of required inputs captured (3,306 of 3,308), 58 of 60 active jobs submitted. The client's EVP of Construction called it "unprecedented." Built inside the client's own infrastructure and security policy; worked directly with the executive team. Creative Chaos Associate of the Quarter, Q3 2026, for this engagement.

> "Built a production-ready application to manage productivity across a $300M annual revenue / 2,000-person org, and resolved all technical issues." — Principal, client's private-equity sponsor

**Lunara** — *Co-Founder/CTO, 2022–2024 · Iterative W23*
Business banking for Pakistani SMEs ("Brex for Pakistan"). Built the product, KYC/AML automation and Tier-1 bank integrations ahead of the regulatory framework; shelved when regulation didn't follow.

**Cruise AI** — *Co-Founder/CTO (technical lead)*
HIPAA-compliant clinical operations platform: zero-to-one distributed voice-to-text, real-time analytics, encrypted storage, CI/CD.

**HIST** — *Co-Founder/CTO (technical lead)*
AI-native cloud infrastructure for healthcare distribution: RAG document ingestion and a RegTech assistant; cut monthly AWS spend ~30% through architectural redesign.

---

## Tools I maintain

| Project | What it does | Stack |
|---|---|---|
| [contrib-scout](https://github.com/ahmad-punch/contrib-scout) | Answers "should I open a PR here?" for any GitHub repo: PR policy, AI-contribution rules, real outsider merge rate, stale first-issue detection | TypeScript CLI |
| [mcp-doctor](https://github.com/ahmad-punch/mcp-doctor) | Health check and linter for Model Context Protocol servers: 30 rules on schema quality, naming and annotations, smoke tests, CI-friendly scores | Python CLI |
| [nestjs-idempotency](https://github.com/ahmad-punch/nestjs-idempotency) | Safe retries for payment-style endpoints via `Idempotency-Key`, with in-memory and Redis stores and fingerprint mismatch detection | NestJS library |
| [awesome-ai-contribution-policies](https://github.com/ahmad-punch/awesome-ai-contribution-policies) | Verified, machine-readable dataset of how 100+ open source projects treat AI-assisted contributions | JSON + Markdown |
| [oss-contributor](https://github.com/ahmad-punch/oss-contributor) | Claude Code plugin that prepares policy-compliant PRs, builds minimal reproductions, and blocks forbidden commit trailers | Plugin |
| [repo-wrapped](https://github.com/ahmad-punch/repo-wrapped) | Year-in-review cards for any git repo, offline, with a shareable SVG | TypeScript CLI |

Upstream, I contribute to the NestJS ecosystem (core, GraphQL federation, Swagger), the MCP TypeScript SDK, and RAGFlow. Issues and PRs come with a reproduction and a failing test first.

---

## How I build

- **Humans vs. agents is a design decision, not an afterthought.** Decide what judgment stays with people, then encode the rest as reusable configuration.
- **Parallel fan-out reads, serialized writes.** Agents run concurrently without corrupting the system of record.
- **Extensible by configuration.** New use cases land as declarative config, not code; the system grows without redeployment.
- **Reliability over demos.** Configuration layered by volatility, automated staleness detection, learning loops that remember human rulings instead of re-asking.
- **Reasoning separated from plumbing.** Behavior lives in prompts and evals and is validated before app code is written.
- **Direct SDK by default.** Frameworks when they earn their place; RAG only when the problem actually needs it.

## Stack

Anthropic SDK · MCP · Claude Code · OpenAI Codex · Cursor · Python · TypeScript / Next.js · NestJS · Postgres + pgvector · Chroma / Qdrant · LangGraph · Ollama & local model hosting · GCP / AWS / Azure · Kubernetes · Terraform · Docker

---

NUST Electrical Engineering · NUST 50 Under 50 (2025) · Best Industrial Final Year Project, SEECS 2018 · Anthropic Claude Code certified

![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ahmad-punch&theme=dark&hide_border=true&include_all_commits=true&count_private=true&layout=compact)
