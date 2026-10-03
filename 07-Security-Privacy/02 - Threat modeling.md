---
title: "Threat modeling"
format: prompt
archetype: checklist
domain: security-privacy
tags:
  - security
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
expected_output: "targeted security analysis with verification"
risk_level: high
external_actions: false
sensitive_data: do_not_provide
---

# Threat modeling

## When to use it

For a sensitive architecture or feature.

## Copy-ready prompt

```text
Build a pragmatic threat model.

Identify:
- assets;
- actors;
- trust boundaries;
- entry points;
- data flows;
- external dependencies;
- threats;
- abuse cases;
- mitigations;
- verification;
- residual risks.

Prioritize plausible scenarios.
Do not generate a generic checklist disconnected from the architecture.

Output: targeted security analysis with verification.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A targeted security analysis with verification.
