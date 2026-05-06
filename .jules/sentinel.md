## 2026-05-06 - [Repository Security Hardening]
**Vulnerability:** Lack of automated secret scanning, missing code governance for security-critical files, and potential credential leakage via registry config files.
**Learning:** Security controls (Gitleaks, CODEOWNERS, etc.) must be established as a foundational baseline across all active development paths, as inconsistencies between branches can create security gaps during development.
**Prevention:** Implement automated scanning with pinned SHAs and mandatory reviews for security infrastructure from the project's inception.
