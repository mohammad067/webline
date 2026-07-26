## 2026-07-06 - Security Baseline Restoration
**Vulnerability:** Automated secret scanning (Gitleaks) and registry configuration exclusions (.npmrc, .yarnrc) were missing due to a baseline regression on the active branch.
**Learning:** Security controls must be established as a foundational baseline across all active development paths to avoid risks from branch-specific inconsistencies.
**Prevention:** Ensure the security baseline, including Gitleaks workflows and hardened .gitignore, is present in all branches and restored immediately if found missing.
