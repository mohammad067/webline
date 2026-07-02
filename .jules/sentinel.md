## 2026-07-02 - Security Baseline Restoration
**Vulnerability:** Automated secret scanning (Gitleaks) and registry token exclusions (.npmrc, .yarnrc) were missing due to a recurring baseline regression in the current branch.
**Learning:** Security controls established in other branches or the main branch are not automatically present in new or isolated branches, leading to inconsistent security postures across the codebase.
**Prevention:** Always verify and restore the security baseline (Gitleaks workflow and hardened .gitignore) as the first step when working in a new or regressed environment.
