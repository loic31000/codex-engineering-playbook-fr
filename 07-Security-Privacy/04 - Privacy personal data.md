---
title: "Privacy and personal data"
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

# Privacy and personal data

## When to use it

When the system processes personal data.

## Copy-ready prompt

```text
Analyze the provided feature from a data-protection perspective.

Map:
- data categories;
- source;
- declared purpose;
- storage;
- people/services with access;
- transfers or sharing;
- logs and telemetry;
- retention period;
- deletion;
- export;
- backups;
- test environments.

Prioritize:
excessive collection, unnecessary data, leakage in logs, overly broad access, indefinite retention, and forgotten secondary copies.

For each issue:
- affected data;
- risk;
- proposed minimization or technical control;
- verification method.

Separate:
- confirmed fact;
- assumption;
- missing information;
- legal decision requiring validation.

Never invent a legal basis or a compliance conclusion.
```

## Expected output

A targeted security analysis with verification.
