## 2026-07-03 - Security Baseline Restoration
**Vulnerability:** Security baseline regression (missing Gitleaks workflow and insecure .gitignore)
**Learning:** Automated security controls (Gitleaks) and file exclusions (.npmrc, .yarnrc) are frequently missing in new branches, indicating a recurring baseline regression issue.
**Prevention:** Re-implementing the Gitleaks workflow and hardening .gitignore must be the first action in any branch where they are missing to maintain a consistent security posture.
