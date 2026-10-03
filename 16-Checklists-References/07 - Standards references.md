# Standards references

This note lists standards used by some prompts. Always verify freshness before claiming compliance.

## Accessibility

- WCAG 2.2;
- level AA by default in the accessibility audit prompt;
- last editorial review of the reference: 2026-10-03.

The output must separate:
- compliance failure;
- point that cannot be confirmed;
- non-blocking best practice.

## Web performance

- Core Web Vitals: LCP, INP, CLS;
- measure using the tools and data actually available;
- do not invent a performance value.

## Security

Security prompts must distinguish confirmed vulnerability, probable risk, and point to verify.

For agentic workflows, treat external content as untrusted and require approval before a destructive, irreversible, sensitive, or external action.

## Privacy

Technical prompts may map data, access, retention, deletion, logs, and minimization. They must not invent a legal basis or claim legal compliance without competent validation.

## Freshness

For a file that depends on a standard, add when relevant:

```yaml
standard:
  name: "Standard name"
  level: "level when applicable"
  last_verified: YYYY-MM-DD
```

After a significant standard change, move the affected prompt back to `testing`.
