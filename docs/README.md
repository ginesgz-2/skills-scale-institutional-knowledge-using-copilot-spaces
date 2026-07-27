# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs. This folder contains standardized processes, checklists, and guidance for managing projects from initiation through retrospective and continuous improvement.

## About OctoAcme Project Management

OctoAcme runs projects using a **customer-first, iterative approach** with clear ownership, data-informed decisions, and psychological safety. Our methodology balances structure with flexibility to deliver value incrementally while maintaining stakeholder alignment.

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Management Overview

OctoAcme follows a structured, five-phase project lifecycle that begins with **Initiation** and culminates in **Close & Retrospective**. During initiation, the team validates business needs, identifies stakeholders, and produces a lightweight Project One-pager defining the problem, goal, and success metrics. Once approved, the project moves into **Planning**, where work is broken into shippable increments, acceptance criteria are defined, and dependencies are mapped. Execution follows a disciplined approach using GitHub Projects boards with columns (Backlog, Ready, In Progress, In Review, QA, Done) and emphasizes small pull requests (≤400 lines) with mandatory CI checks and at least one approval before merging. Finally, **Release & Deployment** is governed by pre-release checklists, staging verification, and rollback procedures, while **Retrospectives** capture learnings and convert them into actionable improvements tracked in the project backlog.

OctoAcme operates with clearly defined personas that eliminate ambiguity around ownership: the **Project Manager (PM)** coordinates delivery, manages schedules, risks, and communications; the **Product Manager (PdM)** defines outcomes, prioritizes the backlog, and measures success; **Developers** implement features, write tests, and participate in design reviews; and **QA/Testing** validates quality and acceptance criteria. The organization maintains a consistent communication cadence with weekly syncs between PM and PdM, twice-weekly standups for the delivery team (or as agreed), monthly stakeholder updates, and ad-hoc escalations following a three-level path: team-level triage → PM escalation to Product Lead → sponsor-level escalation.

Quality is embedded throughout the OctoAcme workflow rather than treated as a gate. The team implements unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance when needed. Risk management is equally systematic: risks are captured in a Risk Register (with ID, description, impact, likelihood, owner, and mitigation plan), identified during planning and ongoing execution, assessed for severity, mitigated through proactive actions, and monitored at weekly syncs. This combination of continuous quality practices, proactive risk identification, and structured communication creates accountability while reducing surprises and escalations.

## Documentation Map

### Getting Started
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, core roles, key artifacts, and project lifecycle
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed descriptions of Project Managers, Product Managers, Developers, QA, and other key roles

### Project Phases
1. **[Project Initiation](octoacme-project-initiation.md)** — Validate business need, align stakeholders, create One-pager, decide go/no-go
2. **[Project Planning](octoacme-project-planning.md)** — Break work into increments, estimate scope, define DoD, identify dependencies
3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Daily standups, team rhythm, PR workflow, quality standards, blocker escalation
4. **[Release & Deployment](octoacme-release-and-deployment.md)** — Release types, pre-release requirements, deployment checklist, rollback procedures
5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings, track action items, measure improvements

### Cross-Cutting Concerns
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk register, escalation paths, stakeholder communication templates

## Quick Reference: Project Lifecycle at a Glance

| Phase | Key Deliverables | Owner |
|-------|------------------|-------|
| Initiation | One-pager, Stakeholder alignment, Go/no-go decision | PM + Product Lead |
| Planning | Prioritized backlog, DoD, Release plan, Risk register | PM + Team |
| Execution | Daily standups, PRs, testing, demos | Team + PM |
| Release | Release notes, deployment, announcement | PM + Ops |
| Retrospective | Learnings, action items, improvements | PM + Team |

## Key Artifacts by Phase

- **Project Charter / One-pager** — Problem statement, goal, success metrics, stakeholders, timeline
- **Roadmap and Release Plan** — High-level timeline and milestone map
- **Sprint/Iteration Backlog** — Prioritized work with acceptance criteria and estimates
- **Definition of Done** — Clear standards for what "complete" means
- **Risk Register** — Tracking ID, description, impact, likelihood, owner, and mitigation
- **Release Notes** — Release name, date, summary, notable changes, migration steps
- **Retrospective Notes** — What went well, improvements, action items with owners and due dates

## How to Use These Docs

- **New to a project?** Start with the [Project Management Overview](octoacme-project-management-overview.md) and [Roles & Personas](octoacme-roles-and-personas.md).
- **Starting a new project?** Follow the [Initiation](octoacme-project-initiation.md) and [Planning](octoacme-project-planning.md) guides.
- **In execution?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md).
- **Preparing for release?** Use the [Release & Deployment](octoacme-release-and-deployment.md) guide.
- **Wrapping up?** Follow the [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) process.
- **Managing cross-team dependencies?** Refer to [Risk Management & Communication](octoacme-risks-and-communication.md) for escalation paths and stakeholder templates.

## Communication Cadence

- **Daily**: Standups (15 min) — focus on progress, blockers, dependencies
- **Weekly**: PM + PdM sync — alignment on priorities and risks
- **Twice-weekly** (or as agreed): Delivery team standups
- **Monthly**: Stakeholder updates and status reports
- **As-needed**: Ad-hoc escalations via the escalation path (Team → PM → Product Lead → Sponsor)

## Contributing to These Docs

These documents are living artifacts. To suggest updates, improvements, or new content, open an issue using the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.

When contributing, ensure:
- Content aligns with existing process docs
- Updates improve clarity or close a documented gap
- Proposed content has been reviewed with stakeholders (if needed)

---

**Last Updated**: This README was created to centralize OctoAcme project management knowledge and improve discoverability for new team members and Copilot Spaces integration.
