## 2026-06-09 - [Baseline Consistency]
**Vulnerability:** Security baseline regressions due to branch inconsistencies.
**Learning:** Security controls like Gitleaks scanning and hardened `.gitignore` rules must be established as a foundational baseline across all active development paths to avoid risks from branch inconsistencies.
**Prevention:** Ensure that every branch includes the project's core security configurations and automate their presence through CI/CD where possible.
