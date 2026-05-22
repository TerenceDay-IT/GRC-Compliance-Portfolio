# NIST SP 800-53 Control Gap Assessment

## Executive Summary
This matrix tracks our fictional organization's compliance posture against select NIST SP 800-53 security controls and maps out our Plan of Action and Milestones (POA&M) for remediation.

| Control ID | Control Name | NIST Requirement | Company Implementation | Status | Remediation Plan / POA&M |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **AC-2** | Account Management | Establish and manage system accounts. | HR triggers automated IT ticket for onboarding/termination. | **Compliant** | None. Review process annually. |
| **IA-2** | Identification and Authentication | Enforce multi-factor authentication (MFA). | MFA enforced via Okta on cloud systems; 3 legacy servers use single passwords. | **Partially Compliant** | **POA&M-001:** Deploy Okta agents to legacy servers by Q3. |
| **MP-4** | Media Storage | Restrict access to digital media / local drives. | Employees are downloading customer data directly onto personal laptops. | **Non-Compliant** | **POA&M-002:** Implement MDM to block local downloads of sensitive data. |