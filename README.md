# Hey, I'm Aleksandr

Full-stack engineer in Helsinki. My home turf is TypeScript and Node.js (NestJS, React, Next.js) on AWS, with Python a close second for the ML work: fine-tuning, MLX, FastAPI. I'm just as comfortable in Go, Swift, and Flutter when a project calls for it. agentvault is Go, the mlx-audio-swift work is Swift, the mobile stuff is Flutter and Kotlin.

Most of my recent work is on-device AI: RAG and hybrid search, LoRA/QLoRA fine-tuning, converting PyTorch models to MLX and the Apple Neural Engine, and getting models small enough to run on a laptop with no cloud. I like taking ideas from "not sure this will work" to running in production.

## What I'm working on

[agentvault](https://github.com/beshkenadze/agentvault) — agent-agnostic secret broker for macOS. Lets AI coding agents run real commands with credentials they never see in plaintext. The secret is injected into a child process and masked at the source, so the agent only ever reads back `{{AV:NAME}}` in stdout, logs, and errors. Touch ID gated, daemon + thin CLI, pluggable backends (age file, Keychain, 1Password). Written in Go.

[arxiv-search](https://github.com/beshkenadze/arxiv-search) — semantic search across 1M+ arXiv papers, runs entirely in your browser. Zero infrastructure costs. This one got some traction.

[Kaban](https://github.com/kaban-board/kaban) — terminal Kanban board built for AI code agents. Has an MCP server so Claude Code, Cursor, etc. can manage their own task boards.

[us-legal-tools](https://github.com/beshkenadze/us-legal-tools) — TypeScript SDKs for US legal APIs (eCFR, Federal Register, CourtListener, GovInfo, DOL). Auto-generated from OpenAPI specs, monorepo with Turborepo. Five packages published to npm.

[eyecite-js](https://github.com/beshkenadze/eyecite-js) — TypeScript port of Free Law Project's eyecite library for extracting legal citations from text.

## Open source I contribute to

[mlx-audio](https://github.com/Blaizzy/mlx-audio) — one of the top contributors to this on-device speech library for Apple Silicon (7.4k stars). Text-to-speech, speech-to-text, and audio models running locally through Apple's MLX. This is where most of my on-device speech work lives.

[mlx-audio-swift](https://github.com/Blaizzy/mlx-audio-swift) — the Swift side of mlx-audio (682 stars), bringing the same on-device audio models to native Apple apps.

[mlx-vlm](https://github.com/Blaizzy/mlx-vlm) — vision-language models on MLX (5k stars). Run and fine-tune VLMs locally on Apple Silicon.

## Products I ship

Small Mac apps and dev tools under [bshk.app](https://bshk.app). Pay once, local-first, no telemetry.

[Tish](https://tish.bshk.app) — real-time noise cancellation, call recording, live transcription, and AI meeting summaries. Apple Silicon native.

[Solovey](https://solovey.bshk.app) — audio cleanup for creators. Drag-and-drop post-processing that removes noise, evens volume, and polishes voice recordings. All on device.

[Zamok](https://zamok.bshk.app) — self-hosted license key management for indie devs. Offline certs, native SDKs. Open source.

[AppGenie](https://appgenie.bshk.app) — no-code AI mini-apps for Jira. Describe an action, get a button. Built on Atlassian Forge.

## Older projects I still care about

[Caesar](https://caesar.team) — open-source zero-knowledge password manager for teams. AES-256 + RSA-4096, all encryption client-side, the server never sees plaintext. I designed the crypto architecture and built it from scratch.

[bitnami-pgvector-search](https://github.com/beshkenadze/bitnami-pgvector-search) — multi-arch Docker image combining PostgreSQL, pgvector, and pg_search. Gets auto-built and tested via GitHub Actions.
