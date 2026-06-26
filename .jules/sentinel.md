## 2026-06-24 - Security baseline restoration
**Vulnerability:** Automated secret scanning and registry token exclusions were missing from the current branch.
**Learning:** Security controls must be established as a foundational baseline across all active development paths to avoid risks from branch inconsistencies.
**Prevention:** Always verify and restore security workflows (like Gitleaks) and environment hardening (like .gitignore) when entering a new development context.
