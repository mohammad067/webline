## 2026-06-28 - Security Baseline Restoration
**Vulnerability:** Automated secret scanning (Gitleaks) and registry token exclusions (.npmrc, .yarnrc) were missing from the current branch, representing a regression of the established security baseline.
**Learning:** Security controls must be established as a foundational baseline across all active development paths to avoid risks from branch inconsistencies.
**Prevention:** Always verify and restore the security baseline (Gitleaks workflow and hardened .gitignore) when entering a new branch or environment.
