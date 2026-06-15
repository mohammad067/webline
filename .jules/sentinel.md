## 2026-06-14 - Security Baseline Regression and Hardening
**Vulnerability:** Security baseline regression (absence of Gitleaks secret scanning) and potential registry token leakage.
**Learning:** Security controls and leakage prevention measures must be consistently maintained as a foundational baseline across all active development paths to avoid risks from branch inconsistencies.
**Prevention:** Ensure all new branches inherit and maintain the established security baseline, including automated secret scanning workflows and hardened .gitignore configurations.
