## 2026-08-12 - Re-establishing Security Baseline and Registry Token Hardening

**Vulnerability:** The active branch lacked the `.github/workflows/gitleaks.yml` secret scanning workflow, leaving automated credential detection disabled, and `.gitignore` omitted `.npmrc` and `.yarnrc` exclusions, risking inadvertent exposure of private package registry tokens.
**Learning:** Branch-specific regressions frequently drop workflow configurations or essential ignore rules, causing security gaps across isolated branches.
**Prevention:** Always maintain automated secret scanning workflows and keep `.gitignore` hardened against registry token files across all active development branches.
