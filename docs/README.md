# OctoAcme Documentation

Welcome to the OctoAcme project management documentation. This folder contains comprehensive guides for running structured, customer-focused projects from initiation through retrospective.

## Quick Start

If you're new to OctoAcme's project management approach, start with the **[Project Management Overview](./octoacme-project-management-overview.md)** for a high-level introduction to our principles, roles, and key artifacts.

## Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The methodology spans five key phases:

### 1. **Initiation**
Teams validate the business need and create a lightweight Project One-pager defining the problem statement, success metrics, and stakeholders. This gates the decision to move into planning, where teams confirm sponsor alignment and resource availability. See **[Project Initiation Guide](./octoacme-project-initiation.md)** for details.

### 2. **Planning**
Work is broken into shippable increments with prioritized backlogs, acceptance criteria, release timelines, and a Definition of Done. Teams identify dependencies, risks, and integration points during this phase. See **[Project Planning](./octoacme-project-planning.md)** for the full planning process.

### 3. **Execution**
Execution is coordinated through a structured team rhythm including daily standups (15 minutes), weekly delivery syncs, and sprint-based iterations tracked on GitHub Projects. Small pull requests (≤400 lines) flow through a standardized workflow requiring at least one approval, automated CI testing, and linting before merge. Quality assurance is embedded throughout—unit tests, integration tests, end-to-end smoke tests, and security scanning all run in CI, with manual QA for feature acceptance as needed. See **[Execution & Tracking](./octoacme-execution-and-tracking.md)** for workflows and quality standards.

### 4. **Release**
Release and deployment follow a standardized process designed to reduce risk. All acceptance criteria must be met, CI must pass, security scans complete, and a rollback plan documented before deployment. Teams deploy to staging for smoke tests, then to production using automated pipelines when possible, followed by post-deploy verification and stakeholder announcement. See **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** for the full process.

### 5. **Close & Retrospective**
After each sprint, release, or milestone, retrospectives capture learnings (what went well, what could improve) and convert them into prioritized action items tracked in the backlog. This continuous improvement cycle, combined with blameless incident retrospectives, ensures OctoAcme evolves its practices based on real experience. See **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** for how to run effective retrospectives.

## Core Roles & Responsibilities

Three core roles drive delivery at OctoAcme:

- **Project Managers** coordinate schedules, risks, and cross-team communication
- **Product Managers** define outcomes, prioritize the backlog, and measure success
- **Developers** implement features while collaborating on design and testability

For detailed persona descriptions, see **[Roles and Personas](./octoacme-roles-and-personas.md)**.

## Communication & Risk Management

A weekly PM-PdM sync, twice-weekly standups, and monthly stakeholder updates form the communication backbone, supplemented by escalation paths for blockers (team-level → PM → Product Lead → Sponsor).

Risk management is continuous, with a Risk Register capturing ID, description, impact, likelihood, owner, and mitigation plan—reviewed at every weekly sync. See **[Risk Management & Communication](./octoacme-risks-and-communication.md)** for escalation paths, communication templates, and incident protocols.

## Document Index

| Document | Purpose |
|----------|----------|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme principles, roles, and artifacts |
| [Project Initiation Guide](./octoacme-project-initiation.md) | Validation, stakeholder alignment, and authorization for new projects |
| [Project Planning](./octoacme-project-planning.md) | Breaking work into shippable increments and creating actionable backlogs |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day execution, team rhythm, quality standards, and metrics |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk identification, escalation paths, and stakeholder communication |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Standardized release process, deployment checklist, and rollback procedures |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capturing learnings and converting them into actionable improvements |
| [Roles and Personas](./octoacme-roles-and-personas.md) | Detailed definitions of typical roles and responsibilities |

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Getting Help

- Use these docs as your source of truth for process and best practices
- Reference the templates and checklists when planning, executing, or retrospecting
- If you notice gaps or opportunities to improve these docs, create an issue using the **[Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template
