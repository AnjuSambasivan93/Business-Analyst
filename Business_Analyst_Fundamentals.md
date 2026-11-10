# Business Analyst (BA) 

## 1. What is Business Analysis?

Business Analysis is the process of identifying business problems, understanding business needs, and recommending solutions.

A **Business Analyst (BA)** acts as a bridge between business stakeholders and technical teams.

### Main Responsibilities
- Understand business problems.
- Gather and document requirements.
- Analyse existing business processes.
- Identify areas for improvement.
- Communicate with stakeholders.
- Support solution development and testing.
- Ensure the final solution meets business needs.

**Example:**

Problem: Employees manually prepare reports every week.

Solution: Introduce an automated reporting system.

BA's role: Understand the reporting requirements, document them, and work with the development team to implement a solution.

---

## 2. Requirements Gathering

Requirements gathering means collecting information about what stakeholders need.

### Common Techniques
- **Interviews:** Ask stakeholders questions.
- **Workshops:** Discuss requirements with a group.
- **Observation:** Watch how employees perform tasks.
- **Surveys:** Collect information through questionnaires.
- **Document Analysis:** Review existing documents and processes.

### Types of Requirements

**Functional Requirements**

Describe what a system should do.

Examples:
- Users can log in.
- Users can download reports.
- The system generates monthly reports.

**Non-Functional Requirements**

Describe how well a system should work.

Examples:
- Reports should load within 3 seconds.
- The system should be secure.
- The system should be available 99.9% of the time.

---

## 3. Stakeholder Analysis

A stakeholder is anyone who affects or is affected by a project.

Examples:
- Customers
- Employees
- Managers
- Developers
- Project Managers
- Business Owners

### Stakeholder Analysis Steps
1. Identify stakeholders.
2. Understand their needs.
3. Identify their influence and interest.
4. Plan how to communicate with them.

**Example:**

For a reporting system:
- Manager: Needs accurate reports.
- Employee: Wants to reduce manual work.
- Developer: Needs clear technical requirements.

---

## 4. Business Process Mapping

Process mapping is a visual representation of how work is completed.

### As-Is Process

Shows how a process currently works.

Example:

`Collect Data → Clean Data → Prepare Excel Report → Email Manager`

### To-Be Process

Shows how the improved process should work.

Example:

`Collect Data Automatically → Validate Data → Generate Dashboard → Manager Views Report`

**Purpose:** Identify unnecessary steps, delays, and opportunities for improvement.

### Tool
- Microsoft Visio
- diagrams.net (Draw.io)
- Lucidchart

---

## 5. BPMN (Business Process Model and Notation)

BPMN is a standard method for drawing business process diagrams.

### Basic BPMN Symbols

| Symbol | Meaning |
|---|---|
| Circle | Start or End Event |
| Rounded Rectangle | Task or Activity |
| Diamond | Decision or Gateway |
| Arrow | Sequence Flow |
| Pool / Lane | Participant or Responsibility |

### Example

`Start → Receive Request → Check Details → Approved? → Process Request → End`

A decision gateway can create different paths, such as Approved and Rejected.

**Tool to practise:** diagrams.net

---

## 6. Gap Analysis

Gap Analysis compares the current situation with the desired future situation.

**Formula:**

`Current State → Identify Gap → Future State`

### Example

| Current State | Desired State | Gap |
|---|---|---|
| Manual reporting | Automated reporting | No automation |
| Reports take 3 hours | Reports take 10 minutes | Slow process |
| Data stored in Excel | Centralised database | Data integration needed |

### Steps
1. Understand the current process.
2. Define the desired process.
3. Identify differences.
4. Recommend improvements.

---

## 7. User Stories

A user story describes a requirement from the user's perspective.

### Format

**As a [user], I want [feature], so that [benefit].**

### Example

As a manager, I want to download monthly reports so that I can monitor business performance.

### Acceptance Criteria

Acceptance criteria define the conditions that must be met for a user story to be accepted.

Example:
- The manager can select a month.
- The system generates the report.
- The report can be downloaded as a PDF.
- The report contains accurate information.

---

## 8. Agile Methodology

Agile is an approach to project delivery where work is completed in small stages, with regular feedback and improvements.

### Main Concepts

- **Sprint:** A short, fixed period of work.
- **Product Backlog:** A prioritised list of work.
- **Sprint Planning:** Selecting work for a sprint.
- **Daily Scrum:** A short meeting to inspect progress and adjust the plan.
- **Sprint Review:** Demonstrating completed work and collecting feedback.
- **Sprint Retrospective:** Discussing improvements to teamwork and processes.

### Scrum Roles
- Product Owner
- Scrum Master
- Developers

### Example

Sprint 1: Develop login functionality.

Sprint 2: Develop reporting functionality.

Sprint 3: Develop dashboard functionality.

---

## 9. Jira

Jira is a project management tool commonly used in Agile projects.

### Main Concepts
- **Epic:** A large piece of work.
- **User Story:** A requirement from the user's perspective.
- **Task:** A specific activity.
- **Bug:** A problem in the system.
- **Sprint:** A fixed period for completing selected work.
- **Backlog:** A prioritised list of work.

### Example

Epic: Reporting System

User Story: As a manager, I want to download reports.

Task: Create the report download feature.

Bug: Download button is not working.

---

## 10. Confluence

Confluence is a documentation and team collaboration tool.

### Common Uses
- Document business requirements.
- Store meeting notes.
- Create project documentation.
- Record decisions.
- Share information with teams.

### Example Documents
- Business Requirements Document (BRD)
- Functional Requirements Document (FRD)
- Process Maps
- Meeting Notes
- Risk Register

---

## 11. Business Requirements Document (BRD)

A BRD describes the business needs and objectives of a project.

### Basic Structure
1. Project Overview
2. Business Problem
3. Project Objectives
4. Stakeholders
5. Business Requirements
6. Project Scope
7. Assumptions and Constraints
8. Risks
9. Success Criteria

### Example

**Project:** Automated Reporting System

**Problem:** Manual report preparation takes too much time.

**Objective:** Reduce reporting time.

**Requirement:** The system must automatically generate weekly reports.

**Success Criteria:** Reduce report preparation time from 3 hours to 10 minutes.

---

## 12. User Acceptance Testing (UAT)

UAT is testing performed by business users or their representatives to check whether a solution meets business needs.

### Steps
1. Review business requirements.
2. Prepare test scenarios.
3. Execute test cases.
4. Record results.
5. Report defects.
6. Retest after fixes.
7. Obtain business acceptance.

### Example

Requirement: Users should be able to download reports.

Test:
1. Log in.
2. Open the reports page.
3. Select a report.
4. Click Download.
5. Verify that the correct file downloads.

Expected Result: The report downloads successfully with accurate data.

---

## 13. Risk Analysis

Risk Analysis identifies possible problems that could affect a project.

### Example

| Risk | Impact | Mitigation |
|---|---|---|
| Missing requirements | High | Conduct stakeholder reviews |
| Project delays | Medium | Monitor progress regularly |
| Data errors | High | Implement data validation |
| Poor user adoption | Medium | Provide training |

---

## 14. Business Case and Options Analysis

A business case explains why a project or proposed solution is worth pursuing.

### Main Components
- Business problem
- Proposed solution
- Expected benefits
- Estimated costs
- Risks
- Alternative options
- Recommendation

### Example

Problem: Manual reporting is slow.

Option 1: Continue using Excel.

Option 2: Develop an automated reporting system.

Recommendation: Choose automation if the expected benefits justify the cost and risks.

---

## 15. Service Design

Service Design focuses on creating services that meet user needs and deliver better outcomes.

### Main Concepts
- Understand users and their needs.
- Map the customer or user journey.
- Identify problems in service delivery.
- Design improved services.
- Test proposed solutions with users.
- Continuously improve services.

### Example

A family support organisation wants to improve its service request process.

The BA:
1. Interviews service users and staff.
2. Maps the existing process.
3. Identifies delays and difficulties.
4. Works with stakeholders to design improvements.
5. Tests whether the new process meets user needs.

---

## 16. Important BA Tools

| Tool | Purpose |
|---|---|
| Jira | Agile project and task management |
| Confluence | Requirements and project documentation |
| Microsoft Visio | Process mapping |
| diagrams.net | Free process mapping and BPMN |
| Excel | Gap analysis, requirements tracking, risk registers |
| Miro | Workshops, brainstorming, journey mapping |
| Microsoft Word | Business documents and reports |
| Power BI | Data analysis and business reporting |

---

## 17. Business Analyst Project Lifecycle

A simplified BA workflow:

`Identify Problem → Identify Stakeholders → Gather Requirements → Analyse Processes → Design Solution → Support Development → UAT → Implementation → Review Outcomes`

### BA Responsibilities at Each Stage

| Stage | BA Responsibility |
|---|---|
| Discovery | Understand business problems |
| Requirements | Gather and document needs |
| Analysis | Identify gaps and improvement opportunities |
| Design | Help define suitable solutions |
| Development | Clarify requirements |
| Testing | Support UAT |
| Implementation | Support change and user adoption |
| Review | Check whether business objectives were achieved |

---

## 18. Important BA Terms to Remember

| Term | Simple Meaning |
|---|---|
| Stakeholder | Person or group involved in a project |
| Requirement | Something the business needs |
| BRD | Business Requirements Document |
| FRD | Functional Requirements Document |
| BPMN | Business Process Model and Notation |
| As-Is | Current process |
| To-Be | Future improved process |
| Gap Analysis | Difference between current and desired states |
| User Story | Requirement from a user's perspective |
| Acceptance Criteria | Conditions required for acceptance |
| UAT | User Acceptance Testing |
| Backlog | Prioritised list of work |
| Sprint | Short, fixed work period |
| KPI | Key Performance Indicator |
| Scope | What is included or excluded from a project |
| Dependency | Something that relies on another task or condition |
| Change Management | Helping people and organisations adopt changes |

---

**Remember:**

A Business Analyst focuses on understanding **WHAT the business needs, WHY it needs it, and HOW to improve the process or service**.
