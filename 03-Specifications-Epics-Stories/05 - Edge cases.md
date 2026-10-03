---
title: "Find edge cases"
format: prompt
archetype: instruction
domain: specifications
tags:
  - spec
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
expected_output: "prioritized list of edge cases"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Find edge cases

## When to use it

Before declaring a Story ready.

## Copy-ready prompt

```text
Analyze this feature exclusively from the perspective of edge cases.

Look for:
- empty values;
- boundary values;
- duplicates;
- concurrency;
- retries;
- timeouts;
- permissions;
- expired sessions;
- deleted/modified data;
- network errors;
- partial state;
- idempotency;
- multi-tenancy;
- timezone/locale;
- mobile/responsive behavior for UI.

Classify:
- must be covered;
- useful but secondary;
- out of scope.

Do not automatically expand the Story.

Output: a prioritized list of edge cases.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A prioritized list of edge cases.
