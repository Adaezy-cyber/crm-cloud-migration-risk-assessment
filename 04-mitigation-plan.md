# Risk Mitigation Plan

Detailed treatment plans for the three highest-rated risks from the [risk matrix](03-risk-matrix.md).

---

## Risk 1: Unauthorized access to customer financial information

**Risk statement:** Unauthorized users gain access to sensitive customer information after the CRM migration.

**Mitigation approach:** *Mitigate.* Strengthening access controls is prioritized over avoiding migration entirely, since access management is one of the biggest risk drivers in cloud environments.

**Controls/actions:**
- Enforce Multi-Factor Authentication (MFA) for all users
- Apply Role-Based Access Control (RBAC)
- Follow the Principle of Least Privilege
- Review user access regularly
- Monitor user activity through a SIEM solution
- Use Privileged Access Management (PAM) for administrator accounts

**Responsible stakeholders:** CISO, IAM Administrator, Cloud Security Engineer, IT Security Team

**Effectiveness metrics:**
- % of users enrolled in MFA
- Number of unauthorized access attempts detected
- Number of unnecessary privileged accounts removed
- Reduction in access-related incidents

**Residual risk:** Low

---

## Risk 2: Exposure of customer data during migration

**Risk statement:** Sensitive customer information is exposed while migrating data to the cloud.

**Mitigation approach:** *Mitigate.* Focus on keeping data protected throughout the migration process itself, rather than only at rest.

**Controls/actions:**
- Encrypt all data in transit and at rest
- Restrict migration activities to authorized personnel only
- Validate migrated data to ensure integrity
- Implement Data Loss Prevention (DLP)
- Conduct security testing before go-live

**Responsible stakeholders:** Data Protection Officer (DPO), Database Administrator, Cloud Migration Team, Security Operations Centre (SOC)

**Effectiveness metrics:**
- % of encrypted data transfers
- Number of detected data leakage incidents
- Successful integrity verification checks
- Security assessment findings after migration

**Residual risk:** Low

---

## Risk 3: Cloud storage misconfiguration

**Risk statement:** Cloud storage is configured incorrectly, exposing sensitive customer information.

**Mitigation approach:** *Mitigate.* Preventive controls before migration completes, paired with continuous monitoring afterward.

**Controls/actions:**
- Follow secure cloud configuration standards
- Perform regular configuration reviews
- Use Cloud Security Posture Management (CSPM)
- Conduct vulnerability assessments and penetration testing
- Enable alerts for unauthorized configuration changes

**Responsible stakeholders:** Cloud Administrator, DevSecOps Engineer, Cloud Security Engineer, Internal Audit Team

**Effectiveness metrics:**
- Number of cloud misconfigurations detected
- % of compliant cloud resources
- Mean Time to Remediate (MTTR)
- Number of publicly exposed storage resources

**Residual risk:** Low

---

## Summary

All three highest-rated risks were treated with a **mitigate** strategy rather than avoid, transfer, or accept — reflecting that the migration itself is a business necessity, but the specific exposure paths (access, transit, configuration) are controllable. Each plan is anchored to named stakeholders and quantifiable metrics so effectiveness can be tracked post-migration rather than assumed.
