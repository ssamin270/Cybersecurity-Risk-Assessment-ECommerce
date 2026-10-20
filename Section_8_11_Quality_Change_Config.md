# Section 8: Quality Management Plan

## 8.1 Quality Management Approach
Quality management for the Cybersecurity Risk Assessment and Mitigation Strategy Implementation project ensures that all project deliverables meet academic standards, satisfy cybersecurity best practices, and align with recognized frameworks such as NIST CSF 2.0 and the ASD Essential Eight[cite: 1]. Quality is integrated throughout the project lifecycle through proactive quality assurance (QA) and structured quality control (QC) activities[cite: 1].

Quality Assurance (QA) focuses on NIST CSF 2.0 and ASD alignment, GitHub peer pull reviews, and standardized document formatting[cite: 1]. 

Quality Control (QC) focuses on deliverable review checklists, citation and reference checks, and consistency cross-checks across all team sections[cite: 1].

## 8.2 Quality Objectives & Standards
* Framework Alignment: All identified threats, risk scores, and recommended controls must map directly to established standards (NIST SP 800-30, NIST CSF 2.0, and ASD Essential Eight)[cite: 1].
* Consistency: Project deliverables must maintain strict terminology consistency across all sections (e.g., risk IDs, task names in WBS/Gantt, and RACI role assignments)[cite: 1].
* Completeness: Every high-priority risk in the risk register must have a corresponding mitigation strategy, assigned owner, and verification method[cite: 1].
* Academic Integrity: All literature, standards, and external frameworks must be cited using standard academic formatting[cite: 1].

## 8.3 Quality Metrics & Verification Matrix

Deliverable 1: Risk Register & Mitigation Strategy
* Quality Metric: Completeness & Framework Alignment[cite: 1]
* Acceptance Criteria: 100% of high and critical risks have an assigned mitigation, owner, and ASD/NIST alignment[cite: 1].
* Verification Method: Peer review by Person 3 & Person 4 prior to merging into main baseline[cite: 1].

Deliverable 2: WBS & Gantt Chart
* Quality Metric: Logical Flow & Task Interdependencies[cite: 1]
* Acceptance Criteria: Zero dangling tasks; all critical path items identified and aligned with scope[cite: 1].
* Verification Method: Review by Person 2 & Person 1 against scope statement[cite: 1].

Deliverable 3: Project Documentation
* Quality Metric: Consistency & Structural Clarity[cite: 1]
* Acceptance Criteria: Uniform formatting, zero typos, consistent asset names, and valid citations[cite: 1].
* Verification Method: Final group proofreading check prior to Session 11 submission[cite: 1].

Deliverable 4: GitHub Repository
* Quality Metric: Version Integrity[cite: 1]
* Acceptance Criteria: All section updates submitted via pull requests with clear commit messages[cite: 1].
* Verification Method: Audit of git log and commit history by Person 4[cite: 1].

---

# Section 9: Change Management Process

## 9.1 Change Control Framework
During the execution of this cybersecurity assessment, changes may arise from shifting assessment requirements, modified task deadlines, or refined scope definitions[cite: 1]. To prevent scope creep and ensure overall schedule integrity, all proposed changes must follow a formal Change Request Process[cite: 1].

Process Steps:
1. Submit Change Request (Any Member)[cite: 1]
2. Log Ticket in Jira & GitHub[cite: 1]
3. Conduct Impact Analysis on Schedule & Scope[cite: 1]
4. Team Review & Approval[cite: 1]
5. Update Project Plans & Baselines[cite: 1]

## 9.2 Change Control Workflow
1. Identification & Request: Any group member identifying a necessary change completes a Change Request (CR) ticket in Jira[cite: 1].
2. Impact Assessment: The team evaluates the proposed change regarding its impact on the project schedule, work distribution, document consistency, and assessment requirements[cite: 1].
3. Review & Decision: The group reviews the CR during the weekly meeting[cite: 1]. Minor changes require consensus among all four members[cite: 1]. Changes affecting project submission deadlines or core unit outcomes are escalated to the academic reviewer/facilitator[cite: 1].
4. Implementation & Tracking: Once approved, the change is applied to project deliverables, logged in the Change Log, and tracked in Jira and GitHub[cite: 1].

## 9.3 Change Log Record

Change Request 1 (CR-01):
* Date Requested: 12/Oct/2026
* Description of Change: Expand E-Commerce platform scope to include Multi-Factor Authentication (MFA) for Admin Portal[cite: 1].
* Requested By: Person 3
* Impact Analysis: Minor addition to Risk Register & Mitigation plan; no schedule impact[cite: 1].
* Status: Approved
* Approval Date: 14/Oct/2026

Change Request 2 (CR-02):
* Date Requested: 20/Oct/2026
* Description of Change: Adjust Gantt milestone for Risk Assessment completion[cite: 1].
* Requested By: Person 2
* Impact Analysis: Shifted task completion by 2 days; remaining tasks re-aligned[cite: 1].
* Status: Approved
* Approval Date: 21/Oct/2026

---

# Section 10: Configuration Management & Version Control (GitHub Framework)

## 10.1 Configuration Management Strategy
Configuration Management ensures that all project assets—including report documents, risk registers, diagram files, and presentation materials—are tracked, controlled, and version-managed systematically[cite: 1]. GitHub serves as the primary Configuration Management Tool for storing, updating, and merging team deliverables[cite: 1].

## 10.2 Repository Structure & Branching Strategy
To prevent overwriting files and ensure a single source of truth, the team follows a structured repository setup and feature-branch workflow[cite: 1]:

* main branch: Contains the latest, fully approved group project plan and final deliverables[cite: 1]. Direct commits to main are restricted.
* feature/person-1-overview: Scope statement, charter, overview, communication plan[cite: 1].
* feature/person-2-wbs-gantt: WBS diagrams, task schedules, and Gantt charts[cite: 1].
* feature/person-3-risk-raci: Risk register, risk matrix, and RACI responsibilities[cite: 1].
* feature/person-4-quality-change-config: Quality plan, change process, and configuration controls[cite: 1].

Workflow Description: Feature branches are updated independently by each assigned author. Once reviewed via Pull Request (PR), changes are merged directly into the main submission branch[cite: 1].

## 10.3 Version Control Guidelines & Commit Conventions
1. Commit Message Format: Members write clear, informative commit messages following standard formats:
   * feat(person-4): add quality management plan and metrics table
   * docs(person-4): finalize change management workflow diagram
2. Pull Requests (PR): When a member completes their assigned section, they submit a Pull Request to merge into main[cite: 1]. At least one other team member must review and approve the PR[cite: 1].
3. Document Versioning Scheme: Draft reports follow the semantic versioning standard:
   * Version 0.1: Initial section drafts.
   * Version 0.5: Integrated group draft for internal review[cite: 1].
   * Version 1.0: Final checked report for Session 11 submission[cite: 1].

---

# Section 11: Timeline Agreement & Key Project Assumptions

## 11.1 Key Project Assumptions
* E-Commerce Architecture Model: The system consists of a web frontend, cloud-hosted customer database, administrative management portal, and third-party payment gateway integration[cite: 1].
* Assessment Focus: Recommendations focus on high-impact administrative and technical controls (e.g., Multi-Factor Authentication, Patching, and Data Backups) appropriate for small-to-medium enterprises[cite: 1].
* Resource Availability: All four team members contribute equally and allocate required hours weekly toward research, documentation, and coordination[cite: 1].
* Non-Production Testing: No active penetration testing or live data extraction will be conducted on operational websites[cite: 1].

## 11.2 Key Agreed Timeline & Milestones

Milestone 1 (M1): Baseline Approval
* Target Date: Session 8
* Primary Responsible: Person 1
* Target Deliverables: Project Overview, Objectives, Charter, Scope Statement, Communication Plan[cite: 1].

Milestone 2 (M2): Schedule & Risk Baseline
* Target Date: Session 9
* Primary Responsible: Person 2 & Person 3
* Target Deliverables: WBS, Gantt Chart, Risk Register, RACI Matrix[cite: 1].

Milestone 3 (M3): Governance & Control Baseline
* Target Date: Session 10
* Primary Responsible: Person 4
* Target Deliverables: Quality Management Plan, Change Process, GitHub Configuration Strategy[cite: 1].

Milestone 4 (M4): Final Report Integration
* Target Date: Session 11
* Primary Responsible: All Members
* Target Deliverables: Combined Document Version 1.0, Jira Audit, GitHub Final Merge[cite: 1].

Milestone 5 (M5): Video Presentation
* Target Date: Session 12
* Primary Responsible: All Members
* Target Deliverables: Recorded Group Video Submission[cite: 1].
