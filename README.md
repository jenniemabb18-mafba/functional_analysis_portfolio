# Jennie Mabb | Management & Process Analysis Portfolio
A collection of architectural blueprints and data migration specifications focusing on structural logic, auditability, and stakeholder-driven design.

Jennie Mabb, M.S.
Senior Management Analyst | Process & Data Integrity Specialist
Specializing in Requirements Elicitation, Strategic Architecture, and Operational Governance

A results-driven Analyst with 15+ years of experience in high-security federal (DOJ) and international financial (ABN AMRO) environments. I specialize in the 'Structural Integrity of Information' — bridging the gap between complex business needs and technical execution through meticulous documentation and logical modeling.

I leverage a Master of Science in Mental Health Counseling to provide advanced stakeholder elicitation, conflict resolution, and human-centered design, ensuring that technical systems are built to serve the mission and the user.

🛠 Strategic Deliverables & Case Studies
### [Functional Requirements Design (NTS)](./NTS_Functional_Requirements_Design.pdf)
The Objective: Transform a manual driver education process into a secure, cloud-based platform.

Key Deliverable: Authored a 100+ point Functional Requirements Document (FRD) covering system logic, performance benchmarks, and security protocols.

Focus Areas: Role-Based Access Control (RBAC), Data Auditing, and Plain-Language Technical Writing.

### [Strategic Architectural Analysis](./Software_Design_Project_Mabb.pdf)
The Objective: Evaluate design constraints for transitioning local gaming environments to distributed web-based platforms.

Key Deliverable: Developed a platform recommendation white paper comparing Linux, Windows, and MacOS environments for scalability and cost-efficiency.

Focus Areas: Platform Evaluation, Distributed Systems, and Kotlin/Cross-platform strategy.

### [Regulatory Compliance] 
[GDPR White Paper](/White_Paper_ANN_GDPR_Mabb.pdf)
The Objective: Analyze the impact of international privacy laws on Artificial Neural Networks (ANN) and personalization engines.

Key Deliverable: A formal analysis of "Privacy by Design," addressing Right to Erasure and Data Portability within automated systems.

Focus Areas: GDPR, International Data Privacy Law, and Risk Mitigation.

[Stateless_Tokenization_Handshake](./PCI-DSS_Tokenization_Architect_Board.jpg)
Objective: To implement a stateless cryptographic engine that secures transaction validation without persisting Sensitive Authentication Data (SAD).

Key Deliverables: Development of a cryptographic randomizer for generating short-lived ephemeral Dynamic CVVs (dCVVs). Implementation of transient session state management that enforces a 90-second expiration policy.

Focus Areas: PCI DSS v4.0.1 Compliance: Strict enforcement of the prohibition against storing SAD post-authorization. Data Minimization (GDPR): Ensuring tokens exist only in ephemeral volatile memory, leaving no footprint for auditors to scrub.

[Prescriptive_CDE_and_Logical_Mapping_Layer](./PCI-DSS_Tokenization_Architect_Board.jpg)
Objective: To design a decoupled database schema that minimizes the PCI DSS audit footprint by isolating sensitive financial data.

Key Deliverables: Identity Vault (Table 1): A secure layer for PII, mapped to random surrogate keys (UID). Account Mapping Layer (Table 2): A translation bridge between customer profiles (UID) and card indices (CCid). Prescriptive CDE (Table 3): A hardened vault containing encrypted PANs, designed as the primary audit boundary.

Focus Areas: Compliance Scoping: Partitioning data to ensure Table 1 and Table 2 remain OUT OF SCOPE, while hardening Table 3 as the MAXIMUM IN-SCOPE environment. Pseudonymization (GDPR Article 32): Utilizing decoupled tokenization to safeguard personal relationship links between users and their financial data.

Additional Artifacts: (./PCI-DSS_GDPR_Compliance_Translation_Matrix.pdf) and (./PCI-DSS_GDPR_Compliance_Translation_Matrix_Scope.pdf) for notations on the Architect Board.

### [Database Architecture & Migration Spec](./MySQL_Data_Integrity_and_Migration_Specification_Mabb.pdf)
The Objective: Oversee a large-scale database overhaul involving 37,994 records and structural renaming.

Key Deliverable: Documented a full migration path in MySQL, focusing on Referential Integrity and data type standardization to prevent loss during transformation.

Focus Areas: SQL (MySQL), Relational Logic, and Audit-Ready Record Verification.

### [UML System Logic & UX Modeling](./NTS_UML_System_Designs_Mabb.pdf)
The Objective: Visualize "Actor" interactions and complex system workflows to prevent operational bottlenecks.

Key Deliverable: Developed Sequence Diagrams, Activity Maps, and UI Logic Workflows for inventory and task management systems.

Focus Areas: UML Modeling, Decision Logic, and User Experience (UX) Strategy.

Core Competencies
Methodology: SDLC, Agile Requirements Gathering, Operational Diagnostics.

Technical Literacy: SQL (MySQL), UML Modeling (Lucid/Visio), System Architecture Analysis.

Interpersonal: Advanced Clinical Elicitation, Stakeholder Management, Conflict De-escalation.

Professional Contact
Email: jennie.mabb18@gmail.com
Location: Virginia (Remote-preferred)
Eligibility: Public Trust (DOJ)

Additional Designs: 
![PCI-DSS_Architecture_Board](./PCI-DSS_Tokenization_Architect_Board.jpg)
![TDEE Logic Workflow](./TDEE_Calculator_Logic_Workflow.jpg)
![Habit App Architecture](./Habit_App_Logic_Architecture_Mabb.jpg)
