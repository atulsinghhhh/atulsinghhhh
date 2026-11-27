<h1 align="center">Hey, I'm Atul 👋</h1>

<p align="center">
  <b>Backend & realtime infrastructure engineer</b><br/>
  I build the systems other products sit on top of: media servers, APIs, and the data layers behind them.
</p>

<p align="center">
  <a href="https://livqeno.com"><img src="https://img.shields.io/badge/Livqeno-live-2ea44f?style=for-the-badge" alt="Livqeno"/></a>
  <a href="https://www.linkedin.com/in/atul-singh-rathore/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://leetcode.com/u/atulsinghh/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
  <img src="https://img.shields.io/badge/Hyderabad-India-orange?style=for-the-badge" alt="Hyderabad, India"/>
</p>

---

## 🔭 Current focus

| | |
|---|---|
| 📡 **Realtime infrastructure** | WebRTC/SFU media servers, signaling, and the control-plane APIs and SDKs developers use ([livqeno.com](https://livqeno.com) · [docs](https://docs.livqeno.com) · [SDKs](https://github.com/atulsinghhhh/livqeno-sdks)) |
| 💸 **Payments & ledgers** | Go + PostgreSQL: correctness under concurrency, retries and provider failures ([FinCore](https://github.com/atulsinghhhh/FinCore)) |
| ⚙️ **Backend services in Go** | Multi-service systems for uploads, transcoding and async processing ([streamvault](https://github.com/atulsinghhhh/streamvault)) |

## 🚀 Featured projects

### 📡 [Livqeno](https://livqeno.com)
Developer-first realtime infrastructure: WebRTC/SFU media plane, signaling, a control API and SDKs, so developers can add video, voice, chat and live streaming without running their own media servers.
**The hard part:** session negotiation, ICE/TURN handling, and data-channel reliability under real network conditions. The platform is proprietary; the public client SDKs are in [livqeno-sdks](https://github.com/atulsinghhhh/livqeno-sdks).
`Go (Pion)` `TypeScript` `Redis` `Postgres` `Docker` `Kubernetes`

### 💸 [FinCore](https://github.com/atulsinghhhh/FinCore)
Ledger-backed payment processing: payments, refunds, payouts and settlement reconciliation on a double-entry ledger whose rules are enforced by PostgreSQL itself. Idempotent APIs, a transactional outbox for webhooks, and a sweeper for lost provider webhooks.
**Result:** k6 load test, 14,825 requests in 30 s, 0 duplicate charges, money conserved to the paisa.
`Go` `PostgreSQL` `Razorpay` `Next.js` `k6`

### 🎞️ [streamvault](https://github.com/atulsinghhhh/streamvault)
File/video upload, storage and streaming platform, mid-rewrite from a Next.js monolith into Go microservices (auth, API, upload, image/video workers).
**The hard part:** presigned direct-to-storage uploads and an async transcode pipeline that survives worker crashes.
`Go` `Next.js` `Postgres` `MinIO` `Redis` `asynq`

### ◎ [Settle](https://settle-jet.vercel.app)
USDC checkout on Solana (devnet). Unique payment address per order via HD wallet derivation, Sign-In With Solana for merchants, and automated on-chain payment reconciliation into PostgreSQL.
`TypeScript` `Next.js` `Solana` `PostgreSQL`

### 🎙️ [Swaraloom](https://github.com/atulsinghhhh/Swaraloom)
Fully local, privacy-first AI voice agent for Apple Silicon: STT/LLM/TTS pipeline with measured benchmarks, a memory budget enforced in code, and no cloud APIs.
`Python` `MLX` `Qwen3`

**Also:** [lango](https://github.com/atulsinghhhh/lango) (Flutter, spaced-repetition engine) · [waymark](https://github.com/atulsinghhhh/waymark) (GPS route tracking and simplification) · [personal-os](https://github.com/atulsinghhhh/personal-os) (Flutter)

## 🛠️ Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=js,ts,go,py,cpp,java&perline=6" alt="Languages"/><br/>
  <img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,express,nestjs,flutter&perline=6" alt="Frameworks"/><br/>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,supabase,prisma&perline=6" alt="Databases"/><br/>
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,githubactions,prometheus,grafana,azure&perline=6" alt="Infra"/>
</p>

**Also:** Fastify · FastAPI · Django (basic) · Neo4j · Kafka · C · AWS (familiar)  
**Realtime:** WebRTC · Pion · WebSockets  
**AI / LLM:** LLM API integration (Groq) · prompt engineering · LLM-generated query generation (Cypher) · local LLMs (MLX, Qwen3) · STT/TTS · RAG basics

## 📊 GitHub stats

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=atulsinghhhh&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats"/>
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=atulsinghhhh&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages"/>
</p>

## 💡 Engineering interests

- 🗄️ **Databases:** correctness at the data layer, such as ledger rules enforced inside PostgreSQL, idempotency, transactional outboxes and query/API performance, across Postgres, MongoDB, Redis and graph data.
- 🤖 **AI / ML:** applying LLMs to real backend problems, such as local STT → LLM → TTS voice agents with measured latency and memory, RAG, and turning natural-language input into safe, structured queries and actions instead of bolting on a chatbot.
- 📡 **Real-time systems:** media servers and service-to-service reliability.

## 📫 Contact

atulrathore667@gmail.com
