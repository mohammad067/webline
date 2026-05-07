## 2026-05-07 - Inconsistent Security Baseline Across Branches
**Vulnerability:** Security controls (Gitleaks, CODEOWNERS, security policy) were missing in the active development branch despite being present in other branches.
**Learning:** Security infrastructure must be established as a foundational baseline early and synced across all branches to prevent security gaps during development.
**Prevention:** Implement security baseline (linting, secret scanning, governance) as the first step in project initialization and ensure it is inherited by all feature branches.
