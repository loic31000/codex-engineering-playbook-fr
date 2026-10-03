---
title: "Write an incident postmortem"
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

# Write an incident postmortem

## When to use it

After an incident.

## Copy-ready prompt

```text
Write a blameless postmortem.

Structure:
- summary;
- impact;
- timeline;
- detection;
- response;
- root cause;
- contributing factors;
- what worked well;
- what did not work well;
- corrective actions;
- owner/priority;
- prevention measures.

Distinguish root cause from trigger.

Output: an evidence-based diagnosis or maintenance plan.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

An evidence-based diagnosis or maintenance plan.
