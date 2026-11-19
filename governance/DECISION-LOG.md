# Decision Log

## ADR-0001 — Project-neutral boundaries
- Status: Accepted | Date: 2026-11-19
- Foundation Build, Foundation Validation, and Project Onboarding are separate.
- No project-specific assumptions, dependencies, secrets, or production data in this repository.

## ADR-0002 — Agent baseline
- Status: Accepted | Date: 2026-11-19
- OpenCode primary; Copilot CLI fallback. Avoid concurrent agent duplication.
- Shared rules and handoff artifacts are authoritative.

## ADR-0003 — Resource constraints
- Status: Accepted | Date: 2026-11-19
- Defer local models and multi-agent orchestration on current 16 GB RAM / 6 GB VRAM.

## ADR-0004 — Windows-first
- Status: Accepted | Date: 2026-11-19
- Use `.cmd` shims where PowerShell blocks `.ps1`; do not weaken system ExecutionPolicy.
