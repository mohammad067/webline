## 2026-05-20 - Establishing Security Baseline and Governance
**Vulnerability:** Absence of automated secret scanning, access controls for security-critical files, and clear vulnerability disclosure policy in the current branch.
**Learning:** Security controls (Gitleaks, CODEOWNERS, etc.) must be established as a foundational baseline early in a project's lifecycle. Inconsistencies or lack of these controls across development paths can lead to accidental exposure of credentials and unreviewed changes to security configurations.
**Prevention:** Implement automated secret scanning (Gitleaks) and mandatory code reviews (CODEOWNERS) for security-sensitive files as part of the initial repository setup.
