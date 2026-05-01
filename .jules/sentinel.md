## 2026-05-01 - Security Governance and Credential Protection
**Vulnerability:** Lack of mandatory security reviews and potential exposure of registry tokens.
**Learning:** Foundational security requires not just a disclosure policy, but also enforcement mechanisms (CODEOWNERS) and proactive prevention of common credential leaks (.npmrc).
**Prevention:** Always include registry config files in .gitignore and establish CODEOWNERS for security-sensitive paths.
