---
title: "Security baseline"
format: prompt
archetype: instruction
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

# Security baseline

## When to use it

At the beginning of a project.

## Copy-ready prompt

```text
Build the minimum security baseline for this project.

Evaluate:
- Internet exposure;
- authentication;
- authorization;
- personal/sensitive data;
- secrets;
- dependencies;
- uploads;
- webhooks;
- public API;
- multi-tenancy;
- admin functions;
- logs;
- CI/CD;
- backups.

For each domain:
- applicable or N/A;
- risk;
- minimum control;
- verification.

Keep controls proportional to risk.

Output: targeted security analysis with verification.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A targeted security analysis with verification.
