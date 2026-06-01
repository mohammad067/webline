## 2026-06-01 - Establishing Security Baseline Consistency
**Vulnerability:** Potential for secret exposure when security controls like Gitleaks are missing from development branches, and potential for CI failure due to runner compatibility issues.
**Learning:** Security controls (Gitleaks, CODEOWNERS, etc.) must be established as a foundational baseline across all active development paths, as inconsistencies between branches can create security risks during development and cause CI failures if infrastructure requirements (like Node.js version overrides) are not maintained.
**Prevention:** Always verify that security baseline components (like secret scanning with appropriate runner configuration) are present when starting work in a new branch or repository.
