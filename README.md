# CRM Cloud Migration Risk Assessment

A GRC case study applying risk management fundamentals to a realistic scenario: a mid-sized financial services company migrating its CRM system from on-premises infrastructure to the cloud.

## Scenario

A medium-sized financial services company is migrating its CRM system — which holds customer financial information and PII — from an on-premises solution to a cloud-based service. This project walks through the risk management lifecycle for that migration: identifying risks, assessing and scoring them, and building mitigation plans for the highest-priority items.

## What's in this repo

| File | Contents |
|---|---|
| [`docs/01-risk-concepts.md`](docs/01-risk-concepts.md) | Core definitions (risk, threat, vulnerability, impact, likelihood) and a comparison of qualitative vs. quantitative risk assessment methodologies |
| [`docs/02-risk-register.csv`](docs/02-risk-register.csv) | 10 identified risks with category, threat source, and vulnerability for each |
| [`docs/03-risk-matrix.md`](docs/03-risk-matrix.md) | Likelihood × impact scoring for the top 5 risks, with resulting risk levels |
| [`docs/04-mitigation-plan.md`](docs/04-mitigation-plan.md) | Detailed mitigation strategy, controls, stakeholders, and success metrics for the 3 highest-rated risks |

## Methodology

- **Risk identification** followed a threat–vulnerability–impact model across technical, operational, compliance, third-party, and reputational categories.
- **Risk scoring** used a 5×5 likelihood/impact matrix (score = likelihood × impact), with levels of Low (1–4), Medium (5–9), High (10–15), and Critical (16–25).
- **Mitigation planning** followed the standard four-strategy framework (avoid, transfer, mitigate, accept), with each plan tied to named stakeholders and measurable KPIs.

## Key findings

- The two most critical risks both centre on data exposure: **unauthorized access to customer financial information** and **exposure of data in transit during migration** — both scored in the Critical band (20–25).
- **Cloud storage misconfiguration** was the third Critical-rated risk, reinforcing that most severe exposure in this scenario is preventable through IAM and configuration discipline rather than exotic attack scenarios.
- Recommended mitigations centre on MFA, RBAC, least privilege, encryption in transit/at rest, and Cloud Security Posture Management (CSPM) — controls that map directly to **NDPA** compliance obligations for organisations processing Nigerian personal data.

## Skills demonstrated

Risk identification · Qualitative & quantitative risk assessment · Risk matrix scoring · Risk treatment planning · NDPA-aligned controls · Stakeholder mapping · GRC documentation

## About

Prepared by Adaeze Elizabeth Adeteye as part of independent GRC study (ICDFA GRC101 coursework), and adapted here as a public portfolio artifact.
