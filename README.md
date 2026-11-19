# MAJEK Vibe Coding Foundation
Project-neutral standards and workflows for AI-assisted software engineering.

## Boundaries
1. Foundation Build: shared rules, workflows, templates, and tool registry.
2. Foundation Validation: disposable fixtures and synthetic data only.
3. Project Onboarding: separate future process for each project.

No project-specific code, dependencies, credentials, production data, or configuration belong here.

## Decisions
- OpenCode primary; GitHub Copilot CLI fallback, not concurrent.
- VS Code/Cursor are editors.
- `browse` MCP is the single browser baseline, pending review.
- Windows-first; use `.cmd` shims if PowerShell blocks `.ps1`.
- Defer local models and multi-agent orchestration on current hardware.
- Never modify H:, partitions, production systems, or unrelated projects without explicit approval.

Read `governance/SAFETY-POLICY.md` first. Bootstrap only; not yet validated as v1.0.
