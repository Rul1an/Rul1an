# Rul1an

I build Assay: evidence receipts and CI review artifacts for agent systems.

My work sits on one boundary:

> what was observed, what artifact proves it, and what claim it does not make.

Right now I am focused on agent-runtime evidence: MCP tool calls, policy
decisions, eval outputs, runtime decisions, and model-inventory artifacts that
can survive code review without becoming broad trust scores.

## Start Here

- [`assay`](https://github.com/Rul1an/assay) - Rust CLI for evidence bundles,
  receipts, Trust Basis claims, and reviewable CI artifacts.
- [`Evidence Receipts in Action`](https://github.com/Rul1an/assay/discussions/1235)
  - the short proof-oriented walkthrough for the current three receipt families.
- [`assay-action`](https://github.com/Rul1an/assay-action) - GitHub Action for
  verifying Assay evidence artifacts and publishing PR-native reports.
- [`Assay-Harness`](https://github.com/Rul1an/Assay-Harness) - approval-aware
  recipes and gates over Assay receipts.

## Current Threads

I contribute upstream design feedback where agent systems need clearer evidence
boundaries:

- OpenTelemetry GenAI lifecycle events: durable pause, checkpoint, and resume
  correlation for long-running agents.
- MCP and gateway audit trails: separating transport success from tool outcome.
- Tool audit hooks: small JSONL surfaces first, signing and receipts as optional
  adapters.
- Evidence bundle design: references and digests over payload stores.

## What I Care About

- bounded artifacts over broad claims
- explicit redaction and omission states
- reviewable diffs instead of scalar trust scores
- CI-native proof surfaces that downstream tools can consume
- standards and OSS work that keeps "observed" separate from "true"
