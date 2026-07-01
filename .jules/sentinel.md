## 2026-07-01 - Security Baseline Restoration
**Vulnerability:** Automated secret scanning (Gitleaks) and registry token exclusions (.npmrc, .yarnrc) were missing from the current branch.
**Learning:** Security controls frequently regress across different branches and environments in this repository, necessitating constant re-verification and restoration of the baseline.
**Prevention:** Ensure that the security baseline (Gitleaks workflow and hardened .gitignore) is treated as a foundational requirement for all active development paths.
