# OctoAcme Project Management Docs

## Quick Overview
OctoAcme follows an iterative, customer-first approach to project management with clear ownership, data-informed decisions, and psychological safety. Projects move through five primary phases—initiation, planning, execution, release, and retrospective—with a focus on delivering small, testable increments and validating outcomes through measurable success metrics.

Work is organized on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and managed through a disciplined pull-request and CI workflow: small PRs when possible, explicit acceptance criteria and issue links in PR descriptions, automated tests and lint gates in CI, and at least one required approval before merging. Planning converts approved initiatives into prioritized, estimable backlogs and release plans; risks and cross-team dependencies are captured in a Risk Register and surfaced during regular syncs.

Roles and responsibilities are explicitly defined to ensure clear ownership across delivery: Project Managers coordinate schedules, risks, and communications; Product Managers define outcomes and prioritize work; Developers implement and test code; QA validates acceptance criteria and quality; stakeholders provide direction and approvals. This role clarity supports predictable delivery, reduces single-person dependency risk, and makes escalation paths explicit (Team → PM → Product Lead → Sponsor).

Quality assurance and release discipline are built into the lifecycle. QA practices include unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when needed. Releases require passing CI/security scans, drafted release notes, rollback/mitigation plans, and post-deploy verifications; an incident playbook and rollback guidance are in place to manage production issues and follow-on retrospectives.

## Core Principles
- Customer-first: prioritize customer value and usability  
- Iterative delivery: deliver small, testable increments  
- Clear ownership: each project has a named PM and Product Lead  
- Data-informed decisions: measure impact and iterate based on evidence  
- Psychological safety: encourage feedback and learning

## Documentation Index

### Getting Started
- [Project Management Overview](./octoacme-project-management-overview.md) — High-level intro to roles, lifecycle, and key artifacts  
- [Roles and Personas](./octoacme-roles-and-personas.md) — Detailed role descriptions and responsibilities

### Project Phases
1. [Initiation](./octoacme-project-initiation.md) — Validate business need, align stakeholders, create a lightweight plan  
2. [Planning](./octoacme-project-planning.md) — Turn approved initiatives into actionable backlogs and timelines  
3. [Execution & Tracking](./octoacme-execution-and-tracking.md) — Manage day-to-day delivery, PR workflow, and tracking  
4. [Release & Deployment](./octoacme-release-and-deployment.md) — Standardize releases and rollback procedures  
5. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive improvements

### Cross-Cutting Concerns
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify, track, and communicate risks and dependencies

## Quick Navigation Guide
- You are starting a project? Read the Initiation doc and fill the Project One-pager.  
- Preparing to plan work? See Planning for backlog templates, estimates, and Definition of Done.  
- Actively delivering? Use Execution & Tracking for day-to-day workflows, PR guidance, and reporting.  
- Releasing to production? Follow Release & Deployment checklists and smoke-test guidance.  
- After delivery or incident? Run a Retrospective and add action items to the backlog.

## Core Roles Summary
- Project Manager (PM): coordinates delivery, schedules, risks, and stakeholder communication.  
- Product Manager (PdM): defines problem statements, success metrics, and backlog priorities.  
- Developers: implement features, write tests, and participate in reviews and design discussions.  
- QA/Testing: validate acceptance criteria, run test plans, and confirm release readiness.  
- Stakeholders: provide inputs, approvals, and business context.

## Communication Cadence
- Daily: Team standups (15 min) — progress, blockers, dependencies  
- Weekly: PM + PdM sync; delivery team check-ins; risk review  
- Monthly: Stakeholder updates and status summaries  
- Per milestone: Sprint planning, demos, and retrospectives

## How to Use These Docs
- Keep the Project Charter / One-pager updated in your project repo.  
- Reference the doc that matches your current lifecycle phase.  
- Add process-specific artifacts to `.copilot/` if you want Copilot Spaces to use them as context.  
- Use the ISSUE_TEMPLATE in `.github/ISSUE_TEMPLATE/` to propose changes to these process docs.
