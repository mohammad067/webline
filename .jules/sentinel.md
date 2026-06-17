## 2026-06-17 - Security Baseline Regression
**Vulnerability:** Absence of automated secret scanning and potential exposure of registry tokens in the current branch.
**Learning:** Security controls must be established as a foundational baseline across all active development paths to avoid risks from branch inconsistencies.
**Prevention:** Implement automated secret scanning (Gitleaks) and hardened .gitignore rules as a foundational step for every repository and ensure these controls are consistent across branches.
