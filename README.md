<h1 align="center">Amanuel Merara Gutu</h1>

<p align="center">
  <b>Software Engineer</b> · LLM Evaluation &amp; Alignment · Backend / RAG Systems
</p>

<p align="center">
  <a href="https://linkedin.com/in/amanuel-merara-3bb71a36a">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:amanuel.merara@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

AI-focused software engineer building **production systems** with hands-on **frontier-LLM evaluation** experience. I've been contracted to **Anthropic (via Revelo)** to evaluate Claude Code's production PRs — generating the preference data behind RLHF and reward-model training — and I now author expert coding trajectories at **AfterQuery** that teach frontier models to reason.

I like working where **alignment research meets real engineering**: not just labeling data, but building the RAG platforms and evaluation harnesses that turn "is this answer good?" into a reproducible, regression-tested metric.

### 🧠 AI Engineering

Hands-on experience shaping how frontier models learn — from generating the preference data behind RLHF to building the eval infrastructure that measures whether a model is actually right.

- **Frontier-model evaluation @ Anthropic (via Revelo).** Evaluated & ranked **50+ AI-generated PRs** across real-world Python repos — scoring correctness, test coverage, and edge-case handling at an **80% first-pass acceptance rate** — producing the preference labels that fed **RLHF and reward-model training**.
- **Training-data authorship @ AfterQuery.** Author **expert coding trajectories** (reference solutions + stepwise reasoning) across **12+ repositories, 4 languages, and 6+ problem types**, plus agentic coding environments that teach models how an expert resolves multi-file problems.
- **RAG evaluation harnesses.** Build eval systems that measure **hit rate, MRR, precision@k, and LLM-as-judge** groundedness/relevance on auto-generated test sets — making answer quality a reproducible, regression-tested metric instead of a vibe.
- **Applied LLM systems.** Embeddings & vector retrieval (pgvector), Claude API & Gemini, LangChain, Socratic RAG tutoring, and token-by-token SSE streaming with source citations.

### ⚙️ Backend Engineering

Shipping production backends with an eye for latency, resilience, and clean service boundaries.

- **Performance.** Rebuilt chat-history storage as a standalone **Go microservice** over MongoDB, cutting response latency **263ms → 41ms (~84%)** as an independently scalable service with its own datastore.
- **Resilience & caching.** Integrated 3 external FX APIs behind a **Redis write-through cache** with scheduled refresh and provider failover — **cutting redundant upstream calls ~80%**.
- **Event-driven systems.** Shipped an event-driven price-drop alert feature (Firebase Cloud Messaging) on a product ranked **#1 of 13** company-wide; comfortable with async workers (Celery), WebSockets, and SSE.
- **Architecture & quality.** Multi-tenant APIs, JWT/RBAC auth, SSRF-guarded ingestion, encrypted BYOK, Dockerized services, and CI/CD — always backed by real test suites (**115-** and **70+-test** pytest suites on recent projects).

### What I'm doing now

- 🔬 Authoring expert coding trajectories & agentic environments that train frontier LLMs — **@ AfterQuery**
- 🏗️ Building RAG systems and scalable backends with **FastAPI**, **Go**, and **Next.js**
- 📚 **Head of Education** — mentoring **40+ engineers** in DSA, algorithms & system design
- 🌱 Going deeper on **system design, cloud deployment workflows, and Go internals**

### Selected work

**[AlgoMentor](https://github.com/Amaankaa/AlgoMentor)** — *Graph-Guided RAG Learning Platform*
Multi-tenant full-stack SaaS (FastAPI + Next.js, 46 endpoints / 19 Postgres tables) with top-12 pgvector retrieval over Gemini embeddings, async Celery + Redis ingestion, and token-by-token SSE streaming. Includes a **RAG evaluation harness** (hit rate, MRR, precision@k, LLM-as-judge) and a prerequisite-graph engine that recommends what to study next. Shipped with a 115-test suite and CI/CD to DigitalOcean.

**SafeSight Analytics** — *Real-time Video Surveillance Platform*
Async FastAPI backend for real-time monitoring — REST + WebSocket alerting, a configurable rules engine, role-based access, and a DeepFace vision integration. Backed by a 70+ test pytest suite and Docker Compose.

### Tech I work with

**Languages** — Python · Go · TypeScript · JavaScript · C++ · Java
**Backend** — FastAPI · Gin (Go) · Node.js · REST · WebSockets · SSE · Celery
**AI / LLM** — RAG · Embeddings · pgvector · LangChain · Claude API · Gemini · RLHF & Evaluation
**Data / Infra** — PostgreSQL · MongoDB · Redis · MySQL · Docker · GitHub Actions · Linux
**Frontend** — React · Next.js · Tailwind CSS

### Beyond the code

Google-backed (**A2SV**) competitive programmer — **1,000+ problems** solved across LeetCode & Codeforces, 26+ rated contests. I care about clean architecture, correctness, and code that's a pleasure for the next person to read.

<p align="center"><i>Open to roles in AI/LLM engineering, alignment & evaluation, and backend systems.</i></p>
