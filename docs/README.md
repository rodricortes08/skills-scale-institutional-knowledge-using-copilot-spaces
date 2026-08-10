# OctoAcme Project Management Docs

## Quick Overview

OctoAcme follows an iterative, customer-first approach to project management with clear ownership, data-informed decisions, and psychological safety. Our processes span five lifecycle phases: initiation, planning, execution, release, and retrospective.

Each project has a named **Project Manager (PM)** who coordinates delivery, schedules, and communications, and a **Product Lead** who defines outcomes, prioritizes the backlog, and measures success. Cross-functional teams work iteratively to deliver small, testable increments that maximize customer value.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Documentation Index

### Getting Started

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level intro to roles, lifecycle, and key artifacts
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Detailed descriptions of Project Manager, Product Manager, Developer, and QA responsibilities

### Project Lifecycle Phases

The OctoAcme project management lifecycle consists of five key phases:

1. **[Initiation](./octoacme-project-initiation.md)** — Validate business need, align stakeholders, and create a lightweight plan
   - *Use this when*: A new project idea or feature proposal is ready to be explored
   - *Key deliverables*: Project One-pager, stakeholder list, high-level timeline, initial risk list

2. **[Planning](./octoacme-project-planning.md)** — Turn approved initiatives into actionable backlogs and timelines
   - *Use this when*: An initiative has been approved and needs detailed planning
   - *Key deliverables*: Prioritized backlog, release plan, Definition of Done, dependency map

3. **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, track progress, and maintain quality
   - *Use this when*: Your team is actively building and delivering work
   - *Key activities*: Daily standups, weekly syncs, PR reviews, automated testing, risk monitoring

4. **[Release & Deployment](./octoacme-release-and-deployment.md)** — Standardize releases to production and manage rollbacks
   - *Use this when*: Ready to ship features or fixes to production
   - *Key activities*: Pre-release checks, deployment, smoke tests, rollback procedures

5. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive improvements
   - *Use this when*: After each sprint, release, or significant milestone
   - *Key activities*: Reflect on what went well, identify improvements, track action items

### Cross-Cutting Concerns

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify, track, and communicate risks and dependencies
  - *Use this throughout*: All project phases, especially during planning and execution
  - *Key activities*: Risk register maintenance, stakeholder updates, escalation procedures

## Core Roles & Responsibilities

| Role | Primary Responsibilities | Key Goals |
|------|--------------------------|-----------|
| **Project Manager** | Coordinate delivery, manage schedules, risks, and communications | Deliver on time and within scope; maintain transparency |
| **Product Manager** | Define vision, prioritize backlog, measure outcomes | Maximize customer value; drive data-informed decisions |
| **Developer** | Implement features, write tests, participate in reviews | Deliver reliable code; reduce cycle time to production |
| **QA/Testing** | Validate quality and acceptance criteria | Ensure product reliability and user satisfaction |

For detailed descriptions of each role, see [Roles and Personas](./octoacme-roles-and-personas.md).

## Communication Cadence

- **Daily**: Team standups (15 min) — progress, blockers, dependencies
- **Weekly**: PM + PdM sync, delivery team standup, risk register review
- **Monthly**: Stakeholder updates and business reviews
- **Per milestone**: Sprint planning, demos, and retrospectives
- **Ad-hoc**: Escalations and incident communication

## Key Artifacts

Every OctoAcme project maintains:

- **Project Charter / One-pager** — Problem statement, objectives, success metrics
- **Roadmap and Release Plan** — Timelines, milestones, deliverables
- **Sprint/Iteration Backlog** — Prioritized work with acceptance criteria
- **Acceptance Criteria & Definition of Done** — Quality standards
- **Risk Register** — Tracked risks with mitigation plans
- **Retrospective Notes** — Learnings and action items

## How to Use These Docs

1. **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
2. **Kicking off a project?** Use the [Initiation Guide](./octoacme-project-initiation.md) and reference the [Roles and Personas](./octoacme-roles-and-personas.md)
3. **In active delivery?** Consult [Execution & Tracking](./octoacme-execution-and-tracking.md) for guidance on daily workflows and quality standards
4. **Managing risks?** Refer to [Risk Management & Communication](./octoacme-risks-and-communication.md) at any project phase
5. **Ready to release?** Follow the [Release & Deployment Guide](./octoacme-release-and-deployment.md)
6. **Reflecting and improving?** Use [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

### Tips for Success

- **Keep your Project Charter updated** in your project repo or project board
- **Reference the relevant process doc** based on your current project phase
- **Add process-specific docs to `.copilot/`** if you want Copilot Spaces to use them as context
- **Use templates from `.github/ISSUE_TEMPLATE/`** to standardize process improvements and updates
- **Review this README during team onboarding** to align all team members on OctoAcme's approach
