---
title: "Diagnose a bug"
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

# Diagnose a bug

## When to use it

When the symptom is known but the cause is not.

## Copy-ready prompt

```text
Diagnose this bug before proposing a fix.

Procedure:
1. restate the symptom;
2. clarify expected vs actual behavior;
3. identify reproduction conditions;
4. locate the boundaries involved;
5. formulate several hypotheses;
6. look for evidence that confirms or rejects each hypothesis;
7. identify the most likely root cause;
8. propose the regression test;
9. only then propose the minimal fix.

Do not change several things at once.

Output: an evidence-based diagnosis or maintenance plan.
```

## Expected output

An evidence-based diagnosis or maintenance plan.
