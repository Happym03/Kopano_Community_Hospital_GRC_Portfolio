

# Kopano Community Hospital — GRC Portfolio Project

> ⚠️ **Fictional organisation.** Kopano Community Hospital is a fictional 200-bed public/community hospital created for GRC portfolio-building purposes. It is not modelled on, or affiliated with, any real hospital in Katlehong or elsewhere in South Africa. All documents, findings, and data in this repository are illustrative.

## Overview

This repository is a Governance, Risk and Compliance (GRC) portfolio project set in a healthcare context, built to demonstrate practical GRC skills applied to a high-stakes environment: patient safety, special personal information under POPIA, medical device security, and clinical system continuity.

The project models how a hospital's Information Governance function would structure its documentation suite — from the top-level governance charter down to incident response and disaster recovery — with each document cross-referencing the others the way a real GRC programme would.

**Organisation profile**
- **Name:** Kopano Community Hospital
- **Location:** Katlehong, Ekurhuleni, Gauteng, South Africa
- **Type:** 200-bed public/community hospital — casualty, maternity, general medicine
- **In-scope systems:** Electronic Health Record (EHR), Laboratory Information System (LIS), Picture Archiving and Communication System (PACS), pharmacy dispensing system, networked biomedical devices, supporting IT infrastructure

## Repository Contents

| # | Document | Type | Description |
|---|----------|------|-------------|
| 01 | `01_Governance_Charter.docx` | Word | Establishes the GRC mandate, the Hospital Information Governance Committee (HIGC) structure, RACI matrix, and risk appetite statement |
| 02 | `02_Risk_Register.xlsx` | Excel | Live risk register — 9+ risks across cyber, POPIA, third-party, business continuity, medical device, insider threat, physical security, and change management categories, each with inherent/residual scoring, owner, and treatment plan |
| 03 | `03_ISO27001_Gap_Assessment.xlsx` | Excel | Control-by-control gap assessment against ISO/IEC 27001:2022 Annex A, scoped to the clinical information environment |
| 04 | `04_POPIA_Compliance_Assessment.docx` | Word | Assessment against the eight conditions for lawful processing (POPIA Chapter 3), plus special personal information (health data) considerations under sections 26–27 |
| 05 | `05_Incident_Response_Playbook.docx` | Word | Incident response procedures covering ransomware, medical device compromise, and unauthorised patient record access, plus the POPIA section 22 breach notification procedure |
| 06 | `06_Business_Continuity_DR_Summary.docx` | Word | RTO/RPO targets for critical clinical systems, backup strategy, ward-level downtime procedures, and the annual testing programme |

## How the Documents Connect

The six documents are designed to be read as a single, cross-referenced programme rather than in isolation:

- The **Governance Charter** sits at the top, defining the HIGC, roles, and risk appetite that everything else operates under.
- The **Risk Register** is the live, central artifact — every risk links forward to the specific ISO control, POPIA section, or playbook scenario that treats it.
- The **ISO 27001 Gap Assessment** shows current control maturity (2 Implemented / 15 Partially Implemented / 4 Not Implemented, of 21 controls assessed) and feeds prioritised actions back into the Risk Register.
- The **POPIA Compliance Assessment** evaluates lawful processing of patient data and flags where security safeguards overlap with ISO controls (Condition 7) and where breach readiness overlaps with the Incident Response Playbook (Section 7).
- The **Incident Response Playbook** and **Business Continuity/DR Summary** operationalise how the Hospital actually responds when something goes wrong — including patient-safety-first downtime procedures that keep clinical care running on paper if systems fail.

## Key Themes Demonstrated

- **Healthcare-specific risk framing:** patient safety is explicitly prioritised over system availability in every document (e.g. "do not power off encrypted machines," manual fallback procedures for every critical system).
- **POPIA special personal information handling:** health data treated under sections 26–27, including confidentiality undertakings for non-clinical staff and a documented breach notification SLA.
- **Regulatory breadth:** POPIA, ISO/IEC 27001:2022, the National Health Act, HPCSA guidance, and SAHPRA medical device vigilance requirements are all referenced where relevant.
- **Realistic maturity levels:** findings are deliberately mixed — some controls compliant, most partially implemented with named gaps and owners, reflecting a real organisation mid-improvement rather than either a blank slate or a fully mature ISMS.
- **Traceability:** every document ends with a "Related Documents" section showing exactly how it links to the rest of the portfolio.

## Companion Project

This project pairs with **Happy Insurance Brokers** (a FAIS/insurance-sector GRC portfolio in a separate repository), demonstrating GRC application across two different regulated industries — financial services and healthcare.

## Author

Built by Happy Thabile Mngoma as part of a GRC and cybersecurity compliance portfolio.
- GitHub: [github.com/Happym03](https://github.com/Happym03)
- LinkedIn: [linkedin.com/in/thabile-mngoma-79552a184](https://linkedin.com/in/thabile-mngoma-79552a184)
