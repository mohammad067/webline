## 2026-08-19 - Restoring Gitleaks Baseline and .gitignore Token Exclusions
**Vulnerability:** Automated secret scanning workflow (`.github/workflows/gitleaks.yml`) and package registry token exclusions (`.npmrc`, `.yarnrc` in `.gitignore`) were missing on the active branch, exposing the repo to potential secret leakage.
**Learning:** Branch-specific security regressions can cause missing CI secret scanning and unignored registry token configurations.
**Prevention:** Maintain automated secret scanning workflows and registry token `.gitignore` entries across all branches.
