# atul

Backend & realtime infrastructure engineer. I build the systems other
products sit on top of — media servers, APIs, and the data layers behind them.

## About

I build backend infrastructure: real-time media systems, service APIs, and
the databases and queues behind them. Most of what's here is TypeScript or Go,
talking to Postgres, Redis, or a graph database, depending on the problem.

## Current focus

- **Realtime infrastructure**: WebRTC/SFU media servers, signaling, and the
  control-plane APIs and SDKs developers use to talk to them
  ([livqeno.com](https://livqeno.com) · [docs](https://docs.livqeno.com) · [SDKs](https://github.com/atulsinghhhh/livqeno-sdks))
- **Payments and ledgers in Go + PostgreSQL**: correctness under concurrency,
  retries and provider failures ([FinCore](https://github.com/atulsinghhhh/FinCore))
- **Backend services in Go**: multi-service systems for uploads, transcoding,
  and async processing ([streamvault](https://github.com/atulsinghhhh/streamvault))

## Featured projects

**[Livqeno](https://livqeno.com)**: Developer-first realtime infrastructure:
WebRTC/SFU media plane, signaling, a control API, and SDKs, so other developers
can add video/voice/chat/live-streaming without running their own media servers.
The hard part: session negotiation, ICE/TURN handling, and data-channel
reliability under real network conditions. The platform is proprietary; the
public client SDKs are in [livqeno-sdks](https://github.com/atulsinghhhh/livqeno-sdks).
`Go (Pion) · TypeScript · Redis · Postgres · Docker · Kubernetes`

**[FinCore](https://github.com/atulsinghhhh/FinCore)**: Ledger-backed payment
processing: payments, refunds, payouts and settlement reconciliation on a
double-entry ledger whose rules are enforced by PostgreSQL itself. Idempotent
APIs, a transactional outbox for webhooks, and a sweeper for lost provider
webhooks. A k6 load test ran 14,825 requests in 30 s with 0 duplicate charges
and money conserved to the paisa.
`Go · PostgreSQL · Razorpay · Next.js · k6`

**[streamvault](https://github.com/atulsinghhhh/streamvault)**: File/video
upload, storage and streaming platform, mid-rewrite from a Next.js monolith
into Go microservices (auth, API, upload, image/video workers). The hard part:
presigned direct-to-storage uploads and an async transcode pipeline that
survives worker crashes.
`Go · Next.js · Postgres · MinIO · Redis · asynq`

**[Settle](https://settle-jet.vercel.app)**: USDC checkout on Solana (devnet).
Unique payment address per order via HD wallet derivation, Sign-In With Solana
for merchants, and automated on-chain payment reconciliation into PostgreSQL.
`TypeScript · Next.js · Solana · PostgreSQL`

**[Swaraloom](https://github.com/atulsinghhhh/Swaraloom)**: Fully local,
privacy-first AI voice agent for Apple Silicon: STT/LLM/TTS pipeline with
measured benchmarks, a memory budget enforced in code, and no cloud APIs.
`Python · MLX · Qwen3`

## Other projects

[lango](https://github.com/atulsinghhhh/lango) (Flutter, spaced-repetition engine) ·
[waymark](https://github.com/atulsinghhhh/waymark) (GPS route tracking and simplification) ·
[personal-os](https://github.com/atulsinghhhh/personal-os) (Flutter)

## Technical stack

**Languages** — JavaScript · TypeScript · Go · SQL · C++ · C · Java (basic)
**Frameworks** — Next.js · React · React Native · Flutter · Express.js · NestJS · Fastify · FastAPI · Django (basic)
**Databases** — PostgreSQL · MySQL · MongoDB · Redis · Neo4j · Supabase
**Realtime** — WebRTC · Pion · WebSockets · Kafka
**Infra / DevOps** — Docker · Kubernetes · CI/CD · Azure · AWS (familiar)
**AI / LLM** — LLM API integration (Groq) · prompt engineering · LLM-generated query generation (Cypher) · RAG basics

## Engineering interests

Real-time media systems, service-to-service reliability, and reasoning
systems built on graph data rather than log search. Also interested in
applying LLMs to real backend problems — turning natural-language input into
safe, structured queries and actions instead of bolting on a chatbot.

## Contact

atulrathore667@gmail.com
