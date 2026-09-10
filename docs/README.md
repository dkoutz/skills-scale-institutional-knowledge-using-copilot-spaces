# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management documentation hub. This directory contains the process guides used to run projects at OctoAcme — from initiation through retrospective and continuous improvement. Use this README as your starting point to discover roles, workflows, templates, and checklists that help teams deliver reliably and iterate on outcomes.

OctoAcme organizes work around a lifecycle of Initiation, Planning, Execution, Release, and Close/Retrospective. Each stage is supported by lightweight artifacts (Project One-pager, prioritized backlog, Risk Register) and clear working agreements. Day-to-day execution is driven from a project board (Backlog, Ready, In Progress, In Review, QA, Done) with sprint planning and a Definition of Done to ensure items are shippable. The process emphasizes iterative delivery, measurable outcomes, and explicit ownership so teams can move quickly while managing risk.

Roles and responsibilities are defined so each project has clear accountability: Product Managers set outcomes and prioritize work; Project Managers coordinate schedules, risks, and communications; Developers implement and test changes; and QA validates acceptance criteria. Pull request conventions encourage small, focused PRs (≤400 lines), link to issues and acceptance criteria, and require automated CI checks and at least one approval before merging. Cross-functional collaboration is reinforced through templates, acceptance criteria, and assigned owners for risks and action items.

Quality and release practices are embedded in the workflow. Teams maintain unit and integration tests, run end-to-end smoke tests for critical flows, and include security scanning in CI. Releases follow a checklist-driven process: pre-release verification, staging smoke tests, automated production pipelines where possible, and a documented rollback/incident playbook. Retrospectives are timeboxed and produce 2–3 prioritized action items that are tracked in the backlog or as issues.

## Documentation Index

### Foundation & Overview
- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, and key artifacts. Start here if you're new.
- [Roles & Personas](octoacme-roles-and-personas.md) — Definitions of Project Manager, Product Manager, Developer, QA, and other key roles.

### Project Lifecycle Stages
- [Project Initiation Guide](octoacme-project-initiation.md) — Validate ideas, align stakeholders, and create a one-pager to launch new projects.
- [Project Planning](octoacme-project-planning.md) — Turn an approved initiative into an actionable backlog, timeline, and release plan.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Daily standups, sprint management, quality standards, and blocker escalation.
- [Release & Deployment](octoacme-release-and-deployment.md) — Standardized release process, pre-release checklist, and rollback procedures.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings, track action items, and drive iterative process improvements.

### Cross-Cutting Concerns
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Maintain a risk register, communicate with stakeholders, and escalate issues effectively.

## How to Use These Docs

- For new projects: Start with the Project Initiation Guide, then move to Project Planning to create your backlog and timeline.
- For delivery teams: Reference Execution & Tracking for sprint workflows and Risk Management & Communication for status updates.
- For releases: Use Release & Deployment as your checklist and playbook.
- For improvement: Run retrospectives after each sprint or milestone and track action items in the backlog or as issues.

## Key Principles

- Customer-first: Prioritize customer value and usability
- Iterative delivery: Deliver small, testable increments
- Clear ownership: Every project has a named PM and Product Lead
- Data-informed: Measure impact and iterate based on evidence
- Psychological safety: Encourage feedback and learning

## Communication Cadence

- Daily standups (delivery team)
- Weekly PM + Product Manager sync
- Twice-weekly standups for delivery teams (as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## Need Help?
If you can't find what you're looking for in these docs:
1. Check the index above
2. Search within individual documents in the docs/ folder
3. Reach out to your Project Manager or Product Lead

---

*This README was added in response to issue #2 to provide a central entry point for OctoAcme's project management processes.*
