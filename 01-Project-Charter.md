# Project Charter — Enterprise AI System Inventory and AI Governance Register

**Project:** Enterprise AI System Inventory Implementation Program
**Environment:** Museum, Cultural Heritage, Metadata, and Records-Management Environment

## 1. Project Overview

This project creates a real-world AI System Inventory Program for a museum, cultural heritage, metadata, and records-management environment.

The goal is to build a centralized register of all AI systems used across the organization, including approved tools, vendor tools, internal experiments, public-facing systems, and shadow AI tools.

The inventory helps leadership answer:

- What AI systems are being used?
- Who owns each system?
- What data does each system use?
- Which systems are public-facing?
- Which systems process sensitive information?
- Which systems require human review?
- Which systems are approved, pending, or unapproved?
- Which systems need risk assessment?
- Which systems need monitoring?
- Which systems may fall into higher regulatory or governance risk categories?

This project demonstrates practical AI governance operations because AI governance starts with visibility.

## 2. Business Problem

A museum has several departments using AI tools, but no central inventory exists.

Departments may be using AI for:

- Object description drafting
- Metadata enhancement
- Image tagging
- Exhibition translation
- Visitor chatbot support
- Meeting summaries
- Public content drafting
- Research support
- Email drafting
- Spreadsheet cleanup
- Records management
- Collection search

Some tools are approved. Others may be informal or "shadow AI" tools used by staff without formal review.

This creates serious governance challenges:

- Leadership does not know which AI tools are active.
- Sensitive data could be uploaded to unapproved systems.
- Public-facing AI content may not be reviewed.
- AI-generated metadata may enter official records without validation.
- Vendor tools may use museum data in unclear ways.
- No one knows which AI systems require monitoring.
- AI risks cannot be managed consistently.

The purpose of this project is to solve this by implementing a formal AI System Inventory and Governance Register.

## 3. Project Goal

Create an operational AI inventory process that allows the museum to:

- Identify all AI systems in use
- Assign business owners
- Classify risk
- Track approval status
- Identify public-facing systems
- Identify sensitive data use
- Document required controls
- Support AI governance committee review
- Prepare for audits and compliance reviews
- Maintain a living AI register

## 4. Why This Is a Real-World Project

This project reflects how organizations actually begin AI governance. Before policies, audits, and dashboards work, an organization needs a clear inventory.

The [NIST AI RMF Core](https://airc.nist.gov/airmf-resources/airmf/5-sec-core/) is structured around **Govern, Map, Measure, and Manage**. This project primarily supports the **Govern** and **Map** functions by creating visibility, ownership, accountability, and risk classification for AI systems.

The [OECD AI Principle on Accountability](https://oecd.ai/en/dashboards/ai-principles/P9) states that AI actors should ensure traceability, including in relation to datasets, processes, and decisions made during the AI system lifecycle. An AI system inventory is one of the practical ways to create that traceability.

## 5. Charter Details

| Field | Detail |
|---|---|
| **Project Name** | Enterprise AI System Inventory Program |
| **Organization Type** | Museum / Cultural Heritage / Records and Metadata Environment |
| **Business Sponsor** | Executive Leadership or Director of Operations |
| **Governance Owner** | AI Governance Committee |
| **System Inventory Owner** | Records Management / Data Governance Team |

**Supporting Teams:** Collections, Registration, Curatorial, Digital Collections, Visitor Services, Exhibitions, Education, Communications, IT, Legal / Compliance, Procurement, Records Management

**Project Objective:** Create and maintain a centralized inventory of AI systems used across the organization.

**Success Criteria:**

- All known AI systems are recorded.
- Each AI system has a business owner.
- Each AI system has a risk tier.
- Each AI system has an approval status.
- Public-facing systems are clearly identified.
- Systems using sensitive data are flagged.
- Shadow AI tools are identified and reviewed.
- High-risk systems are escalated for governance review.
- Inventory dashboard is updated regularly.
- AI inventory becomes part of audit readiness evidence.

## 6. Scope

**In Scope** — the AI inventory covers:

- Internal AI tools
- Vendor AI products
- Generative AI tools
- Chatbots
- Translation AI
- Image recognition AI
- Metadata enhancement AI
- Meeting summarization tools
- AI embedded in productivity software
- AI used in records workflows
- AI used in public communication
- Shadow AI used by staff

**Out of Scope** — this project does not:

- Build an AI model
- Replace a full AI risk assessment
- Certify regulatory compliance
- Perform legal classification
- Conduct cybersecurity testing
- Approve vendors by itself

The inventory is the starting point for governance, not the final approval mechanism.

## 7. Implementation Phases

| Phase | Description |
|---|---|
| 1 | Discovery and Stakeholder Mapping |
| 2 | AI System Intake Form Design |
| 3 | AI System Register Creation |
| 4 | Risk Tiering and Classification |
| 5 | Ownership and Approval Review |
| 6 | Shadow AI Identification |
| 7 | Governance Dashboard Creation |
| 8 | Review Cadence and Audit Readiness |

## 8. Phase 1 — Discovery and Stakeholder Mapping

**Objective:** Identify where AI is being used across the organization.

**Discovery Questions** (ask each department):

1. What AI tools are currently used by the team?
2. Are any AI tools embedded inside existing software?
3. What tasks are supported by AI?
4. What data is entered into the AI tool?
5. Are outputs used internally or publicly?
6. Are outputs reviewed by a human?
7. Is the AI tool approved by IT or leadership?
8. Is the AI tool free, paid, vendor-provided, or built internally?
9. Does the tool process personal, confidential, or cultural heritage data?
10. Who is responsible for the tool?

**Stakeholder Map**

| Stakeholder | Role in Inventory |
|---|---|
| Executive Leadership | Sponsors AI governance visibility |
| AI Governance Committee | Reviews high-risk systems |
| Data Governance Team | Maintains inventory fields |
| Records Manager | Reviews records impact |
| Registrar | Reviews collection record impact |
| Curators | Review cultural and interpretive risks |
| IT | Identifies approved and unapproved tools |
| Procurement | Identifies vendor AI tools |
| Legal / Compliance | Reviews high-risk or sensitive tools |
| Department Heads | Confirm systems used by teams |
