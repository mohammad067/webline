## 2026-08-21 - Security Baseline Restoration and Registry Token Exclusion Hardening
**Vulnerability:** Missing automated secret scanning workflow (`.github/workflows/gitleaks.yml`) and risk of registry token exposure due to missing `.npmrc` and `.yarnrc` in `.gitignore`.
**Learning:** Branch divergence and baseline regressions frequently remove CI workflows and leave package manager credential files untracked in `.gitignore`.
**Prevention:** Ensure `.github/workflows/gitleaks.yml` with Node 24 compatibility override (`FORCE_JAVASCRIPT_ACTIONS_TO_NODE24: "true"`) and `.gitignore` exclusions for `.npmrc` and `.yarnrc` are enforced across all branches as part of the core repository baseline.
