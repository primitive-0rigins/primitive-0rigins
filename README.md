# Primitive Origin LLC

AI systems, local-first infrastructure, and compact technical prototypes.

This profile is a portfolio of systems work: original project ideas, scoped MVPs,
working demos, tests, and clear boundaries between what is implemented and what is roadmap.

## Focus

- Applied AI systems and agentic workflows
- Local-first memory, retrieval, and automation tools
- Rust networking and infrastructure prototypes
- Small codebases with reproducible demos
- Architecture that can be explained, tested, and inspected

## Featured Work

### Mosaic

Pixel-hypergraph memory for visual documents.

Mosaic renders documents into image tiles, stores tile metadata as hypergraph nodes,
retrieves visually similar tiles with local pixel-derived vectors, links evidence with
hyperedges, and exports inspectable reports and demo artifacts.

What it demonstrates:

- Visual-first retrieval architecture
- Hypergraph memory modeling
- Honest prototype boundaries around VLM and agent roadmap work
- Runnable CLI, tests, static report, and generated demo video

Repository: https://github.com/primitive-0rigins/mosaic

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

## How To Evaluate The Repos

Each portfolio project is meant to be run, not just read.

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
