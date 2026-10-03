---
title: "Secrets and supply chain"
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

# Secrets and supply chain

## When to use it

Before merge or when adding a dependency.

## Copy-ready prompt

```text
Review this change from a secrets and supply-chain perspective.

Verify:
- no hardcoded secret;
- variables/configuration;
- logs;
- CI;
- token permissions;
- new dependency;
- reputation/maintenance;
- version;
- lockfile;
- transitive dependencies;
- vulnerabilities;
- installation scripts;
- license when relevant.

Classify issues by severity.

Output: targeted security analysis with verification.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A targeted security analysis with verification.
