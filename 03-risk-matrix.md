# Risk Assessment Matrix

From the 10 risks in the [risk register](02-risk-register.csv), the five most significant were scored using a 5×5 likelihood/impact matrix.

**Scoring model:** Risk Score = Likelihood (1–5) × Impact (1–5)

| Risk Level | Score Range |
|---|---|
| Low | 1–4 |
| Medium | 5–9 |
| High | 10–15 |
| Critical | 16–25 |

## Scored risks

| Risk | Likelihood | Impact | Risk Score | Risk Level |
|---|---|---|---|---|
| R1 — Unauthorized access to customer financial information | 5 | 5 | 25 | **Critical** |
| R2 — Exposure of customer data during migration | 4 | 5 | 20 | **Critical** |
| R3 — Cloud storage misconfiguration | 4 | 4 | 16 | **Critical** |
| R6 — Non-compliance with NDPA requirements | 3 | 5 | 15 | High |
| R8 — Cloud service outage | 3 | 4 | 14 | High |

## Reading the matrix

Three of the five top risks land in the Critical band, and all three trace back to the same root cause: **inadequate access and configuration discipline** rather than sophisticated external attacks. This points to where mitigation effort should concentrate first — see the [mitigation plan](04-mitigation-plan.md) for the treatment strategy on R1, R2, and R3.

The two High-rated risks (R6, R8) are lower in score mainly because likelihood is more moderate, but both carry severe-to-high impact — non-compliance with NDPA in particular carries regulatory and reputational consequences that make it worth tracking even outside the top three.
