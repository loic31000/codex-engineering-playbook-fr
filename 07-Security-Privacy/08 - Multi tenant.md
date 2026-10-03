---
title: "Multi-tenant isolation review"
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

# Multi-tenant isolation review

## When to use it

For a multi-tenant SaaS.

## Copy-ready prompt

```text
Analyze multi-tenant isolation end to end.

Verify:
- tenant context;
- DB queries;
- caches;
- async jobs;
- files;
- search;
- logs;
- API;
- admin;
- exports;
- webhooks;
- analytics;
- tests.

Look for possible cross-tenant access.
Propose dedicated isolation tests.

Output: targeted security analysis with verification.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A targeted security analysis with verification.
