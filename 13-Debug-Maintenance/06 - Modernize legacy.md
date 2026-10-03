---
title: "Modernize legacy code"
format: prompt
archetype: workflow
domain: debug-maintenance
tags:
  - debug
  - maintenance
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
expected_output: "evidence-based diagnosis or maintenance plan"
risk_level: high
external_actions: false
sensitive_data: do_not_provide
---

# Modernize legacy code

## When to use it

When improvement is needed without rewriting everything.

## Copy-ready prompt

```text
Propose an incremental modernization strategy.

First:
- critical behavior to preserve;
- stable areas;
- painful areas;
- existing tests;
- possible boundaries.

Then:
- strangler/increments;
- cut points;
- characterization tests;
- migrations;
- exit criteria.

Avoid a full rewrite by default.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

An evidence-based diagnosis or maintenance plan.
