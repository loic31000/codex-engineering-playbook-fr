---
title: "Diagnose performance"
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

# Diagnose performance

## When to use it

Before any optimization.

## Copy-ready prompt

```text
Using the symptoms and measurements, build a profiling plan.

Separate:
- CPU;
- memory;
- I/O;
- DB;
- network;
- frontend;
- external dependencies.

For each hypothesis, define:
- metric;
- tool/observation;
- comparison threshold;
- experiment.

Do not optimize before identifying the bottleneck.

Output: an evidence-based diagnosis or maintenance plan.
```

## Expected output

An evidence-based diagnosis or maintenance plan.
