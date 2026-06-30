## 2026-06-28 - Security Baseline Restoration and Hardening
**Vulnerability:** Recurring security baseline regressions where the Gitleaks automated secret scanning workflow was missing and registry configuration files (.npmrc, .yarnrc) were not explicitly excluded in .gitignore.
**Learning:** Security controls must be established as a foundational baseline across all active development paths to mitigate risks from branch inconsistencies and accidental credential exposure.
**Prevention:** Ensure the .github/workflows directory and gitleaks.yml are present in all branches and maintain a hardened .gitignore that includes registry tokens.
