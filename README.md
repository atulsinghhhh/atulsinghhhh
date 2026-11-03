# atul

Backend & realtime infrastructure engineer. I build the systems other
products sit on top of — media servers, APIs, and the data layers behind them.

## About

I build backend infrastructure: real-time media systems, service APIs, and
the databases and queues behind them. Most of what's here is TypeScript or Go,
talking to Postgres, Redis, or a graph database, depending on the problem.

## Current focus

- **Realtime infrastructure** — WebRTC/SFU media servers, signaling, and the
  control-plane APIs and SDKs developers use to talk to them ([Livqeno](https://github.com/atulsinghhhh/Livqeno) · [livqeno.com](https://livqeno.com))
- **Backend services in Go** — multi-service systems for uploads, transcoding,
  and async processing ([streamvault](https://github.com/atulsinghhhh/streamvault))

## Featured projects

**[Livqeno](https://github.com/atulsinghhhh/Livqeno)** — Developer-first realtime
infrastructure: WebRTC/SFU media plane, signaling, a control API, and SDKs, so
other developers can add video/voice/chat/live-streaming without running their
own media servers. The hard part: session negotiation, ICE/TURN handling, and
data-channel reliability under real network conditions. [livqeno.com](https://livqeno.com)
`TypeScript · Pion (Go) · Redis · Postgres`

**[streamvault](https://github.com/atulsinghhhh/streamvault)** — File/video
upload, storage and streaming platform, mid-rewrite from a Next.js monolith
into Go microservices (auth, API, upload, image/video workers). The hard part:
presigned direct-to-storage uploads and an async transcode pipeline that
survives worker crashes.
`Go · Next.js · Postgres · MinIO · Redis · asynq`

**[lango](https://github.com/atulsinghhhh/lango)** — Flutter app for learning
Korean and Japanese together, with a hand-built SM-2 spaced-repetition engine
and Supabase auth/RLS. The hard part: making two non-Latin scripts feel
equally first-class in one UI.
`Flutter/Dart · Supabase (Postgres + RLS)`

**[waymark](https://github.com/atulsinghhhh/waymark)** — Personal exploration
map: GPS walk tracking with accuracy/duplicate/speed filtering, Douglas–Peucker
route simplification, and offline-safe recording. The hard part: making a GPS
pipeline that behaves on a real phone, not just a demo.
`TypeScript · SQLite · argon2id/JWT`

## Technical stack

**Backend** — Go · TypeScript (Node) · Express
**Realtime** — WebRTC · Pion · WebSockets
**Data** — PostgreSQL · Redis · Neo4j · Supabase
**Infra** — Docker · MinIO · asynq
**Frontend / mobile** — Next.js · React · Flutter

## Engineering interests

Real-time media systems, service-to-service reliability, and reasoning
systems built on graph data rather than log search.

## Contact

atulrathore667@gmail.com
