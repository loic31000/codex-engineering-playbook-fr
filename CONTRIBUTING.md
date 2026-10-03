# Contributing to the library

This library should remain simple, readable in Obsidian, and directly usable with Codex.

## Before adding a prompt

Check that it does not duplicate an existing prompt.

Ask yourself three questions:

1. What recurring problem does this prompt solve?
2. At what point in the workflow should it be used?
3. What observable result shows that it works?

## Recommended format

```markdown
---
title: "Prompt title"
format: prompt
archetype: instruction
status: draft
version: "0.2.0"
language: en
tools:
  - codex
real_world_tests: 0
tags:
  - domain
---

# Title

## When to use it

...

## Copy-ready prompt

```text
...
```

## Expected output

...

## Control points

- [ ] ...
```

## Archetypes

Recommended values:

```text
instruction
workflow
checklist
template
```

## Statuses

```text
draft
testing
stable
deprecated
```

### From `draft` to `testing`

The prompt is used on a real project.

Update its real-world test metadata and record the run in the test log.

### From `testing` to `stable`

Recommended criteria:

- at least 3 real-world uses;
- satisfactory results across multiple contexts;
- no known major ambiguity;
- no known tendency to silently expand scope;
- sufficiently stable expected output;
- documented limitations when needed.

The version can then move to:

```yaml
version: "1.0.0"
status: stable
```

### `deprecated`

Do not immediately delete a prompt that has been widely used.

Set:

```yaml
status: deprecated
```

and identify the replacement prompt.

## Prompt versioning

Lightweight convention:

- `0.x.y`: still experimental;
- `1.0.0`: first stable version;
- minor change: improvement without a deep change in intent;
- major change: workflow or output contract significantly changed.

## Naming convention

Inside categories:

```text
NN - Explicit name.md
```

Examples:

```text
01 - Frontend architecture.md
08 - WCAG accessibility.md
15 - Visual QA.md
```

The filename should explain the need without opening the file.

## Prompt quality

Before contributing, verify:

- one objective;
- sufficient context;
- explicit scope;
- no contradictory instruction;
- no artificial micromanagement of reasoning;
- clear expected output;
- verification criteria;
- escalation condition when a decision is missing;
- no secret data required.

Use [[15-Meta-Prompting/07 - Evaluate prompt quality]] for a self-review.

## New domain

Create a new folder only if several prompts genuinely justify a new category.

Avoid categories containing a single file.

## Suggested commits

Simple examples:

```text
prompt(frontend): add design system review
prompt(security): improve threat modeling
docs: expand conventions
meta: improve prompt template
```

No commit convention is mandatory for solo work; readability comes first.

## V0.2 contract for a new prompt

A new prompt must:

- use `format: prompt` and an `archetype` among `instruction`, `workflow`, `checklist`, `template`;
- declare useful inputs and expected output;
- place the output contract inside the copyable block;
- define a stop condition only when ambiguity can materially change the result;
- avoid massive context and over-guidance;
- distinguish facts, assumptions, and information to clarify;
- never request a real secret;
- flag any external, destructive, irreversible, or sensitive action before execution.

Before promotion to `stable`, document at least three real-world uses and, when possible, the five case families from the test log.
