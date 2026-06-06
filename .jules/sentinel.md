## 2026-06-06 - Re-implementation of Gitleaks baseline
**Vulnerability:** Security baseline regression; several development branches were found lacking the Gitleaks secret scanning workflow despite it being a project standard.
**Learning:** Security controls must be established as a foundational baseline across all active development paths early on. Inconsistent application of security workflows across branches can lead to temporary "blind spots" where secrets could be committed without detection.
**Prevention:** Ensure that the foundational security baseline (including .gitignore, SECURITY.md, and secret scanning workflows) is one of the first things implemented in any new repository or project branch, and verify its presence during security audits.
