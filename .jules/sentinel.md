## 2026-05-30 - Gitleaks Runner Compatibility and Baseline Consistency
**Vulnerability:** Gitleaks action may fail with 502 errors on default Node 20 runners or miss secrets if not established across all branches.
**Learning:** In this environment, the `FORCE_JAVASCRIPT_ACTIONS_TO_NODE24: true` environment variable is required for Gitleaks to run successfully. Furthermore, security controls must be part of a foundational baseline across all active development paths to ensure consistent protection.
**Prevention:** Always include the Node 24 override in Gitleaks workflows and verify that security baseline components (like secret scanning) are present when starting work in a new branch or repository.
