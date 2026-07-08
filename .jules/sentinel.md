## 2026-07-06 - Security Baseline Restoration
**Vulnerability:** Security baseline regression; missing automated secret scanning (Gitleaks) and registry token exclusions in `.gitignore`.
**Learning:** Security controls must be established as a foundational baseline across all active development paths to avoid risks from branch inconsistencies.
**Prevention:** Always ensure `.github/workflows/gitleaks.yml` is present and `.gitignore` includes registry configuration files like `.npmrc` and `.yarnrc`.
