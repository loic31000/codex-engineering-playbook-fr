---
title: "PR review"
format: prompt
archetype: checklist
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

# PR review

## When to use it

When reviewing an entire PR.

## Copy-ready prompt

```text
Analyze this PR as a whole, not only file by file.

Evaluate:
- consistency with the Story;
- size/focus;
- architecture;
- security;
- data;
- tests;
- documentation;
- migration;
- backward compatibility;
- rollout;
- observability.

Report blockers first.

Output: a ready-to-use Git/release artifact.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A ready-to-use Git/release artifact.
