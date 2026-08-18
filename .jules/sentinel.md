## 2026-08-16 - Security Baseline Restoration and Registry Token Exclusion Hardening
**Vulnerability:** Missing automated Gitleaks secret scanning workflow and unignored package manager registry token files (.npmrc, .yarnrc).
**Learning:** Development branches can suffer from baseline security control regressions if workflow definitions or token exclusions are omitted across branch divergences.
**Prevention:** Maintain automated secret scanning workflow and registry token exclusions in .gitignore as mandatory baseline security configurations.
