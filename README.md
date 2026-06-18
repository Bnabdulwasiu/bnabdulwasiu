# ABDULRAHMAN ABDULWASIU

Backend Engineer.
Love building things that are fast, durable, and don't break under pressure.
Currently deepening my work in API design, database internals, and async systems.

---
**Experience**

● Backend Engineer @ HNG Internship — Finalist (Graduated 140/10,000)
&nbsp;&nbsp;✦ Built and shipped backend services across multiple stages of a competitive engineering programme — from simple microservices to custom storage engines.
&nbsp;&nbsp;✦ Focused on: async APIs, database optimization, OAuth security, and file I/O systems.
&nbsp;&nbsp;✦ Integrated AI systems (LiveKit) into a team codebase for real-time AI voice interviewing.

---
**Connect With Me**

» Email &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;→ [abuumair.dev@gmail.com](mailto:abuumair.dev@gmail.com)
» LinkedIn &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;→ [linkedin.com/in/bnabdulwasiu](https://linkedin.com/in/bnabdulwasiu)
» X / Twitter &nbsp;→ [twitter.com/bnabdulwasiu](https://twitter.com/bnabdulwasiu)
» Portfolio &nbsp;&nbsp;&nbsp;&nbsp;→ [bnabdulwasiu.github.io/my-website](https://bnabdulwasiu.github.io/my-website)

---
**Skills & Tools**

» Backend &nbsp;&nbsp;&nbsp;&nbsp;· Python, FastAPI, SQLAlchemy, asyncio, Pydantic
» Databases &nbsp;· PostgreSQL, SQLite
» Auth &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;· GitHub OAuth, HTTP-only cookies, CSRF protection, JWT token refresh
» Testing &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;· Pytest, async test suites

---
**Featured Projects**

● **Background Job Scheduler** — [github.com/Bnabdulwasiu/background-worker](https://github.com/Bnabdulwasiu/background-worker)
&nbsp;&nbsp;✦ Production-grade job scheduler with a heap-based priority queue, DAG workflow support, automatic retries with exponential backoff, and a dead-letter queue for jobs that exhaust all retry attempts.
&nbsp;&nbsp;✦ DAG system lets jobs declare dependencies — e.g. Report → Upload → Email — so downstream jobs only run once their parents succeed.
&nbsp;&nbsp;✦ Starvation prevention: low-priority jobs receive automatic priority boosts over time so they are never permanently starved by high-priority traffic.
&nbsp;&nbsp;✦ Live dashboard powered by Server-Sent Events (SSE) with real-time job status updates and structured JSON logs for every lifecycle event.

● **Append-Only Event Store** — [github.com/Bnabdulwasiu/stage-8a](https://github.com/Bnabdulwasiu/stage-8a)
&nbsp;&nbsp;✦ Custom-built database engine that writes event records into an append-only log on disk and retrieves them in O(1) time using an in-memory byte-offset index.
&nbsp;&nbsp;✦ Solved a hard Unicode bug: pre-encoding to UTF-8 bytes before measuring length so that multi-byte characters (é, ü, emojis) never corrupt the offset index.
&nbsp;&nbsp;✦ Includes crash-safe startup recovery that rebuilds the index from raw bytes, skipping any torn lines left by unexpected shutdowns.

● **Insighta Labs+** — Full-Stack Analytics Suite
&nbsp;&nbsp;✦ A complete demographic data platform with three independent clients: a FastAPI backend, a Vercel-deployed web portal, and a Python CLI tool.
&nbsp;&nbsp;✦ Backend: PostgreSQL with composite indexes, connection pooling (10 active / 20 overflow), and TTL query caching that dropped response times from 320ms to <5ms.
&nbsp;&nbsp;✦ Web portal: Vanilla JS/HTML, GitHub OAuth, HTTP-only cookies, auto token refresh.
&nbsp;&nbsp;✦ CLI: `insighta` shell tool for token auth, natural-language profile queries, and CSV data export.
&nbsp;&nbsp;✦ [Backend](https://github.com/Bnabdulwasiu/insighta-backend) · [Web](https://github.com/Bnabdulwasiu/insighta-web) · [CLI](https://github.com/Bnabdulwasiu/insighta-cli) · [Live Demo](https://insighta-web-psi-neon.vercel.app)

---

I am available for backend engineering roles, API design work, and database optimization contracts.
Feel free to reach out — always happy to talk shop.

Let's build something solid together.
