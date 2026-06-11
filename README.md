# Hi, I'm Rul1an 👋

I build **[Assay](https://github.com/Rul1an/assay)**: evidence receipts and CI
review artifacts for agent systems. My work sits on one boundary: what was
observed, what artifact proves it, and what claim it deliberately does not make.

Right now I am focused on agent-runtime evidence: MCP tool calls, policy
decisions, eval outputs, and model-inventory artifacts that survive code review
without collapsing into a broad trust score. Researcher and engineer at Ignite Group.

### Find me
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/Rul1an)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/roelschuurkes/)
[![Assay Discussions](https://img.shields.io/badge/Assay-Discussions-2088FF?logo=github&logoColor=white)](https://github.com/Rul1an/assay/discussions)

## Projects

### Agent runtime evidence

| Project | Description |
|---|---|
| [assay](https://github.com/Rul1an/assay) | Rust CLI: MCP policy enforcement, evidence receipts, Trust Basis claims, coverage-aware side-effect verification, and reviewable CI artifacts. |
| [assay-action](https://github.com/Rul1an/assay-action) | GitHub Action: verify Assay bundles, publish PR-native summaries, SARIF, and downloadable reports. |
| [Assay-Harness](https://github.com/Rul1an/Assay-Harness) | Approval-aware recipes, gates, and reports over Assay receipts. |
| [plimsoll-action](https://github.com/Rul1an/plimsoll-action) | Review what an agent release changed at runtime (files, network, MCP tools), gate the PR, and report findings in code scanning. |

### AI and developer tooling

| Project | Description |
|---|---|
| [llm-cost](https://github.com/Rul1an/llm-cost) | Static cost analysis for LLM workloads. Offline-first, single binary. |
| [zig-cross-compile-action](https://github.com/Rul1an/zig-cross-compile-action) | Zig-based cross compilation for C, C++, Rust, and Go. No Docker. |

## Upstream threads

I contribute design feedback upstream where agent systems need clearer evidence
boundaries:

- MCP tool-call attestation: keeping the request-attestation boundary separate
  from execution receipts, and pinning canonicalization so test vectors stay
  reproducible across implementations.
- OpenTelemetry GenAI: guardrail and security-finding conventions, and lifecycle
  events for long-running agents.
- Gateways and audit trails: separating transport success from tool outcome, and
  treating arguments as digests or projections rather than default payloads.

## What I care about

- bounded artifacts over broad claims
- explicit redaction and omission states
- reviewable diffs instead of scalar trust scores
- CI-native proof surfaces that downstream tools can consume
- standards and OSS work that keeps "observed" separate from "true"

## Stats

[![Rul1an's GitHub stats](https://github-readme-stats.vercel.app/api?username=Rul1an&show_icons=true&hide_border=true)](https://github.com/anuraghazra/github-readme-stats)
