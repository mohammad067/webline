## 2026-08-16 - Re-establishing Security Baseline and Registry Token Protection

**Vulnerability:** Missing automated secret scanning workflow (`.github/workflows/gitleaks.yml`) and missing exclusions for `.npmrc` and `.yarnrc` registry credential files in `.gitignore`.
**Learning:** Security baseline configurations can recur as regressions across isolated development branches if baseline workflows and ignore rules are not consistently maintained.
**Prevention:** Always maintain `.github/workflows/gitleaks.yml` with `FORCE_JAVASCRIPT_ACTIONS_TO_NODE24: true` and explicitly ignore registry credential files (`.npmrc`, `.yarnrc`) in `.gitignore`.
