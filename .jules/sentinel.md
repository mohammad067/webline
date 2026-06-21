## 2026-06-21 - Security baseline restoration and leakage prevention hardening
**Vulnerability:** Security baseline regression identified; Gitleaks secret scanning workflow and registry token exclusions (.npmrc, .yarnrc) were missing.
**Learning:** Security controls must be consistently maintained across all development paths. The absence of these controls increases the risk of sensitive data exposure and unauthorized access via leaked tokens.
**Prevention:** Explicitly verify the presence of the security baseline (Gitleaks workflow and hardened .gitignore) in every branch. Restore foundational security controls immediately upon identifying their absence.
