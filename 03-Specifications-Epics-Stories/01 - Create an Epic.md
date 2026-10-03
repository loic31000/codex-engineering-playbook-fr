---
title: "Create an Epic"
format: prompt
archetype: template
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
expected_output: "coherent Epic that can be split into Stories"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Create an Epic

## When to use it

When an initiative is larger than a single Story.

## Copy-ready prompt

```text
Transform this need into a structured Epic.

Include:
- business objective;
- expected outcome;
- affected users;
- scope;
- out of scope;
- success criteria;
- dependencies;
- risks;
- architecture/data/security/UX impact;
- candidate Stories.

Do not detail the technical implementation yet.
Each candidate Story must represent value or a verifiable outcome.

Output: a coherent Epic that can be split into Stories.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A coherent Epic that can be split into Stories.
