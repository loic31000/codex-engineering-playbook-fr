---
title: "Diagnose a flaky test"
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

# Diagnose a flaky test

## When to use it

When a test passes and fails intermittently.

## Copy-ready prompt

```text
Analyze this flaky test.

Look for:
- timing;
- order;
- shared state;
- concurrency;
- network;
- randomness;
- timezone;
- resources;
- race condition;
- cleanup;
- DB isolation;
- asynchronous assertions.

First propose how to reproduce or amplify the problem, then propose the fix.

Output: an evidence-based diagnosis or maintenance plan.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

An evidence-based diagnosis or maintenance plan.
