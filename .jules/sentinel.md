## 2026-06-28 - Security baseline restoration and .gitignore hardening
**Vulnerability:** Security baseline regression; missing automated secret scanning (Gitleaks) and inadequate .gitignore exclusions for registry tokens (.npmrc, .yarnrc).
**Learning:** Security controls must be established as a foundational baseline across all active development paths. Their absence in a branch or the main development path poses a risk of accidental sensitive data exposure.
**Prevention:** Re-implement the Gitleaks workflow in .github/workflows/gitleaks.yml and ensure .gitignore always excludes registry configuration files.
