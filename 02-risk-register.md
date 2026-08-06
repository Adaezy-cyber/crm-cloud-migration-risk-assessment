# Risk Register

## Overview

Cloud migration presents significant opportunities for organizations to improve scalability, operational efficiency, and service delivery. However, for financial services organizations handling customer financial information and Personally Identifiable Information (PII), it also introduces new technical, operational, compliance, and business risks.

This risk register identifies the key risks associated with migrating the organization's Customer Relationship Management (CRM) system from an on-premises environment to the cloud. Each risk considers the potential threat, the vulnerability that could be exploited, and the possible business impact if the risk materializes.

The register provides the foundation for the subsequent risk assessment, prioritization, and treatment activities carried out throughout this project.

---

## Risk Register

| ID | Risk Statement | Risk Category | Threat Source / Actor | Vulnerability Exploited |
|----|----------------|---------------|-----------------------|-------------------------|
| **R1** | There is a risk that unauthorized individuals could gain access to customer financial information if weak Identity and Access Management (IAM) controls are exploited, resulting in data breaches, regulatory penalties, financial loss, and loss of customer trust. | Technical | External attackers | Weak Identity and Access Management (IAM) controls |
| **R2** | There is a risk that sensitive customer financial information and Personally Identifiable Information (PII) could be intercepted during migration if data is transmitted without adequate encryption, resulting in unauthorized disclosure of confidential information and potential regulatory violations. | Technical | Cybercriminals | Data is not encrypted during migration |
| **R3** | There is a risk that customer financial information and PII could become publicly accessible if cloud storage resources are misconfigured, resulting in unauthorized access, data exposure, regulatory non-compliance, and reputational damage. | Technical | Cloud administrator error | Incorrect storage permissions |
| **R4** | There is a risk that customer records could be accidentally deleted, modified, or corrupted during migration because of inadequate backup procedures or weak change management practices, disrupting business operations and affecting data integrity. | Operational | Internal staff | Poor backup and change management procedures |
| **R5** | There is a risk that ransomware could disrupt the migration process by exploiting unpatched systems or weak endpoint security, making critical customer information unavailable and delaying business operations. | Security | Cybercriminals | Unpatched systems and weak endpoint security |
| **R6** | There is a risk that the organization could fail to comply with the requirements of the Nigeria Data Protection Act (NDPA) if compliance obligations are not adequately addressed during migration, resulting in regulatory investigations, financial penalties, and reputational damage. | Compliance | Regulatory bodies | Inadequate compliance planning |
| **R7** | There is a risk that employees with excessive access privileges could intentionally or unintentionally access customer information beyond their job responsibilities, increasing the likelihood of insider-related security incidents and unauthorized disclosure of sensitive information. | Operational | Insider threat | Lack of the Principle of Least Privilege and periodic access reviews |
| **R8** | There is a risk that outages affecting the cloud service provider could interrupt access to the CRM system because of insufficient redundancy and disaster recovery planning, affecting business continuity, employee productivity, and customer service delivery. | Operational | Cloud service provider | Limited redundancy and disaster recovery planning |
| **R9** | There is a risk that weaknesses in the cloud service provider's security controls could expose customer information through a third-party compromise, affecting the confidentiality, integrity, and availability of sensitive business data. | Third-party | Cloud service provider | Inadequate vendor security assurance |
| **R10** | There is a risk that a successful data breach could reduce customer confidence, damage the organization's reputation, and negatively affect future business growth if security incidents are not effectively prevented, detected, and managed. | Reputational | External attackers and public scrutiny | Weak incident response processes |

---

## Key Observations

A review of the identified risks highlights several important trends:

- Most of the highest-priority risks are related to **Identity and Access Management (IAM), cloud configuration, and data protection** rather than highly sophisticated cyberattacks.
- The migration process introduces both **technical and business risks**, requiring collaboration between security, IT operations, compliance, and business stakeholders.
- Several risks could have significant regulatory implications under the **Nigeria Data Protection Act (NDPA)** because the CRM system processes sensitive customer financial information and Personally Identifiable Information (PII).
- Many of the identified risks can be significantly reduced through proactive governance, strong access controls, secure cloud configuration, encryption, continuous monitoring, and effective change management.

The findings from this risk register formed the basis for the risk assessment matrix, where the identified risks were prioritized according to their likelihood and business impact before appropriate mitigation strategies were developed.
