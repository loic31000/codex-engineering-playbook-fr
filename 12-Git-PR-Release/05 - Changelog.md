---
title: "Write changelog"
format: prompt
archetype: template
domain: git-release
tags:
  - git
  - release
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
expected_output: "ready-to-use Git/release artifact"
risk_level: high
external_actions: false
sensitive_data: do_not_provide
---

# Write changelog

## When to use it

After a release.

## Copy-ready prompt

```text
Write a changelog entry for the intended audience, whether users or developers.

Separate:
- Added;
- Changed;
- Fixed;
- Deprecated;
- Security;
- Breaking changes.

Do not mention internal details that have no value for the reader.

Output: a ready-to-use Git/release artifact.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A ready-to-use Git/release artifact.
