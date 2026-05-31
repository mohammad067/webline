## 2026-05-31 - Security Baseline Consistency and Gitleaks Configuration
**Vulnerability:** Potential for secret exposure when security controls like Gitleaks are missing from development branches, and potential for CI failure due to runner compatibility issues.
**Learning:** Security controls must be established as a foundational baseline across all active development paths. In this repository, the `FORCE_JAVASCRIPT_ACTIONS_TO_NODE24: true` environment variable is essential for Gitleaks to run without 502 errors.
**Prevention:** Ensure every branch includes the standard security baseline (Gitleaks, SECURITY.md, .gitignore) and explicitly configure the Node 24 environment for Gitleaks actions.
