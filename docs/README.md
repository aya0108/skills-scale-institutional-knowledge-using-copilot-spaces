# OctoAcme Project Management Docs

## Overview

OctoAcme operates a structured, lifecycle-driven project management approach designed around five key phases: Initiation, Planning, Execution, Release, and Close & Retrospective. The methodology is grounded in customer-first principles, iterative delivery, clear ownership, and data-informed decision-making. At its foundation, OctoAcme emphasizes psychological safety and transparent communication, with named Project Managers (PMs) and Product Managers (PdMs) accountable for coordinating delivery and defining outcomes respectively.

This documentation hub serves as a central navigation point for all OctoAcme project management processes, ensuring consistent governance, artifact tracking, and quality gates across all cross-functional projects—whether delivering product features, services, or integrations.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle & Navigation

### 1. Initiation
**Purpose**: Validate business need and gain stakeholder alignment

A Project One-pager is completed to confirm business need, identify stakeholders, and establish success metrics before a go/no-go decision is made.

**[→ Read: Project Initiation Guide](./octoacme-project-initiation.md)**

### 2. Planning
**Purpose**: Create an actionable backlog and delivery plan

Work is broken into shippable increments with a prioritized backlog, acceptance criteria, Definition of Done, and a risk register that captures dependencies and mitigation strategies.

**[→ Read: Project Planning](./octoacme-project-planning.md)**

### 3. Execution & Tracking
**Purpose**: Execute delivery with daily oversight and risk management

Work is managed through GitHub Projects with columns (Backlog, Ready, In Progress, In Review, QA, Done), supported by daily standups, weekly delivery syncs, and small pull requests that require automated tests, linting, and approvals before merging.

**[→ Read: Execution & Tracking](./octoacme-execution-and-tracking.md)**

### 4. Release & Deployment
**Purpose**: Safely deploy features to production

Pre-deployment requirements include passing CI/security scans, smoke tests, and rollback plans, followed by production verification and stakeholder announcements.

**[→ Read: Release & Deployment Guide](./octoacme-release-and-deployment.md)**

### 5. Retrospective & Continuous Improvement
**Purpose**: Capture learnings and drive continuous improvement

After each sprint or milestone, teams conduct structured retrospectives to capture learnings and track action items with clear owners and timelines.

**[→ Read: Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)**

## Cross-Cutting Topics

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies throughout all phases
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Understand key project roles and responsibilities
- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to the OctoAcme approach

## Key Roles

| Role | Responsibility |
|------|-----------------|
| **Project Manager (PM)** | Coordinates delivery, manages schedules, risks, and communications |
| **Product Manager (PdM)** | Defines outcomes, prioritizes backlog, and measures success |
| **Developers** | Implement features, collaborate on design, and maintain tests |
| **QA/Testing** | Validate quality and acceptance criteria |
| **Stakeholders** | Provide inputs and approvals |

## Communication Cadence

- **Weekly sync** between PM + PdM
- **Twice-weekly standups** for delivery team (or as agreed)
- **Monthly stakeholder updates**
- **Ad-hoc escalations** as needed

## Quality Assurance Practices

Quality is embedded across the delivery pipeline:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Quick Start

**New to OctoAcme projects?**
1. Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a high-level summary
2. Then navigate to the phase-specific guide that matches your current project stage
3. Reference [Roles & Personas](./octoacme-roles-and-personas.md) to understand team responsibilities

**Looking for a specific answer?**
- Planning a new project? → [Project Initiation](./octoacme-project-initiation.md)
- Managing risks or blockers? → [Risk Management & Communication](./octoacme-risks-and-communication.md)
- Ready to release? → [Release & Deployment](./octoacme-release-and-deployment.md)
- Wrapping up? → [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## Contributing to Process Docs

To propose updates or new content for these process documents, open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
