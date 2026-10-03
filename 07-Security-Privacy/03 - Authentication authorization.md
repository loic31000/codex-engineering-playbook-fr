---
title: "Authentication and authorization review"
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

# Authentication and authorization review

## When to use it

For login, roles, permissions, and multi-tenant systems.

## Copy-ready prompt

```text
Review this authentication/authorization design.

Verify:
- identity;
- session/tokens;
- expiration;
- rotation;
- MFA;
- recovery;
- CSRF when applicable;
- token storage;
- logout;
- server-side authorization;
- object-level access;
- tenant isolation;
- deny by default;
- admin;
- audit.

Explicitly look for authorization bypass paths.

Output: targeted security analysis with verification.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A targeted security analysis with verification.
