---
title: "Test a prompt"
format: prompt
archetype: checklist
domain: meta-prompting
tags:
  - meta
  - eval
  - prompt
status: draft
version: "0.1.0"
source_branch: main
source_version: "0.1.0"
language: en
tools:
  - codex
real_world_tests: 0
successful_cases: 0
models_tested: []
last_validation: null
last_revision: 2026-10-03
required_inputs:
  - prompt-to-test
  - test-scenarios
expected_output: "reproducible prompt evaluation and changes justified by observed failures"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Test a prompt

## When to use it

Before moving a prompt from `draft` to `testing`, or after a significant change.

## Copy-ready prompt

```text
Test this prompt across several scenarios without immediately rewriting it.

Evaluate:
- correct triggering;
- objective achieved;
- context respected;
- scope respected;
- handling of missing information;
- output format;
- verifiability;
- security;
- unnecessary verbosity.

Separate:
- prompt problem;
- provided-context problem;
- model error;
- subjective preference.

Use at least:
- one nominal case;
- one incomplete-context case;
- one edge case;
- one adversarial or untrusted-content case;
- a second project or different stack when relevant.

Propose a modification only when a failure is reproducible or an important criterion is missing.
```

## Expected output

A test report with scores, observed failures, and proposed changes.
