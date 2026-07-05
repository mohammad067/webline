## 2026-07-05 - Security Baseline Restoration and Hardening
**Vulnerability:** Recurring baseline regression where the Gitleaks secret-scanning workflow was missing and registry configuration files (.npmrc, .yarnrc) were not explicitly ignored.
**Learning:** Security controls must be consistently enforced across all branches as foundational elements; their absence in new or existing branches creates a gap in automated secret scanning and risk of accidental token exposure.
**Prevention:** Re-implemented the Gitleaks workflow with specific Node.js 24 compatibility and hardened .gitignore with registry token exclusions.
