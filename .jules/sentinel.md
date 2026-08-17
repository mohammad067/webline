## 2026-08-16 - Security Baseline Restoration and `.gitignore` Hardening
**Vulnerability:** Missing automated Gitleaks secret scanning workflow and unignored package registry token files (`.npmrc`, `.yarnrc`).
**Learning:** Branch-specific regressions can drop foundational security workflows and ignore patterns, leaving commits vulnerable to secret exposure.
**Prevention:** Re-establish `.github/workflows/gitleaks.yml` with pinned Action SHAs and enforce registry token file exclusion in `.gitignore`.
