## 2026-06-24 - Gitleaks Workflow Restoration
**Vulnerability:** Security baseline regression where automated secret scanning was missing.
**Learning:** Security controls like Gitleaks must be established as a foundational baseline across all active development paths to avoid risks from branch inconsistencies.
**Prevention:** Always verify the presence of the security baseline (Gitleaks workflow, hardened .gitignore) when starting work in a new branch or environment.
