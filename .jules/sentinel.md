## 2026-07-03 - [Security Baseline Restoration]
**Vulnerability:** Recurring baseline regression where the Gitleaks workflow and registry token exclusions in `.gitignore` are missing in new branches.
**Learning:** Security controls established in one branch do not automatically propagate to others if they are not part of the foundational repository template or merged into the main development line.
**Prevention:** Explicitly verify and restore the security baseline (Gitleaks workflow and `.gitignore` hardening) as the first step in any new security-focused task to ensure continuous protection.
