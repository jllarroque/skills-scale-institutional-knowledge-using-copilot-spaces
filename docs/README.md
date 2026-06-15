# OctoAcme Project Management Docs

Welcome to the OctoAcme project management process documentation. This README serves as a single entry point for project managers, developers, product leads, and contributors to understand and navigate OctoAcme's structured, iterative approach to project delivery.

## What is OctoAcme?

OctoAcme is a documented project management methodology centered on **customer value**, **clear ownership**, **iterative delivery**, and **continuous improvement**. The approach spans five key phases—Initiation, Planning, Execution, Release, and Close & Retrospective—with defined roles, communication cadences, and quality standards at each stage.

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager (PM) and Product Lead roles
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Overview

Based on the comprehensive documentation in this repository, OctoAcme employs a structured, iterative approach to project delivery grounded in customer value and data-driven decision-making. The organization follows a clear **lifecycle** that spans five phases: Initiation, Planning, Execution, Release, and Close & Retrospective. During **Initiation**, teams validate business needs and align stakeholders around a Project One-pager that defines the problem, goals, success metrics, and resource requirements. Once approved, the **Planning** phase breaks work into prioritized, estimated backlog items with clear acceptance criteria and a Definition of Done. This foundation ensures teams move into execution with aligned timelines, identified dependencies, and documented risks.

**Execution and delivery** form the operational heart of OctoAcme projects. Teams follow a rhythm of daily 15-minute standups focused on progress and blockers, weekly delivery syncs to review milestones and escalate risks, and regular demos at sprint or milestone boundaries. Work is tracked on a project board using a standardized workflow (Backlog → Ready → In Progress → In Review → QA → Done), with small pull requests (≤400 lines when possible) and mandatory code reviews before merging. Quality assurance is integrated throughout: unit tests, integration tests, security scanning in CI, and end-to-end smoke tests for critical flows. Teams also maintain a living Risk Register and track velocity and key success metrics to inform weekly decision-making.

**OctoAcme's organizational structure** assigns clear ownership to three core roles: the **Project Manager** (PM) coordinates schedules, risks, and communications; the **Product Manager** (PdM) owns outcomes, prioritization, and success measurement; and **Developers** collaborate with leadership on implementation and technical risk mitigation. This separation of concerns is reinforced by a regular communication cadence—weekly PM-PdM syncs, twice-weekly team standups, and monthly stakeholder updates—paired with a documented escalation path (Team → PM → Product Lead → Sponsor) to ensure blockers are surfaced and resolved quickly. When projects complete, teams conduct structured retrospectives to capture learnings and convert them into actionable improvements, creating a continuous feedback loop that strengthens future delivery.

## Quick Start: Project Lifecycle

1. **Initiation** → Validate business need, align stakeholders, define success metrics
2. **Planning** → Break work into shippable increments, identify dependencies, create release timeline
3. **Execution** → Build, test, review; track progress via daily standups and project board
4. **Release** → Deploy to production, verify, announce to stakeholders
5. **Close & Retrospective** → Capture learnings, convert to actionable improvements

## Documentation

### Phase-Specific Guides

- **[Project Management Overview](octoacme-project-management-overview.md)** — Foundational introduction to OctoAcme's principles, roles, artifacts, and lifecycle
- **[Project Initiation](octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, create lightweight plan
- **[Project Planning](octoacme-project-planning.md)** — Turn approved initiatives into actionable backlog, estimate scope, define Definition of Done
- **[Execution and Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythm, workflows, quality standards, and blocker escalation
- **[Release and Deployment](octoacme-release-and-deployment.md)** — Standardized release process, pre-release requirements, deployment checklist, rollback procedures
- **[Risks and Communication](octoacme-risks-and-communication.md)** — Risk Register management, stakeholder communication templates, escalation paths

### Supporting Guides

- **[Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — How to run effective retrospectives and convert learnings into improvements
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed descriptions of Project Manager, Product Manager, and Developer roles and responsibilities

## Key Artifacts & Templates

Throughout these docs you'll find templates and checklists for:
- **Project One-pager** — Problem, goal, success metrics, stakeholders, timeline, risks
- **Backlog Item Template** — Title, description, acceptance criteria, priority, estimate, owner
- **Risk Register** — ID, description, impact, likelihood, owner, mitigation, status
- **Definition of Done** — Quality and acceptance standards before work is marked complete
- **Release Notes Template** — Version, date, summary, notable changes, migration steps, known issues
- **Weekly Status Template** — Progress, next steps, risks/blockers, decisions needed
- **Action Item Template** — Title, description, owner, due date, success criteria

## Team Roles

OctoAcme uses three primary roles (see [Roles and Personas](octoacme-roles-and-personas.md) for details):

- **Project Manager (PM)** — Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)** — Defines outcomes, prioritizes backlog, measures success
- **Developers** — Implement features, collaborate on design, write tests, identify technical risks

## Communication Cadence

- **Daily** — 15-minute standups (progress, blockers, dependencies)
- **Twice-weekly** — Team delivery syncs (or as agreed)
- **Weekly** — PM + PdM alignment sync
- **Weekly** — Risk review and project board updates
- **Monthly** — Stakeholder updates
- **Sprint/Milestone boundary** — Demo/Review and retrospective
- **Ad-hoc** — Escalations and incident communication

## How to Use These Docs

1. **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md)
2. **Starting a new project?** Follow the path: Initiation → Planning → Execution → Release
3. **Managing risks or communication?** Refer to [Risks and Communication](octoacme-risks-and-communication.md)
4. **Continuous improvement?** Use [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
5. **Need a template?** Look for the specific phase guide or artifact list above

## Contributing to These Docs

To propose updates, clarifications, or new content:
1. Open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. Describe the gap, rationale, and suggested content
3. Reference relevant stakeholders for alignment

---

**Last Updated:** June 2026  
**Maintained by:** OctoAcme Project Management Team
