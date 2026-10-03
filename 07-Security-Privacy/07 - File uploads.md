---
title: "Secure file uploads"
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

# Secure file uploads

## When to use it

When users can upload files.

## Copy-ready prompt

```text
Analyze the upload flow.

Verify:
- size;
- actual type;
- extension;
- filename;
- storage;
- access;
- antivirus/sandbox when necessary;
- active content;
- image processing;
- path traversal;
- signed URLs;
- lifetime;
- quotas;
- metadata;
- multi-tenancy;
- deletion;
- logs.

Propose a strategy proportional to the risk.

Output: targeted security analysis with verification.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A targeted security analysis with verification.
