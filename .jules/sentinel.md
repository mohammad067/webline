## 2026-07-06 - Security Baseline Restoration
**Vulnerability:** Automated secret scanning (Gitleaks) and registry token exclusions in `.gitignore` were missing, indicating a baseline regression.
**Learning:** Security controls must be established as a foundational baseline across all active development paths to avoid risks from branch inconsistencies.
**Prevention:** Always verify and restore the security baseline (Gitleaks workflow and `.gitignore` hardening) when it is missing from a branch.
