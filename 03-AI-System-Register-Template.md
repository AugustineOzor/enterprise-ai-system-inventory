# AI System Register Template

The register is the core artifact of the AI inventory program.

| Field | Description |
|---|---|
| AI System ID | Unique identifier |
| System Name | Name of tool or AI system |
| Department | Business unit using it |
| Business Owner | Person or role accountable |
| Vendor | Internal or third-party provider |
| AI Type | Generative, translation, vision, etc. |
| Purpose | Business use |
| Data Used | Main input data |
| Data Classification | Public, internal, confidential, restricted |
| Public-Facing | Yes / No |
| Human Review | Required / Not required |
| Risk Tier | Low / Medium / High / Restricted |
| Approval Status | Approved / Pending / Unapproved / Retired |
| Monitoring Required | Yes / No |
| Last Review Date | Date reviewed |
| Next Review Date | Date for reassessment |

## Operating Procedure

How an AI system moves from proposal to a maintained register entry:

1. New AI tool is proposed.
2. Staff completes the [AI System Intake Form](02-AI-System-Intake-Form.md).
3. Data classification is assigned.
4. Risk tier is assigned (see [AI Risk Tier Model](05-AI-Risk-Tier-Model.md)).
5. Business owner is confirmed.
6. Required controls are documented.
7. Governance decision is recorded.
8. System is added to the AI register.
9. Dashboard is updated.
10. System is reviewed according to the [review cadence](07-AI-Inventory-Dashboard.md#review-cadence).
