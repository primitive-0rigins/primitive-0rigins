# Primitive Origin LLC

Self-taught builder focused on local-first AI systems, Rust infrastructure, and practical tools.

This profile is a portfolio of systems work: original project ideas, scoped MVPs,
working demos, tests, and clear boundaries between implemented behavior and roadmap work.

## Focus

- Local-first AI memory, retrieval, and automation systems
- Rust networking and infrastructure prototypes
- Small codebases with reproducible demos
- Architecture that can be explained, tested, and inspected
- Domain-aware tools where real workflows shape the software

## Featured Work

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

I use AI tools heavily as part of the build process, but the emphasis here is direction:
choosing the system shape, constraining scope, checking claims against working code, and
turning ideas into reproducible artifacts.
