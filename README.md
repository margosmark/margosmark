# Hi, I'm Mark 👋

**Senior Software Engineer** — AI platforms, developer experience & distributed systems.

I build the systems engineers use to ship: CI/CD guardrails, LLM gateways, MCP servers, and tooling that makes AI-assisted development safe and practical at scale.

## Featured projects

### 💰 [fintrack](https://github.com/margosmark/fintrack)
Self-hosted personal finance tracker: OFX/CSV import, investments & portfolio
analytics, a Canadian tax engine (ACB, Schedule 3), reporting, privacy mode and
local-first AI categorization. Python/FastAPI + React + Android, with Postgres
row-level security and importers for RBC, Questrade, IBKR and Wealthsimple.

### ⚡ [electricity-dashboard](https://github.com/margosmark/electricity-dashboard)
Ontario electricity cost analyzer for Green Button data: compares Time-of-Use,
Tiered and Ultra-Low Overnight plans, estimates always-on base load, and charts
usage as a weekday × hour heatmap. Runs entirely client-side, with optional
OAuth2 auto-import. Live at [electricity.markarslan.ca](https://electricity.markarslan.ca).

### 🛡️ [arch-guard](https://github.com/margosmark/arch-guard)
Deterministic validation that LLM-generated (or human) code conforms to the
architecture declared in your ADRs/PECs/plans — spec in, dependency graph out,
mermaid diffs in PRs, no LLM in the hot path.

### 🔌 [omada-mcp](https://github.com/margosmark/omada-mcp)
MCP server for TP-Link Omada controllers — inspect sites, devices, clients, VLANs,
ACLs, NAT, mDNS and QoS. **Read-only by default**: writes are flag-gated, dry-run
until explicitly confirmed, and bound to a fixed whitelist.

### 🌐 [llm-gateway](https://github.com/margosmark/llm-gateway)
Personal, LAN-only OpenAI-compatible LLM gateway: provider adapters, alias
routing, safe fallback and an owner console — eight providers behind one wire,
with a fail-closed egress boundary for local endpoints.

### 🔊 [listn](https://github.com/margosmark/listn)
Local-first audio capture and transcription for macOS and Linux, powered by Whisper.
Menu-bar app captures system audio + mic on separate tracks (Me / Others), with a
Unix-socket local web UI, no cloud APIs and no telemetry.

---

A common thread: private by default, safety enforced in code rather than in
review, and systems designed to degrade closed rather than fail open.

🤖 I also build on [hermes-agent](https://github.com/NousResearch/hermes-agent)
and run my own LLM gateway in front of it.
