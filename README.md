# Julio David Arriaga

Technical Program Manager · 6+ years in the payment industry — authentication, certification, and card lifecycle.

CS from Universidad Simón Bolívar · MIS Masters from Washington University in St. Louis.

---

## Factoria

An AI-powered assembly line for building and shipping products. Six MCP services orchestrated by Claude, connected through a shared methodology that treats every failure as curriculum and every session as compounding infrastructure.

The thesis: after the factory is built, each new app costs ~$4 and 3–4 sessions. The factory itself took ~$30 and 37 sessions.

### Shipped

**[Flow](https://github.com/juliodavid8a/flow-app)** — Energy-aware productivity app. Schedules work by energy level, not just time. 812+ tests. WhatsApp integration. MCP server with 18 tools that doubles as the orchestrator's operating system.

**[Ship Lab](https://github.com/juliodavid8a/Ship-Lab)** — AI-powered testing and analysis toolkit. Eight headless labs (security, compliance, scale readiness, brand, quality, growth, kickstart, continuous improvement) + MCP server with 6 tools. 633+ tests, 22K+ LOC.

**[CC-Runner](https://github.com/juliodavid8a/cc-runner)** — MCP server that lets an AI orchestrator invoke Claude Code directly. Runs on Railway. Hardened: bearer auth, branch sanitization, per-repo mutex, session TTL, orphan process kill. Prompt telemetry writes to Supabase automatically — zero manual archiving.

**[Personal Wiki](https://github.com/juliodavid8a/personal-wiki)** — Knowledge graph + spaced repetition + wiki pages + chat. 113+ knowledge nodes, 100+ wiki pages, 102+ edges, 19 MCP tools. Editorial typography. Mermaid diagram rendering. The knowledge layer that persists what sessions learn.

**[GrocerBot](https://github.com/juliodavid8a/GrocerBot)** — AI grocery assistant. Mom sends a list in Venezuelan Spanish on WhatsApp, the bot builds the cart on SAP Commerce, son pays. 63-item corpus validated. 52 tests.

**[Megafono](https://github.com/juliodavid8a/Megafono)** — Personal branding content OS for X/Twitter. MCP server with 7 tools. OAuth 1.0a for X API, Auth0 OAuth for MCP authentication.

### The Stack

React · Node.js · Express · Vite · Next.js · Supabase (Postgres + RLS) · Vercel · Railway · Claude Code · MCP (Model Context Protocol) · Auth0 OAuth · WhatsApp Cloud API · D3.js · Tailwind

### The Methodology

26 sparks — philosophical insights extracted from building. A few that shaped the architecture:

- *Single source of truth or silent lies* — two sources means one is always wrong
- *Quality gates atrophy under urgency* — structural enforcement over discipline
- *Automate the bridge, elevate the antenna* — free the human from mechanical relay
- *Speed through precision* — route cognitive work to the cheapest capable layer
- *One-shot materialization* — infrastructure looks like overhead until it crosses the threshold where ideas ship in one session

The full methodology lives in [SOUL.md](https://github.com/juliodavid8a/flow-app) and the sparks corpus in the Personal Wiki.

---

*"I went from being the MCP server to building one."*
