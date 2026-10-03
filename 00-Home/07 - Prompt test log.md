# Prompt test log

Use this note to track real-world runs and compare versions.

## Recommended minimum cases

1. nominal case;
2. incomplete context;
3. edge case;
4. adversarial case or untrusted content;
5. a second project or different stack when relevant.

## Score per run

Score each axis from 0 to 2:

| Axis | 0 | 1 | 2 |
|---|---|---|---|
| Objective achieved | failed | partial | achieved |
| Context respected | poor | mixed | good |
| Scope respected | expands scope | some drift | respected |
| Quality / verifiability | weak | average | strong |
| Output format | not respected | partial | respected |
| Security / caution | insufficient | acceptable | strong |

Indicative interpretation:

- 12/12: excellent;
- 10–11: good;
- 8–9: improvement needed;
- < 8: prompt should be reworked.

## Run template

```markdown
### YYYY-MM-DD — Prompt name

Project / context:
Case type:
Model / tool:
Prompt version:
French source version:

Score:
- objective: /2
- context: /2
- scope: /2
- quality / verifiability: /2
- format: /2
- security / caution: /2
- total: /12

Result:
- good:
- bad:
- ambiguous:
- missing:

Diagnosis:
- prompt issue:
- context issue:
- model error:
- subjective preference:

Action:
- keep;
- modify;
- merge;
- deprecate.
```

## A/B comparison

When a prompt changes, compare the previous and new version with the same context and model when possible. Keep the version that improves observable criteria, not the one that merely looks more elegant.

## Tests

_No real-world test recorded yet._
