## 2026-08-12 - Re-establishment of Gitleaks Security Baseline and Registry Token Exclusions
**Vulnerability:** Security baseline regressions due to missing automated secret scanning workflows and registry token exclusions on active development branches.
**Learning:** Security configurations must be preserved consistently across all active branches. Git baseline regressions can occur during branching or PR merges, temporarily removing secret scanning workflows and exposing registry configuration files like `.npmrc` and `.yarnrc`.
**Prevention:** Enforce consistent security baselines across all development tracks by re-implementing standard Gitleaks workflows (`gitleaks.yml` pinned with secure action SHAs) and hardening `.gitignore` files against potential registry credentials exposure.
