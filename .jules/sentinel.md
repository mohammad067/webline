## 2026-05-23 - Establishing Security Governance and Baseline Consistency
**Vulnerability:** Inconsistent security controls across branches (e.g., missing Gitleaks and hardened .gitignore).
**Learning:** Security controls must be established as a foundational baseline across all active development paths to prevent gaps.
**Prevention:** Implement mandatory security governance files and automated scanning at the start of project development and ensure they are maintained across all branches.

## 2026-05-23 - Security Governance and "Security Theater"
**Vulnerability:** Inefficient security processes (specifically mandatory reviews for non-critical files).
**Learning:** Security governance involving `.github/CODEOWNERS` for mandatory review was rejected as "security theater" because it failed to provide tangible protection against identified risks and added unnecessary overhead.
**Prevention:** Focus security enhancements on controls with direct, measurable impact (like automated secret scanning) rather than administrative layers that lack immediate security benefit.
