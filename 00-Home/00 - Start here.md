# Start here

This library is designed as a **personal Obsidian vault of prompts and workflows** for working with Codex.

It contains:

- no scripts;
- no automation;
- no configuration files;
- no executable code.

It contains only Markdown `.md` files.

## How to use it

For an important task, avoid one prompt that tries to do everything.

Use this cycle instead:

```text
1. Clarify
2. Specify
3. Plan
4. Implement
5. Test
6. Review
7. Converge
8. Prepare the PR
```

For frontend work:

```text
1. UX / user flow
2. Visual direction
3. Design system / tokens
4. Screen structure
5. Component architecture
6. Responsive
7. Accessibility
8. Performance
9. Visual QA
```

## Important rules

- Do not ask Codex to invent an unknown business decision.
- Use the states: `confirmed`, `assumption`, `undecided`, `N/A`.
- For a large task, ask for a plan first.
- An implementation is not complete until acceptance criteria and relevant tests pass.
- Architecture, security, persistence, or public contract changes must be made explicit.
- Financial costs do not belong in User Stories.

See also:

- [[01 - Daily workflow]]
- [[02 - Reference prompt formula]]
- [[03 - Choose the right prompt]]
