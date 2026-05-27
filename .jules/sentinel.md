## 2026-05-27 - [Gitleaks Node 24 Compatibility]
**Vulnerability:** Accidental exposure of secrets in git history.
**Learning:** Running Gitleaks on default GitHub Action runners sometimes encounters 502 errors during action installation. In this repository, using Node 24 for the Gitleaks action execution is required for stability.
**Prevention:** Explicitly set `FORCE_JAVASCRIPT_ACTIONS_TO_NODE24: true` in the Gitleaks workflow environment.
