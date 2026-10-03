---
title: "Feature security review"
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

# Feature security review

## When to use it

Before implementation or merge.

## Copy-ready prompt

```text
Perform a targeted security review of the provided feature and diff.

Analyze only the surfaces actually touched.
When relevant, verify:
authentication, authorization, validation, injections, SSRF, sensitive data, tenant isolation, uploads, webhooks, secrets, dependencies, logs, rate limiting, and admin functions.

For each finding:
- severity;
- status: confirmed / probable / to verify;
- evidence;
- exploitation preconditions;
- abuse scenario;
- impact;
- minimal mitigation;
- security test or verification method.

Do not request or display any real secret.
Do not create a theoretical vulnerability without a plausible exploitation path.

If a fix involves an external, destructive, or sensitive action, flag it before execution and request approval.
```

## Expected output

A targeted security analysis with verification.
