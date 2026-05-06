# Rul1an

Researcher, engineer, developer, and AI consultant working at Ignite Group.

I build Assay: CI-native evidence tooling for agent systems.

Assay turns observed test-run behavior into bounded, reviewable artifacts:
tool calls, filesystem and network access, policy decisions, eval receipts,
and other small claims that can survive code review.

I care about precise boundaries:
what was observed, where it came from, what the artifact proves,
and what it explicitly does not prove.

Current focus:

- Rust CLI tooling for evidence receipts
- GitHub Actions for PR-native review surfaces
- MCP and agent capability boundaries
- Python/TypeScript harnesses
- eBPF/Landlock-shaped runtime constraints

Start here:

- [`assay`](https://github.com/Rul1an/assay) — Rust CLI and receipt model
- [`assay-action`](https://github.com/Rul1an/assay-action) — GitHub Action for reviewable evidence artifacts
- [`Assay-Harness`](https://github.com/Rul1an/Assay-Harness) — recipes and gates over Assay receipts
