# Security Policy

## Supported Versions

Only the latest released version of OpenBlue receives security fixes.

| Version | Supported |
| :-- | :-: |
| 0.1.x | ✅ |
| < 0.1.0 | ❌ |

## Reporting a Vulnerability

If you believe you have found a security vulnerability in OpenBlue,
**please do not open a public GitHub issue**. Instead, report it privately:

- **Email:** antonfernperez@gmail.com
- **Subject line:** `[OpenBlue Security] <short description>`

Please include:

- The version of OpenBlue affected
- A description of the vulnerability
- Steps to reproduce
- Any proof-of-concept code (if applicable)
- Your assessment of severity

We will acknowledge your report within 5 business days and aim to release
a fix within 30 days for high-severity issues.

## Scope

In scope:

- The OpenBlue extension itself (configuration handling, file writes,
  inter-process communication)
- The packaged `.vsix` distributed in this repository

Out of scope (please report to the respective vendors):

- Vulnerabilities in LM Studio, Ollama, Claude Code, VS Code, or any
  third-party model
- Vulnerabilities in models you load yourself
