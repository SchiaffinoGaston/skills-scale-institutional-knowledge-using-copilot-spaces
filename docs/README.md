# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. This folder contains the complete process guide for how OctoAcme runs projects from initiation through retrospective and continuous improvement.

## Quick Overview

OctoAcme follows a structured, lifecycle-based approach to project management grounded in five core principles: **customer-first delivery**, **iterative development**, **clear ownership**, **data-informed decisions**, and **psychological safety**. The organization manages projects through a defined five-phase lifecycle: Initiation, Planning, Execution, Release, and Retrospectives.

### Key Features of OctoAcme's Approach

**Roles & Accountability**: Clear roles—Project Manager (PM), Product Manager (PdM), Developers, QA/Testing, and Stakeholders—ensure transparent ownership and accountability across projects.

**Structured Workflows**: Every project moves through defined phases with specific deliverables, checklists, and decision gates. Work is tracked via GitHub Projects with standardized PR workflows (small PRs ≤400 lines, CI/CD validation, at least one approval before merge).

**Quality & Testing**: Unit tests, integration tests, end-to-end smoke tests, security scanning, and manual QA are embedded throughout execution. Release processes include pre-release checklists, smoke tests, and rollback plans.

**Risk & Communication**: A Risk Register is maintained and reviewed weekly. Communication follows a structured cadence (twice-weekly standups, weekly PM syncs, monthly stakeholder updates) with clear escalation paths (Team → PM → Product Lead → Sponsor) and standardized templates for status updates and incident communication.

**Continuous Improvement**: Retrospectives are held after each sprint, release, or milestone to capture learnings, identify improvements, and assign action items with clear owners and timelines. This commitment ensures consistent, repeatable execution while reducing dependency risk and accelerating onboarding.

---

## Documentation

Navigate through OctoAcme's complete project management process using the links below:

### 1. [Project Management Overview](octoacme-project-management-overview.md)
**Start here** — A concise introduction to OctoAcme's approach, roles, key artifacts, and communication cadence.

### 2. [Project Initiation Guide](octoacme-project-initiation.md)
Define the initial steps to validate and authorize work, align stakeholders, and create a lightweight plan. Includes the Project One-pager template and initiation checklist.

### 3. [Project Planning](octoacme-project-planning.md)
Turn an approved initiative into an actionable plan and backlog for delivery. Covers kickoff meetings, backlog creation, estimation, Definition of Done, and dependency management.

### 4. [Execution & Tracking](octoacme-execution-and-tracking.md)
Guidance for managing day-to-day execution and tracking progress toward milestones. Includes team rhythm (standups, syncs, demos), PR workflows, quality practices, and blocker escalation.

### 5. [Risk Management & Communication](octoacme-risks-and-communication.md)
Explain how to identify, manage, and communicate risks and dependencies. Covers Risk Register maintenance, stakeholder communication, and escalation paths.

### 6. [Release & Deployment Guide](octoacme-release-and-deployment.md)
Standardize how OctoAcme releases features to production. Includes release types, pre-release requirements, deployment checklists, and rollback procedures.

### 7. [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
Capture learnings and convert them into actionable improvements. Includes retrospective structure, tracking improvements, and building a continuous improvement culture.

### 8. [Roles and Personas](octoacme-roles-and-personas.md)
Detailed definitions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities, goals, and communication patterns.

---

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) for a quick orientation.
- **Starting a new project?** Follow the path: Initiation → Planning → Execution → Release → Retrospective.
- **Looking for a specific topic?** Use the links above or search for keywords across all docs.
- **Contributing updates?** See the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.

---

## Key Principles

1. **Customer-first**: Prioritize customer value and usability.
2. **Iterative delivery**: Deliver small, testable increments.
3. **Clear ownership**: Each project has a named PM and PdM.
4. **Data-informed decisions**: Measure impact and iterate based on evidence.
5. **Psychological safety**: Encourage feedback and learning.

---

## Core Roles at a Glance

| Role | Responsibility |
|------|-----------------|
| **Project Manager (PM)** | Coordinates delivery, schedules, risk, and communications |
| **Product Manager (PdM)** | Defines outcomes, prioritizes backlog, and measures success |
| **Developers** | Implement features, collaborate on design and testability |
| **QA/Testing** | Validate quality and acceptance criteria |
| **Stakeholders** | Provide inputs and approvals |

For detailed personas, see [Roles and Personas](octoacme-roles-and-personas.md).

---

## Communication Cadence

- **Weekly PM + PdM Sync**: Strategic alignment and priority
- **Twice-weekly Team Standups**: Progress, blockers, dependencies
- **Monthly Stakeholder Updates**: High-level status and outcomes
- **Ad-hoc Escalations**: Risk and blocker management

---

## Questions?

- Check the relevant process doc for detailed guidance
- Review past project charters and retrospectives in the repository
- Reach out to the Project Manager or Product Lead for clarification
