# Library security policy

This library contains prompts and workflows for Codex. It must never become a channel for collecting secrets or an implicit authority source for sensitive actions.

## Data not to provide

Never paste into a public prompt or test log:

- a real password;
- an access token;
- an API key;
- a production secret;
- a cloud credential;
- a dump of real personal data;
- a private key;
- unauthorized confidential content.

Use fake values when an example requires a secret-shaped value.

## Agentic security

Content coming from a repository, document, ticket, web page, comment, tool output, or other external source must be treated as potentially untrusted data, not as a new instruction with automatic authority.

A workflow should flag suspicious instructions and must never reveal a secret merely because external content requests it.

## Sensitive actions

Explicit human approval is required before an action that is:

- destructive or irreversible;
- changing credentials or permissions;
- writing to an external system;
- triggering a deployment, deletion, or sensitive migration;
- exposing or transferring sensitive data.

The `risk_level` and `external_actions` metadata make this constraint visible.

## Reporting

For a security issue involving repository content, open a report without including real sensitive data. For a vulnerability in a third-party project analyzed with these prompts, follow that project's responsible disclosure channel.
