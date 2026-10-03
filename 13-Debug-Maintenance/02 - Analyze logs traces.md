---
title: "Analyze logs and traces"
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

# Analyze logs and traces

## When to use it

For an incident or distributed error.

## Copy-ready prompt

```text
Analyze these logs/traces as an investigator.

Build:
- timeline;
- request/job correlation;
- first abnormal signal;
- secondary errors;
- possible failing dependency;
- observability gaps;
- hypotheses;
- next verification steps.

Do not confuse the last visible error with the root cause.

Output: an evidence-based diagnosis or maintenance plan.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

An evidence-based diagnosis or maintenance plan.
