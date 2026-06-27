## 2026-06-24 - Security baseline restoration
**Vulnerability:** Security baseline regression where automated secret scanning (Gitleaks) and registry token exclusions in `.gitignore` were missing.
**Learning:** Security controls must be established as a foundational baseline across all active development paths to avoid risks from branch inconsistencies.
**Prevention:** Re-implemented `.github/workflows/gitleaks.yml` with pinned SHAs and hardened `.gitignore` with `.npmrc` and `.yarnrc` exclusions.
