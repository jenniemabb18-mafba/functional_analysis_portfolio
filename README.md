# Jennie Mabb, M.S.
### Senior Process & Management Analyst | Data Quality & Governance Specialist
**Specializing in Requirements Elicitation, Compliance Architecture & Operational Governance**

[![ISO 27001 Lead Implementer](https://img.shields.io/badge/Certified-ISO%2027001%20Lead%20Implementer-0A66C2)](#)
[![Public Trust](https://img.shields.io/badge/Security%20Status-Former%20Public%20Trust%20(DOJ)-orange)](#)
[![Location](https://img.shields.io/badge/Location-Virginia%20(Remote--Preferred)-informational)](#)

---

## Executive Summary

Accomplished Senior Analyst with **10+ years of experience** navigating high-trust, heavily regulated environments—including **Federal Justice, Sovereign Tribal Governments, Institutional Facilities, and Global Banking**. 

* **Audit & Compliance Excellence:** Certified **ISO 27001 Lead Implementer** with a track record of maintaining **100% audit accuracy** across complex state and federal compliance frameworks (PCI DSS v4.0.1, GDPR, CJIS).
* **Bridging Business & Tech:** Proven ability to translate high-level executive objectives into rigorous technical deliverables—spanning **UML process workflows**, **SQL relational integrity**, and **100+ point Functional Requirements Documents (FRDs)**.
* **Human-Centered Systems Design:** Leveraging a **Master of Science in Mental Health Counseling** to provide an uncommon edge in advanced stakeholder elicitation, cross-functional conflict de-escalation, and behavioral data modeling.

---

## Core Competencies

| Domain | Key Strengths & Tooling |
| :--- | :--- |
| **Governance & Compliance** | ISO 27001, PCI DSS v4.0.1, GDPR (Data Minimization / Privacy by Design), Audit Trails & Controls, Compliance-by-Design Architecture |
| **Analysis & Modeling** | SDLC, Agile Requirements Elicitation, UML (Sequence Diagrams, Activity Maps), FRD/BRD Authoring |
| **Data & Architecture** | SQL (MySQL), Relational Schema Design, Referential Integrity, Data Normalization, Large-Scale Migration Planning |
| **Human & Operational Dynamics** | Clinical Elicitation, Executive Stakeholder Alignment, Root-Cause Diagnostics, Conflict Resolution |

---

## Learning Portfolio & Design Studies

This portfolio documents **deep-dive design studies and educational projects** created to develop expertise in compliance architecture, systems design, and data integrity. Each artifact demonstrates rigorous analytical thinking and technical depth—while being transparent about scope (educational vs. production).

---

### 1. Compliance Architecture & Design Studies

#### **PCI-DSS Tokenization Architecture — Design Study**
* **Artifacts:** [Tokenization Architecture Board](./PCI-DSS_Tokenization_Architect_Board.jpg) • [Compliance Translation Matrix](./PCI-DSS_GDPR_Compliance_Translation_Matrix.pdf) • [Matrix Scope](./PCI-DSS_GDPR_Compliance_Translation_Matrix_Scope.pdf)
* **Objective:** Create a conceptual design demonstrating deep understanding of PCI DSS token vaulting principles and how to architect compliance intent into database schema from inception.
* **Key Architecture Concepts:**
  * **Identity Vault (`Table 1`):** PII isolation strategy using surrogate keys (`UID`) to decouple identity from payment data.
  * **Account Mapping Layer (`Table 2`):** Decoupled translation bridge reducing audit scope exposure.
  * **Prescriptive CDE (`Table 3`):** Hardened vault design containing encrypted PANs as the primary audit boundary.
  * **Ephemeral Handshake:** Cryptographic randomizers producing dynamic CVVs (dCVVs) with 90-second expirations.
* **Framework Alignment:** Demonstrates understanding of PCI DSS v4.0.1 (Sensitive Authentication Data non-persistence) and GDPR Article 32 (Pseudonymization & Data Minimization).
* **What This Shows:** Schema thinking, compliance-by-design methodology, regulatory analysis, foreign key placement strategy.

#### **Privacy by Design in Automated Systems — Research Study**
* **Artifact:** [GDPR White Paper: Privacy by Design in Automated Systems](./White_Paper_ANN_GDPR_Mabb.pdf)
* **Objective:** Educational analysis of the systemic tension between machine learning / personalization and statutory privacy mandates.
* **Key Deliverables:** Legal-technical assessment of **Right to Erasure** and **Data Portability** compliance within non-linear learning models, establishing verifiable audit-ready controls.
* **What This Shows:** Ability to translate complex regulatory requirements into technical implications, privacy-first thinking.

---

### 2. Functional Requirements & Systems Design

#### **Cloud Platform Modernization — Driver Education System (Design Exercise)**
* **Artifact:** [Functional Requirements Document (NTS)](./NTS_Functional_Requirements_Design.pdf)
* **Objective:** Comprehensive requirements lifecycle design for a hypothetical system transformation from legacy manual workflow to secure cloud architecture.
* **Key Deliverables:** Authored a detailed **100+ point FRD** defining granular Role-Based Access Control (RBAC), end-to-end audit trails, state-transition rules, and stakeholder-friendly technical documentation.
* **What This Shows:** Requirements elicitation depth, stakeholder communication, system logic design, ability to bridge business and technical language.

#### **Distributed Architecture Evaluation — Strategic Analysis**
* **Artifact:** [Strategic Architectural Analysis White Paper](./Software_Design_Project_Mabb.pdf)
* **Objective:** Comparative architecture study exploring trade-offs in transitioning standalone environments to distributed, web-enabled infrastructure.
* **Key Deliverables:** Multi-environment benchmark (Linux, Windows, macOS) analyzing scalability, cost efficiency, and cross-platform delivery strategy (Kotlin).
* **What This Shows:** Architectural thinking, cost-benefit analysis, platform evaluation methodology.

---

### 3. Data Architecture, Migrations & Interactive Systems

#### **Large-Scale Database Migration Specification — Design Study**
* **Artifact:** [MySQL Data Integrity & Migration Specification](./MySQL_Data_Integrity_and_Migration_Specification_Mabb.pdf)
* **Objective:** Detailed technical specification for a zero-loss schema overhaul encompassing **37,994 sample records**.
* **Key Deliverables:** Formalized migration runbook enforcing referential integrity, standardized data types, and pre/post-migration verification protocols.
* **What This Shows:** Data integrity thinking, migration planning, attention to compliance-ready documentation, SQL expertise.

#### **Real-Time Transaction & Schema Simulator — Interactive Learning Tool**
* **Artifacts:** [Interactive Schema Canvas (ERD)](./Credit_Card_Bonuses_database_schema_flow_visualizer.html) • [Core Flow Visualizer](./Credit_Card_Bonuses_process_flow_visualizer.html)
* **Objective:** Interactive simulation demonstrating real-time transaction validation, schema boundary enforcement, and relational integrity.
* **Key Deliverables:** Dynamic SVG visualizer enforcing strict 1:1 and 1:N integrity constraints, latency reduction logic, and live SQL command tracing.
* **What This Shows:** Technical visualization skills, understanding of relational constraints, ability to make complex concepts tangible.

#### **System Logic & Actor Workflows — UML Design Suite**
* **Artifact:** [UML System Logic & UX Modeling Specification](./NTS_UML_System_Designs_Mabb.pdf)
* **Objective:** Process modeling to identify operational bottlenecks and user-journey fragmentation before development begins.
* **Key Deliverables:** Complete UML suite (Sequence Diagrams, Activity Maps, UI state machines) for inventory and task management scenarios.
* **What This Shows:** Systems thinking, process visualization, logical workflow design, operational optimization mindset.

---

## Architectural Blueprints & Workflows

<details open>
<summary><b>Click to expand / collapse blueprint previews</b></summary>
<br>

| Blueprint | Description |
| :--- | :--- |
| **PCI-DSS Stateless Tokenization Board**<br>![PCI-DSS Architecture Board](./PCI-DSS_Tokenization_Architect_Board.jpg) | Decoupled CDE boundaries and ephemeral session state logic. |
| **TDEE Logic Workflow**<br>![TDEE Logic Workflow](./TDEE_Calculator_Logic_Workflow.jpg) | Algorithmic logic and conditional branching for metabolic calculations. |
| **Habit Engine Architecture**<br>![Habit App Architecture](./Habit_App_Logic_Architecture_Mabb.jpg) | Behavioral process model and data persistence flow. |

</details>

---

## Professional Profile & Contact

* **Email:** [jennie.mabb18@gmail.com](mailto:jennie.mabb18@gmail.com)
* **Location:** Virginia (Open to Remote & Hybrid roles)
* **Clearance / Trust:** Public Trust (U.S. Department of Justice)
* **Status:** Available for **GRC Analyst**, **Data Governance Analyst/Manager**, or **Compliance Architect** positions. Seeking roles where compliance architecture, data integrity, and process design drive organizational outcomes.
