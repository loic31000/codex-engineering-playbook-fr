---
title: "Write an ADR"
format: prompt
archetype: template
domain: architecture
tags:
  - architecture
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
expected_output: "structured architecture analysis or decision"
risk_level: medium
external_actions: false
sensitive_data: do_not_provide
---

# Write an ADR

## When to use it

When an important technical decision must remain traceable.

## Copy-ready prompt

```text
Write an ADR for this decision.

Structure:
- title;
- status;
- context;
- forces/constraints;
- options considered;
- decision;
- rationale;
- positive consequences;
- negative consequences/trade-offs;
- security/data impact;
- possible migration;
- verification;
- reevaluation criteria.

Stay factual. Do not present a preference as a constraint.

Output: a structured architecture analysis or decision.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A structured architecture analysis or decision.
