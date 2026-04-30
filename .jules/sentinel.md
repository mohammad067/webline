## 2026-04-30 - [Inconsistent Security Baseline Across Branches]
**Vulnerability:** Security policies, automated scanning (Gitleaks), and governance (CODEOWNERS) were present in some project branches but missing in the current active branch, creating a security gap during development.
**Learning:** Security controls must be established as a foundational baseline across all active development paths, not just the main branch, to ensure continuous protection and compliance.
**Prevention:** Verify and enforce the presence of the security baseline (Gitleaks, CODEOWNERS, SECURITY.md) whenever starting work on a new branch or state of the codebase.
