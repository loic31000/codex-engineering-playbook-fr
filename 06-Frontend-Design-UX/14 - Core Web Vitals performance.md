---
title: "Optimize Core Web Vitals"
format: prompt
archetype: instruction
domain: frontend-design-ux
tags:
  - frontend
  - design
  - ux
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
expected_output: "directly actionable frontend/design recommendation"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Optimize Core Web Vitals

## When to use it

When a web app must remain fast.

## Copy-ready prompt

```text
Analyze this page from the perspective of user-perceived performance.

Target Core Web Vitals:
- LCP;
- INP;
- CLS.

Analyze:
- JavaScript weight;
- code splitting;
- hydration;
- server/client rendering;
- images/fonts;
- critical CSS;
- requests;
- caching;
- third-party code;
- long tasks;
- handlers;
- layout shifts;
- lazy loading;
- preloading.

Classify:
- likely causes;
- measurements to collect;
- high-value optimizations;
- premature optimizations to avoid.

Do not claim a performance issue is solved without measurement.

Output: a directly actionable frontend/design recommendation.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A directly actionable frontend/design recommendation.
