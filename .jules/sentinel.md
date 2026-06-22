## 2026-06-22 - [Security Baseline Restoration]
**Vulnerability:** Automated secret scanning (Gitleaks) and registry token exclusions (.npmrc, .yarnrc) were missing from the repository, representing a regression of the security baseline.
**Learning:** Security controls must be consistently enforced across all development paths to prevent accidental exposure of sensitive data as the project evolves.
**Prevention:** Re-implementing the Gitleaks workflow with specific SHAs and environment variables (FORCE_JAVASCRIPT_ACTIONS_TO_NODE24) ensures robust scanning, while explicit .gitignore entries prevent local registry configuration leakage.
