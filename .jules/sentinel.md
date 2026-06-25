## 2026-06-24 - Security Baseline Restoration and Hardening
**Vulnerability:** Security baseline regression (missing Gitleaks scanning) and risk of registry token exposure.
**Learning:** Security controls must be established as a foundational baseline across all active development paths. HARDENED .gitignore prevents accidental leakage of registry tokens (.npmrc, .yarnrc).
**Prevention:** Always verify the presence of the security baseline and ensure registry configuration files are ignored.
