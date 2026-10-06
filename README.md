# Zaal Panthaki

Founder, Operator, and Systems Architect.

I build **The ZAO**, advise founders through **BetterCallZaal**, and architect the open-source software and autonomous agent systems our estate runs on.

Primary hub and portfolio: [bettercallzaal.com](https://bettercallzaal.com) | [thezao.xyz](https://thezao.xyz) | [Live Estate Dashboard](https://bettercallzaal.github.io/zao-repos/)

---

## Executive Summary

I work at the intersection of music, culture, autonomous AI systems, and web3 mechanisms, with a strict bias toward shipping software and producing physical events in public rather than pitching decks.

The core thesis across all my work is structural: **the people who create the value should own their profit margin, data, and intellectual property.** This conviction originated in the decentralized ownership movements around transparent market mechanics (GME / Superstonk / DRS) and directly informs how I design token mechanics, governance contracts, and agent coordination networks.

Under the operating umbrella of **BCZ Strategies LLC**, I run:
1. **The ZAO:** A decentralized impact network returning profit margin, audience data, and IP rights to artists (music-first).
2. **BetterCallZaal:** An operator and advisory practice building alongside founders moving into autonomous agents, on-chain mechanisms, and open-source infrastructure.
3. **Physical Events and Festivals:** Real-world productions including ZAOstock, COC Concertz, and live community assemblies.
4. **Autonomous Agent Fleets:** A multi-agent estate of specialized coding, research, and governance agents operating continuously across 130+ public repositories.

---

## Core Competencies and Technical Architecture

### 1. Autonomous Agent Fleet Orchestration
- **Multi-Agent Runtimes:** Architect of distributed agent systems across ZOE (executive cortex), Orca (isolated worktree and terminal runtime), Hermes (coding and PR reviewer), and Antigravity (planning and discovery).
- **Crash-Safe Execution:** Author of durable side-effect protocols including `effect_intents` transactional outboxes, atomic claim locks (`INSERT ... ON CONFLICT DO NOTHING`), and fenced execution leases.
- **Machine-Readable Proofs:** Implementer of the DreamNet receipt contract (`dreamnet.receipt.v1`), cryptographic `ProofDropV1` evidence anchors, and tamper-evident content hashing (`dreamnet-sorted-json:v0` + SHA-256).
- **Layered Memory Systems:** Design of cognitive memory stacks separating working context, episodic logs, vector recall, and knowledge graph persistence (Bonfire, Spore).
- **Human-in-the-Loop Gating:** Structural enforcement where drafting, exploration, and testing are free, but irreversible one-way doors (on-chain transactions, public publishing, external messaging, database migrations) halt for human authorization.

### 2. On-Chain Mechanisms and Protocol Design
- **Soulbound Social Governance:** Designed and operate the ZAO Fractal Respect system: non-transferable, non-financialized ERC-20 and ERC-1155 soulbound tokens on Optimism that tie governance power strictly to verified labor and contribution, preventing plutocratic capital takeovers.
- **Optimistic Execution:** Implemented OREC (Optimistic Respect Execution Contracts) with 72-hour community review and veto windows.
- **Prediction and Battle Markets:** Architect of WaveWarZ live music battles, utilizing Solana Program Derived Addresses (PDAs) and Base contracts to settle live spectator wagers directly to artist wallets.
- **Decentralized Media and Storage:** Farcaster protocol integration (Neynar API, Hubs, frame/cast mechanics), Arweave permanent audio metadata and NFT distribution, and XMTP messaging.

### 3. Full-Stack Systems Engineering
- **Frontend and Application:** Next.js 16, React 19, TypeScript, Tailwind CSS, Vanilla CSS design systems, WebSockets, LiveKit audio rooms.
- **Backend and Data:** Node.js, Python, PostgreSQL, Supabase (Row Level Security, Edge Functions, pgvector), Redis.
- **DevOps and Workflows:** Git worktree fleet isolation, GitHub Actions serverless cron pipelines, Fly.io deployments, automated CI lint/typecheck/eval gates.

---

## Production Portfolio

The estate is organized into live production platforms, open-source repositories, and physical event infrastructure:

| Product / Platform | Role | Description and Architecture | Live Surface |
|---|---|---|---|
| **The ZAO** | Founder, Architect | Decentralized impact network returning margin, data, and IP to artists. Operates across 100+ unbroken weeks of on-chain Fractal governance. | [thezao.com](https://thezao.com) / [thezao.xyz](https://thezao.xyz) |
| **WaveWarZ** | Co-Founder, Lead Architect | Live-traded music battles where audiences take on-chain positions on battle outcomes, settling directly to artists. Built on Solana mainnet and Base. | [wavewarz.com](https://wavewarz.com) |
| **ZAOstock** | Producer, Lead Operator | Independent music festival and street parklet gathering in Ellsworth, Maine (8 acts, live audio, community parklet, local business integration). | [zaostock.com](https://zaostock.com) |
| **ZAO OS** | Core Developer | Open-source monorepo powering community chat, music curation, proposal voting, and agent control plane. | [zaoos.com](https://zaoos.com) / [GitHub](https://github.com/bettercallzaal/ZAOOS) |
| **poidhz** | Creator, Maintainer | Decentralized task and bounty network: post an objective, provide cryptographic proof of completion, receive direct payout. | [poidhz.com](https://poidhz.com) |
| **ZABAL Gamez** | Organizer, Lead Mentor | Three-month builder battle and workshop cohort for developers and artists building in public across web3 and AI. | [zabal.art](https://zabal.art) |
| **ZAOscout** | Co-Creator | Keyless social research scout using a no-key mirror trio (Redlib, FxTwitter, Haatz) with provider-agnostic LLM synthesis. | [GitHub](https://github.com/ZAODEVZ/ZAOscout) |
| **COC Concertz** | Producer | Live concert series and artist showcase network. | [thezao.xyz](https://thezao.xyz) |
| **FISHBOWLZ** | Architect | Live-streamed audio rooms and interactive listening sessions with autonomous agent co-hosts. | [thezao.xyz](https://thezao.xyz) |

---

## Open Source Estate and Research Library

Everything we build is counted, measured, and maintained in the open:

- **130+ Public Repositories:** Continuously tracked on the live [Estate Dashboard](https://bettercallzaal.github.io/zao-repos/) across `bettercallzaal`, `ZAODEVZ`, and `ZAO-DEVZ`.
- **2,600+ Research Documents:** An open library of deep audits, benchmarks, and architecture specifications located in [bettercallzaal/ZAOOS/research/](https://github.com/bettercallzaal/ZAOOS/tree/main/research).
- **Sovereign Context Hub (ICM):** Machine-readable context boxes published via `context.thezao.com` and `bettercallzaal/zao-icm` for zero-hallucination agent grounding.

---

## Operating Principles

The estate runs under four core operational rules:

1. **Measure, don't assert:** A peer's diagnosis is not a measurement. Run it before you relay it. A figure whose inputs cannot be obtained again is a memory, not a measurement.
2. **Adversarial verification:** A test that has never failed has not been shown to work; point it at the broken version first. A red control must run against a different artifact than the one under test.
3. **Write it down, then automate it:** The whole estate coordinates through a shared vault of markdown that agents and people both read. When something breaks twice, it gets a tool instead of a reminder.
4. **Nothing publishes itself:** Drafting is free; sending is not. Irreversible actions (financial movements, on-chain transactions, public publishing, destructive migrations) stop and require explicit human sign-off.

---

## Connect and Work Together

I advise select founders, build custom autonomous agent workflows, and collaborate on decentralized music and media initiatives.

- **Book a Call:** [cal.com/bettercallzaal](https://cal.com/bettercallzaal)
- **Farcaster:** [@zaal](https://warpcast.com/zaal)
- **X (Twitter):** [@bettercallzaal](https://x.com/bettercallzaal)
- **YouTube:** [@bettercallzaal](https://youtube.com/@bettercallzaal)
- **Daily Build Log:** [thezao.xyz/today](https://thezao.xyz/today)
- **Email:** Contact via [bettercallzaal.com](https://bettercallzaal.com) or DM on Farcaster/X
