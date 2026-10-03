---
title: "Design webhooks and integrations"
format: prompt
archetype: instruction
domain: data-api
tags:
  - data
  - api
status: draft
version: "0.2.0"
source_branch: main
source_version: "0.2.0"
language: en
tools:
  - codex
real_world_tests: 0
successful_cases: 0
models_tested: []
last_validation: null
last_revision: 2026-10-03
required_inputs:
  - provided-context
expected_output: "explicit and verifiable data/API design"
risk_level: medium
external_actions: false
sensitive_data: do_not_provide
---

# Design webhooks and integrations

## When to use it

When integrating external systems robustly.

## Copy-ready prompt

```text
Analyze this external integration.

Define:
- inbound/outbound contract;
- authentication/signature;
- idempotency;
- retries;
- timeout;
- event ordering;
- replay;
- deduplication;
- rate limits;
- errors;
- minimum required storage;
- observability;
- secret management;
- degraded mode.

List assumptions that depend on the provider.

Output: explicit and verifiable data/API design.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

An explicit and verifiable data/API design.
