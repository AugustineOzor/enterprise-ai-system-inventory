# AI Risk Tier Model

The inventory classifies systems by risk. This is inspired by the [EU AI Act's risk-based approach](https://artificialintelligenceact.eu/high-level-summary/), which classifies AI as unacceptable risk (prohibited), high risk (regulated), limited risk (transparency obligations), or minimal risk (largely unregulated).

For this project, a practical internal risk tiering model is used instead of the EU AI Act's categories directly.

## Museum AI Risk Tier Model

| Tier | Description | Example | Governance Action |
|---|---|---|---|
| Low | Internal, non-sensitive productivity support | Formatting internal notes | Basic policy awareness |
| Medium | Internal workflow or records impact | Meeting summaries, metadata suggestions | Department approval and review |
| High | Public-facing, cultural, or collection-impacting AI | Chatbot, translation, image tagging | AI governance review required |
| Restricted | Confidential, legal, HR, donor, acquisition, or sensitive cultural data | Donor AI analysis, restricted provenance tool | Prohibited unless executive exception approved |

## Approval Status Model

Every AI system in the inventory should have one clear status.

| Status | Meaning |
|---|---|
| Approved | System may be used under standard controls |
| Approved with Controls | System may be used only with specific conditions |
| Pending Review | System is known but not approved yet |
| Remediation Required | System has gaps that must be fixed |
| Unapproved | System may not be used |
| Retired | System is no longer in use |
| Prohibited | System use is not allowed due to unacceptable risk |
