# Prompt anti-patterns

Avoid:

## The permanent mega-prompt
Too many rules loaded for every task.

## The "do everything" prompt
Analysis + architecture + code + tests + review in a single turn.

## Micromanaged reasoning
"Think step 1, then step 2, then think some more..."

Prefer:
- objective;
- context;
- constraints;
- output;
- verification.

## Vague terms
"clean", "intuitive", "performant", "secure".

Turn them into observable criteria.

## Implicit authority
Do not let Codex turn a recommendation into a project decision.

## "Make the tests pass"
Without stating that tests must not be weakened or removed.

## No stop condition
An important missing decision must be able to block the affected task.
