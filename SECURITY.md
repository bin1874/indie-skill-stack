# Security Policy

This repository indexes third-party AI agent skills. It does not guarantee that every linked skill is safe for every environment.

## Risk Labels

| Label | Meaning |
|---|---|
| Low | Text-only or local instructions. No secrets, network, shell, or file writes required. |
| Medium | Needs network access, API keys, or project-file access, with a clear reason. |
| High | Uses shell, writes files, reads sensitive data, connects to production systems, or controls third-party accounts. |
| Reject | Risk is unclear, excessive, or mismatched with the claimed use case. |

## Reporting Risk

Open an issue if an included skill:

- asks for unnecessary secrets;
- reads or sends private data without a clear warning;
- hides shell commands, network calls, or credential use;
- has changed behavior since it was reviewed;
- appears abandoned and risky to keep listed.

## Review Scope

Our review is a lightweight human review of public documentation and obvious behavior. It is not a formal security audit.

Use your own judgment before installing any skill in a real project.
