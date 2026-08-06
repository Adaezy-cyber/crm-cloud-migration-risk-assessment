# Risk Management Concepts

## Core definitions

**Risk**
The possibility that something could go wrong and prevent an organization from achieving its objectives. In cybersecurity, risk exists when a threat finds an opportunity to exploit a weakness in a system — potentially leading to financial loss, service disruption, legal exposure, or reputational damage.

**Threat**
Anything with the potential to cause harm to an organization's information or systems — an external attacker, a malicious insider, human error, or even a natural disaster.

**Vulnerability**
A weakness in a system, process, or among people. If discovered and exploited by a threat, it can result in a security incident. Examples: weak passwords, outdated software, poor access controls, misconfigured cloud storage.

**Impact**
The consequences if a risk materializes — financial loss, regulatory penalties, downtime, or loss of customer trust.

**Likelihood**
How probable it is that a threat will successfully exploit a vulnerability, shaped by existing controls, target attractiveness, and the frequency of similar attacks elsewhere.

### How they connect

A threat looks for a vulnerability to exploit. If it succeeds, the organization experiences an impact. The combination of likelihood and impact severity determines the overall risk level.

**Example:** A financial institution moves its CRM to the cloud without properly configuring access permissions. That misconfiguration is a vulnerability. A cybercriminal (threat) could exploit it to reach customer financial data. Because the data is sensitive, the impact would be severe — making this a high-priority risk that should be addressed before migration, not after.

## Qualitative vs. quantitative risk assessment

**Qualitative risk assessment** uses descriptive ratings (Low / Medium / High / Critical), based largely on expert judgment, experience, and stakeholder discussion.

**Quantitative risk assessment** uses numerical values and financial estimates — probability of occurrence and potential monetary impact — to price the cost of a security incident.

| | Advantages | Disadvantages |
|---|---|---|
| **Qualitative** | Fast to perform; useful with limited historical/financial data; accessible to technical and non-technical stakeholders alike | Relies on human judgment; results can be subjective; different assessors may rate the same risk differently |
| **Quantitative** | More objective and measurable; supports budgeting, cost-benefit analysis, and strategic planning; easier for management to justify security investment | Requires reliable historical and financial data; more time- and expertise-intensive |

### When to use which

For a CRM cloud migration, a **qualitative** assessment fits the planning stage — the organization needs to identify and prioritize the biggest risks before migration begins, often without enough data for precise financial modelling. Once migration is underway or complete, a **quantitative** assessment becomes more valuable — estimating potential financial losses, evaluating control effectiveness, and supporting future investment decisions.

In practice, using both approaches together — qualitative first, quantitative once data exists — gives the most complete picture of the organization's risk landscape.
