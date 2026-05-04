## 2026-05-04 - [Node.js Version Requirement for Gitleaks Action]
**Vulnerability:** Gitleaks scan workflow may fail with 502 errors or installation issues if the runner uses a deprecated Node.js version.
**Learning:** Standard GitHub Action runners currently support Node.js 20, but explicit environment configuration can improve reliability.
**Prevention:** Use `FORCE_JAVASCRIPT_ACTIONS_TO_NODE20: true` in the Gitleaks workflow to ensure runner compatibility and execution stability.
