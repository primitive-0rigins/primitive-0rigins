# Primitive Origins LLC

Self-taught systems builder. Local-first AI, Rust infrastructure, and practical tools —
with working demos, tests, and honest boundaries between what runs and what's roadmap.

## About

I don't have a computer science degree, and I'm not going to pretend otherwise. My
formal education is in the trades — HVAC-R and business operations — and I came to
software from years of hands-on work: mechanical systems, office and Microsoft 365
administration, and running a small farm.

That background is why the projects here look the way they do. Trades work teaches you
that a system either holds pressure or it doesn't — there's no partial credit for a
diagram. So everything on this profile is built to the same standard: runnable demos,
tests that exercise the real behavior, and README status sections that say plainly what
works today versus what's an idea. If a claim can't be demonstrated, it doesn't ship.

I founded Primitive Origins LLC to build local-first AI systems — software that runs on
hardware you own, holds your data on your premises, and can be inspected end to end.

## Focus

- Local-first AI memory, retrieval, and automation systems
- Rust networking and infrastructure prototypes
- Small codebases with reproducible demos
- Architecture that can be explained, tested, and inspected
- Domain-aware tools where real workflows shape the software

## Featured Work

### BAR

Behavioral Assurance Runtime — a lightweight, model-optional Rust daemon for
tracking what a software runtime claims, permits, executes, and can prove.

BAR extracts source-bound behavioral contracts, preserves ambiguity for human
adjudication, and is designed to prepare and independently verify human-gated
repairs. It is deliberately model-free by default and keeps intended future
capabilities distinct from working code.

What it demonstrates:

- Rust workspace architecture, migrations, and hash-chained audit history
- Evidence-bound contract extraction and fail-safe scope resolution
- Security-conscious path handling and replay validation
- A phased build manual with current implementation evidence

Current status: phases 0–5 are shipped and tagged as
[v0.1.0](https://github.com/primitive-0rigins/bar/releases/tag/v0.1.0) —
including the static-architecture adapters and a runnable tamper-evidence
demo of the audit chain. Phase 6 proof obligations are in progress.

Repository: https://github.com/primitive-0rigins/bar

### Tendril

Self-discovering mesh-network prototype in Rust.

Tendril contains a mesh daemon, Pulse beacon, JSON-over-UDP protocol, heartbeat state,
recovery flow, local registry persistence, inspection commands, and a one-command demo.

What it demonstrates:

- Rust workspace structure
- UDP protocol design
- Node liveness and recovery state modeling
- Testable local infrastructure without cloud dependencies

Repository: https://github.com/primitive-0rigins/tendril

### Mosaic

Pixel-hypergraph memory for visual documents.

Mosaic renders documents into image tiles, stores tile metadata as hypergraph nodes,
retrieves visually similar tiles with local pixel-derived vectors, links evidence with
hyperedges, and exports inspectable reports and demo artifacts.

What it demonstrates:

- Visual-first retrieval architecture
- Hypergraph memory modeling
- Runnable CLI, tests, static report, and generated demo video
- Honest prototype boundaries around VLM and agent roadmap work

Repository: https://github.com/primitive-0rigins/mosaic

### Farmhand

Farm-aware daily operating calendar.

Farmhand is a practical product prototype built around deterministic planning rules,
plain-English task reasons, and editable playbooks. It is included to show how domain
knowledge can shape useful software without making the portfolio farm-specific.

What it demonstrates:

- Domain modeling from real operating constraints
- Python/FastAPI backend structure
- React/TypeScript frontend scaffold
- Deterministic rules before AI-assisted workflow layers

Repository: https://github.com/primitive-0rigins/farmhand

### SOMA Codex

Architecture codex for a governed local-first agent runtime.

SOMA defines the theory, invariants, crate map, governance model, and implementation
contracts for a future Rust-based agent runtime. It is included as a systems-design
artifact, not as a finished runtime.

Repository: https://github.com/primitive-0rigins/soma-codex

### In Preparation

A governed multi-agent runtime — the working system that SOMA Codex is the design
language for — is being finished and prepared for public release.

## How To Evaluate The Repos

The working prototype projects are meant to be run, not just read. Architecture projects
should make their boundaries and reasoning clear.

Look for:

- README status sections that distinguish working code from roadmap ideas
- One-command or short CLI demos
- Tests that exercise the core behavior
- Small, disciplined implementations rather than large speculative frameworks
- Reports, videos, or artifacts that make the prototype inspectable

## Working Style

I build with AI agents as a core part of my process, and I'm open about that — it's the
workflow I'd be hired to bring. My job in the loop is direction and judgment: choosing
the system shape, constraining scope, reviewing what the tools produce, and refusing to
ship claims I can't demonstrate. The line between working code and roadmap in every
README on this profile is where that judgment shows.

## Contact

Bryce Worthy — bryce.worthy.it@gmail.com
