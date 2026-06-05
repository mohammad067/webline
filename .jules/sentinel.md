## 2026-06-05 - [Baseline] Implement Gitleaks Secret Scanning
**Vulnerability:** Potential exposure of secrets (API keys, credentials) in the repository due to lack of automated scanning.
**Learning:** Security controls like Gitleaks must be established as a foundational baseline across all active development paths, as inconsistencies between branches can create security risks.
**Prevention:** Integrate automated secret scanning (Gitleaks) into the CI/CD pipeline to detect and prevent credential leakage at the source.
