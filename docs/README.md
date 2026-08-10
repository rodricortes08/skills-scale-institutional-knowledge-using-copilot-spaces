# OctoAcme Project Management Docs

## Quick Overview
OctoAcme follows an iterative, customer‑first project management approach that emphasizes clear ownership, measurable outcomes, and small, testable increments. Projects move through five lifecycle phases—initiation, planning, execution, release, and retrospective—with lightweight artifacts created at each stage to align stakeholders and guide delivery.

## Key Workflows
- Initiation: Capture problem statement, success metrics, stakeholders, and a one‑pager to authorize planning.
- Planning: Run kickoff, build a prioritized backlog with acceptance criteria, estimate work, and document a Definition of Done.
- Execution & Tracking: Manage work on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and use a PR workflow with CI/lint gates and at least one approval before merge.
- Release & Deployment: Require passing CI/security scans, staged smoke tests, release notes, and rollback plans; follow post‑deploy verifications and incident playbooks.
- Retrospective & Continuous Improvement: Capture learnings, create action items, and track improvements in the backlog.

## Personas & Core Responsibilities
- Project Manager (PM): Coordinates delivery, risk, timelines, and cross‑team communication.
- Product Manager (PdM): Defines outcomes, prioritizes the backlog, and measures success.
- Developers: Implement features, write tests, and participate in code/design reviews.
- QA/Testing: Validate acceptance criteria with unit/integration/smoke testing and manual verification where needed.
- Stakeholders: Provide inputs, approvals, and domain guidance.

## Communication Cadence
- Daily: Team standups (15 min) to surface progress and blockers.
- Weekly: PM + PdM sync, delivery team sync, and risk review.
- Monthly: Stakeholder updates.
- Per milestone: Sprint planning, demos/reviews, and retrospectives.

## Documentation Index
- octoacme-project-management-overview.md — High-level intro to roles, lifecycle, and key artifacts  
- octoacme-project-initiation.md — Validate business need and create an initial plan  
- octoacme-project-planning.md — Backlog, estimations, and release planning  
- octoacme-execution-and-tracking.md — Day‑to‑day execution, PR conventions, and CI expectations  
- octoacme-risks-and-communication.md — Risk register, escalation paths, and templates  
- octoacme-release-and-deployment.md — Release types, checklists, and rollback playbook  
- octoacme-retrospective-and-continuous-improvement.md — Retrospectives and tracking improvements  
- octoacme-roles-and-personas.md — Detailed role descriptions and responsibilities

## How to use these docs
- Start with the phase that matches your current work (Initiation → Planning → Execution → Release → Retrospective).
- Keep the Project Charter / One‑pager updated in your project repo as the single source of truth.
- Use the .github/ISSUE_TEMPLATE forms to request doc updates or add new process content.
