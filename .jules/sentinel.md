## 2026-06-22 - Restore Security Baseline
**Vulnerability:** Security baseline regression (missing Gitleaks workflow and registry token exclusions).
**Learning:** Foundational security controls like secret scanning and leakage prevention can be lost during branch merges or resets.
**Prevention:** Always verify and re-establish the security baseline (Gitleaks workflow with SHA pinning and .gitignore hardening) as a first step in every session.
