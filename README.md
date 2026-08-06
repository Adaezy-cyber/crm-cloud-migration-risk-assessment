# CRM Cloud Migration Risk Assessment

Cloud migration offers scalability, flexibility, and cost savings, but it also changes an organization's risk profile. For financial services companies handling customer financial data and Personally Identifiable Information (PII), a poorly managed migration can lead to data breaches, regulatory penalties, operational disruption, and loss of customer trust.

This case study explores how I approached the risk assessment of a fictional CRM cloud migration using GRC principles from identifying risks to recommending practical treatment strategies.

## Why this project matters

Organizations continue to adopt cloud technologies to improve efficiency and scalability. However, successful cloud adoption depends on identifying and managing risk before systems go live.

This project demonstrates how a structured GRC approach can help organizations make informed decisions, strengthen security controls, and maintain regulatory compliance throughout a cloud migration.

## Scenario

Like many growing financial institutions, the  medium-sized financial services company is modernizing its infrastructure to improve scalability, to reduce operational overhead, and support a more flexible workforce. However, moving sensitive customer data to the cloud introduces technical, operational, regulatory, and reputational risks that must be assessed before migration.  This project walks through the risk management lifecycle for that migration: identifying risks, assessing and scoring them, and building mitigation plans for the highest-priority items.

## Objectives
- Identify risks introduced during cloud migration.
- Assess business impact and likelihood.
- Prioritize risks using a structured risk matrix.
- Recommend practical mitigation strategies.
- Demonstrate a GRC approach to cloud migration.

## What's in this repo

| File | Contents |
|---|---|
| [`docs/01-risk-concepts.md`](docs/01-risk-concepts.md) | Core definitions (risk, threat, vulnerability, impact, likelihood) and a comparison of qualitative vs. quantitative risk assessment methodologies |
| [`docs/02-risk-register.csv`](docs/02-risk-register.csv) | 10 identified risks with category, threat source, and vulnerability for each |
| [`docs/03-risk-matrix.md`](docs/03-risk-matrix.md) | Likelihood × impact scoring for the top 5 risks, with resulting risk levels |
| [`docs/04-mitigation-plan.md`](docs/04-mitigation-plan.md) | Detailed mitigation strategy, controls, stakeholders, and success metrics for the 3 highest-rated risks |

## Methodology

I approached this assessment by identifying the organization's critical assets, the threats that could affect them, the vulnerabilities those threats could exploit, and the resulting business impact. Each risk was then assessed based on likelihood and impact before being prioritized for treatment. Here is what i did: 

- **Risk identification** followed a threat–vulnerability–impact model across technical, operational, compliance, third-party, and reputational categories.
- **Risk scoring** used a 5×5 likelihood/impact matrix (score = likelihood × impact), with levels of Low (1–4), Medium (5–9), High (10–15), and Critical (16–25).
- **Mitigation planning** followed the standard four-strategy framework (avoid, transfer, mitigate, accept), with each plan tied to named stakeholders and measurable KPIs.

## Key findings

One of the biggest insights from this assessment was that the highest-rated risks weren't sophisticated cyberattacks. They were governance failures like: weak access controls, cloud misconfigurations, and inadequate protection of data during migration.

This reinforces an important lesson in GRC: many of the most damaging incidents occur because fundamental controls were missing or poorly implemented, not because attackers used advanced techniques. Some of the findings are: 
- The two most critical risks both centre on data exposure: **unauthorized access to customer financial information** and **exposure of data in transit during migration**;These two are scored in the Critical band (20–25).
- **Cloud storage misconfiguration** was the third Critical-rated risk, reinforcing that most severe exposure in this scenario is preventable through IAM and configuration discipline rather than exotic attack scenarios.
- Recommended mitigations centre on MFA, RBAC, least privilege, encryption in transit/at rest, and Cloud Security Posture Management (CSPM), controls that map directly to **NDPA** compliance obligations for organisations processing Nigerian personal data.

## Business Impact

If these risks are not managed effectively, the organization could experience:

- Regulatory penalties under the Nigeria Data Protection Act (NDPA).
- Loss of customer trust following exposure of financial information.
- Operational disruption affecting customer services.
- Financial losses associated with incident response and recovery.
- Reputational damage that could affect long-term business growth.

## Skills demonstrated

**Governance & Risk**
- Risk Identification
- Risk Assessment
- Risk Prioritization
- Risk Treatment
  
**Compliance**
- NDPA
- Data Protection Principles
- Stakeholder Accountability
  
**Security**
- IAM
- RBAC
- MFA
- CSPM
- Encryption
- Least Privilege

## Lessons Learned
This project reinforced that effective GRC is about enabling informed business decisions rather than eliminating every risk.

It also highlighted that cloud security depends just as much on governance, access management, and configuration discipline as it does on technical security controls.

## About

Prepared by me, **Adaeze Elizabeth Adeteye**, This project forms part of my growing Governance, Risk, and Compliance portfolio

## References
- NIST Cybersecurity Framework (CSF)
- NIST SP 800-30 Risk Assessment Guide
- ISO 31000 Risk Management Principles
- Nigeria Data Protection Act (NDPA) 2023

