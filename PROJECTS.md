# Yousif Khalid - Engineering project index

Last verified: 3 September 2026. Status labels are deliberate: a live site is not automatically a finished application, and a private case study is not presented as public source.

## Core AI and agent systems

### AI Workforce / AZS v1 - live private system

Python, asyncio, FastAPI, WebSockets, SQLite/sqlite-vec, Ollama, Git worktrees, FFmpeg, ComfyUI.

A six-role engineering workforce spanning planning, implementation, QA, security, and integration. It uses dependency-aware scheduling, isolated worktrees, bounded repair loops, resumable state, token-budgeted Obsidian retrieval, deny-by-default approvals, local/cloud model routing, and auditable execution. Some capability planes remain off by default or are not wired into the main surface; this is a working platform, not a claim that every experimental module is production-active.

### AZS v2 - active private platform

TypeScript, pnpm, Zod, PGlite/PostgreSQL, row-level security, Vitest, Playwright, MCP, Ollama/LiteLLM.

A typed successor with an eleven-step dispatch path, pre-call budget reservations, quotas, append-only receipts, resumable workflows, approval gates, and a fourteen-stage merge gate. The repository contains separate capability planes for perception, memory, learning, codebase analysis, evaluation, design, media, video, Obsidian, prompt construction, and more. Several surfaces are implemented and tested but still lack live callers, which is documented rather than hidden.

### AZS Atelier - shipped subsystem

TypeScript and PGlite-backed design-technique memory. It ingests source evidence as inert data, requires verbatim evidence, retokenizes techniques against a design system, gates them, remembers them, and recalls them for later builds. Recorded gate: 71/71 tests.

### CodeSmith - public source

Python, Ollama, ReAct-style planning and tool use. A fully local coding agent that edits real repositories, executes in a scrubbed environment, learns from failures, and refuses completion until verification succeeds. Public documentation records 191 passing offline tests.

Source: https://github.com/TJVFIT/codesmith

### AZS Roster - public plugin package

A Claude Code plugin marketplace containing fourteen agent roles, six commands, four skills, MCP integration, and gate hooks.

Source: https://github.com/TJVFIT/azs-roster

### AZS v3 Agent Fabric - architecture only

Planning and contract documents for the agent-verification layer above AZS v2. There is intentionally no implementation yet, so it is not represented as shipped software.

## Desktop applications and operating systems

### ARGEVID - shipped Windows v0.1

Tauri 2, Rust, Python/FastAPI sidecar, Next.js, faster-whisper, Ollama, FFmpeg, MCP.

A local natural-language video editor with validated edit plans, real cuts, silence removal, captions, music ducking and loudness control, timeline editing, and propose/simulate/diff/apply behavior. Packaged-binary proof includes a 55.666-second input cut to exactly 12.000 seconds and thirty byte-identical undos. Recorded gate: 245 engine tests, 14 sidecar tests, and 398 Turkish/English keys. Several engine-complete controls still lack UI, and it is not positioned as a full NLE replacement.

### ARGE.OS v1 - shipped Windows desktop system

Tauri 2, Rust, Next.js, TypeScript, SQLite, Ollama.

A local Turkish agency operating system covering staff and fleet data, shoots, conflict/travel detection, content workflows, approvals, client portal surfaces, and billing. Recorded gate: 365 unit/property/adversarial tests, 20 Playwright tests, 750 bilingual keys, and an NSIS installer. External publishing remains simulated unless the owner configures real platform credentials.

### ARGE.OS v2 - private, not shipped

FastAPI, SQLAlchemy/Alembic, SQLite/PostgreSQL, Huey, two Next.js applications, FFmpeg, Blender, Ollama, ComfyUI, MCP.

A multi-tenant agency SaaS rebuild with authenticated tenant boundaries, content-generation jobs, reel production, timeline editing, a client portal, and fifteen MCP tools. The engineering gate has nineteen checks; live social publishing remains intentionally dry-run and the system is not presented as deployed.

### AgencyOS - earlier private system

An earlier, separate Tauri/Supabase/Ollama agency application with a native installer, client approvals, workers, and local caption fallback. The July 2026 project record documents 252 tests and a live worker heartbeat. It still requires owner-managed account and credential setup and is not claimed as a current public deployment.

### SHAMASI.OS - Phase 1 built and packaged

TypeScript, Next.js, SQLite, Tauri/Rust.

An offline-first inventory, costing, and financial-health system for a handmade-art studio. Money is integer kuruş, stock is derived from an append-only event ledger, and outbound drafts are invalidated when stock or price changes. The repository documents 51 tests and contains a Tauri binary and NSIS setup. Email, WhatsApp, and posting phases remain future work.

## Project Zero - deterministic local-first business software

The reusable Tauri/Rust/TypeScript runtime keeps model suggestions behind explicit acceptance while deterministic engines own money and business calculations. Demo mutations require a product-bound signed license; permissions, audit records, Turkish/English parity, and offline behavior are gate-enforced.

### First five packaged tools

- **StockGuard** - stock/sales/price-list import, days-of-stock computation, and reorder drafts.
- **PriceRight / Doğru Fiyat** - cost-card pricing and margin engine with editable fee schedules.
- **ResellerROI / Gerçek Kâr** - exact-cent resale-profit ledger with schedule-versus-export fee reconciliation.
- **Appointment Reminder** - deterministic reminder drafting and owner-clicked SMTP through Windows Credential Manager; no timer sends.
- **Muhasebe Asistanı** - Turkish-first local accounting assistant for onboarding memory, invoice aging, receipt categorization, tax calendar, and approval drafts.

The recorded close-out totals 808 TypeScript tests plus dedicated Rust suites and five NSIS installers. A later re-audit identified remaining product-level issues, so these are described as packaged tools rather than perfected commercial releases.

### NOVA / Restoran Arka Ofisi - substantial release candidate

A Tauri/Rust/TypeScript restaurant back-office assistant for sales-day analysis, price and cost evidence, waste/dead-item reasoning, purchasing drafts, approvals, and exports. The current verified snapshot records 1,234 Vitest cases plus ten skips and a clean typecheck. Build 13 is staged but has not completed the latest real-store buyer test, so it is not called a finished catalog release.

### Active and partial Project Zero work

The current runtime also contains E-Ticaret Asistanı, Ön Büro Çalışanı, DeadlineWatch, Recipe Cost Clerk, and SoloBoard work. These are active/partial implementation surfaces and are intentionally excluded from the shipped-product count.

## Product engineering programs

### Twenty-product factory - five completed applications

The program researched twenty sectors and produced source-cited briefs, product concepts, brands, legal pages, launch sites, and short demos. Five applications completed the full product pipeline:

- **Formatra** - Tauri/NSIS publishing-revenue tool; recorded 146 tests.
- **PackPath** - semiconductor planning web tool; recorded 248 tests.
- **CupBuffer** - Tauri coffee operations tool; recorded 350 tests.
- **SlipHedge** - aviation operations web tool; recorded 265 tests.
- **OrderTide** - maritime operations web tool; recorded 289 tests.

**TrailProof** has a zero-network Rust PDF worker and a separate Windows Job Object sandbox launcher, but OCR/rules/LLM/export phases remain deferred. The other fourteen product applications remain concepts/plans, not shipped software.

### Product Factory compiler - built developer tool

Python, YAML, openpyxl, ReportLab, PyPDF.

A content-agnostic compiler that emits Turkish-capable XLSX, PDF, text, metadata, claims records, and byte-identical ZIP packages from one YAML specification. Independent gates check schema, formulas, placeholders, duplicates, claims, font coverage, and output determinism.

## Live web and product delivery

### TJFit - live product

Next.js 14, TypeScript, Tailwind, Supabase, Gumroad. A live five-language fitness platform with training and nutrition bundles, AI plan/chat flows, authentication, content, commerce, coaching marketplace, and community surfaces. The recorded merge gate is 418/418 tests with a clean typecheck and production build.

Live: https://tjfit.org

### ArgeDijital - live storefront

Next.js 16, React 19, structured catalog data, Turkish-language and hallucination gates. The live storefront unifies forty digital products and five bundles with legal, product, contact, and purchase journeys.

Live: https://argedijital.shop

### Client and small-business sites

- **İşin Kadınları / ALARA** - live Ankara women-entrepreneur platform, built with Next.js, React, Tailwind, Framer Motion, and Lenis: https://isinkadinlari.com
- **SHAMASI** - live bilingual handmade-art funnel with Next.js, React, and WebGL presentation: https://shamasi.vercel.app
- **Aura VIP Kuaför** - live noindex preview with a booking wizard, GSAP/Lenis, and Three.js; content still contains client-owned placeholders: https://aura-vip-kuafor.vercel.app
- **EsnafKit** - live Turkish digital-product site: https://esnafkit.vercel.app
- **PazarKit** - live Turkish digital-product site: https://pazarkit.vercel.app
- **EB Hair Studio** - built Turkish site and Telegram long-poll booking flow; not deployed.
- **ARG1 union** - built eight-page site on an unmerged branch; not live.
- **ArgeFabrika** - private source and live agency presence: https://argefabrika.vercel.app

### Forty-site evidence and product portfolio - all live

Twenty source-grounded sector intelligence sites contain 257 structured, cited statistic rows. Twenty paired product-concept sites include legal pages, machine-readable briefs, and short reels. All forty deployment URLs returned HTTP 200 on 3 September 2026.

Product sites:

- [CupBuffer](https://cupbuffer.vercel.app), [ShelfCandor](https://shelfcandor.vercel.app), [TrailProof](https://trailproof-seven.vercel.app), [Formatra](https://formatra.vercel.app), [OrbitDocket](https://orbitdocket-sand.vercel.app)
- [PackPath](https://packpath-pi.vercel.app), [TrialLog](https://triallog.vercel.app), [BenchFeed](https://benchfeed.vercel.app), [CliffSight](https://cliffsight.vercel.app), [RepairRamp](https://repairramp.vercel.app)
- [OrderTide](https://ordertide.vercel.app), [SlipHedge](https://sliphedge.vercel.app), [Wayshift](https://wayshift.vercel.app), [Portbridge](https://portbridge-smoky.vercel.app), [PressWave](https://presswave.vercel.app)
- [Fillroom](https://fillroom.vercel.app), [RailCast](https://railcast.vercel.app), [OfftakeIQ](https://offtakeiq.vercel.app), [Recase](https://recase-tau.vercel.app), [Estimeter](https://estimeter.vercel.app)

Sector sites:

- [Coffee](https://coffee-industry-amber.vercel.app), [chocolate/cocoa](https://chocolate-cocoa.vercel.app), [olive oil](https://olive-oil-six.vercel.app), [book publishing](https://book-publishing-eosin.vercel.app), [space](https://space-industry-cyan.vercel.app)
- [Semiconductors](https://semiconductors-kappa.vercel.app), [AI](https://ai-industry-delta.vercel.app), [cybersecurity](https://cybersecurity-tau-eight.vercel.app), [solar energy](https://solar-energy-theta.vercel.app), [electric vehicles](https://electric-vehicles.vercel.app)
- [Maritime shipping](https://maritime-shipping-seven.vercel.app), [aviation](https://aviation-sable.vercel.app), [global tourism](https://global-tourism-nu.vercel.app), [gaming/esports](https://gaming-esports.vercel.app), [music](https://music-industry-theta.vercel.app)
- [Film/box office](https://film-box-office.vercel.app), [digital payments](https://digital-payments-eight.vercel.app), [vertical farming](https://vertical-farming-one.vercel.app), [Swiss watches](https://swiss-watches-beryl.vercel.app), [pet care](https://pet-care-six-ashy.vercel.app)

## Intelligence, evaluation, and research systems

### Sentinel - live private intelligence pipeline

Python, Deno, Supabase/PostgreSQL, FastAPI, SQLAlchemy, Redis, Telegram.

A Türkiye-focused market/news intelligence system with RSS/KAP ingestion, deterministic scoring, deduplication, symbol extraction, explainable materiality/history, owner journaling, and a fail-closed near-threshold model judge. The later cloud pipeline records 356/356 Deno tests and authorization-first boot probes. It is not financial advice and has no published investment-performance claim.

### BIST event-study harness

A causal/no-lookahead research harness with timestamp-aware event construction, chronological train/test splits, embargoes, transaction costs, survivorship and ticker-rename guards, Wilson lower bounds, frozen rules, and an append-only test budget. It rejected an apparently strong prior after corrected data and robustness checks.

### Crypto backtest harness

A frozen train/test research protocol with matched baselines, cost modeling, limited test-set looks, and append-only evidence. No profitable-production claim is made.

### XAUUSD execution research - private interview case only

A substantial local research/execution system with deterministic risk controls and cost-first backtests. It is untracked and its documents contain broker/account identifiers, so it will not be uploaded or linked until sanitized and independently rerun.

### NASDAQ research - documentation only

Research/protocol documents without a finished implementation. It is not represented as working software.

## Media and automation systems

- **ArgeDijital Video Studio** - Remotion/FFmpeg pipeline using measured audio timing, locally burned Turkish text, transcription checks, loudness and colorspace QA.
- **Video Engine v2** - audio-driven storyboards, karaoke captions, and loudness mastering.
- **Content Machine / faceless newsroom** - a mixed-status set of newsroom, Postiz, video, and clipping workflows; some components are branch-stranded or awaiting owner account/VPS setup, so it is not called a current 24/7 production service.
- **Whisper clip pipeline** - speech/transcription-driven clip extraction; eighty Turkish streamer clips were produced in the recorded run.
- **AZS Reel and ad-factory work** - creative/media infrastructure and active implementation, not standalone shipped products.

## How the work is owned

The repositories are heavily AI-assisted. The truthful ownership claim is not that every line was typed manually. It is that Yousif defines the architecture and invariants, scopes agent work, integrates the results, runs the systems, diagnoses failures, designs discriminating tests, and decides what is allowed to ship. Model suggestions remain behind typed contracts, deterministic engines, and explicit human acceptance where consequences matter.

Representative proof:

- Revert an important guard and require its test to fail before restoring it.
- Drive the packaged application, not only the unit suite; this exposed duplicate audit writes that a large green suite missed.
