# Prompt lifecycle

Each prompt evolves progressively.

```text
draft
  ↓
testing
  ↓
stable
  ↓
deprecated
```

## draft

An idea structured enough to be tried.

```yaml
status: draft
real_world_tests: 0
successful_cases: 0
last_validation: null
```

## testing

The prompt is used on real projects. Document at least:

- nominal case;
- incomplete context;
- edge case;
- adversarial case or untrusted content;
- a second project or different stack when relevant.

During this phase, record ambiguity, scope creep, ignored constraints, unstable format, unnecessary verbosity, and excessive dependence on one stack.

## stable

A prompt can become stable when it has been sufficiently proven:

- at least 3 real-world uses;
- if possible, at least 2 contexts or projects;
- no known critical failure;
- sufficiently reproducible output;
- incomplete and edge cases tested;
- limitations understood.

```yaml
status: stable
version: "1.0.0"
real_world_tests: 3
last_validation: YYYY-MM-DD
```

## Revalidation

`stable` is not permanent. Move a prompt back to `testing` after:

- a major model change;
- a standard or specification change;
- an observed regression;
- a significant prompt modification;
- a new context type that reveals a weakness.

## deprecated

Keep the file for history and point to its replacement:

```markdown
> Deprecated: use [[Path/New prompt]].
```

## Principle

Maturity is not related to length. A short, reliable prompt is better than a complex prompt that has never been tested in practice.
