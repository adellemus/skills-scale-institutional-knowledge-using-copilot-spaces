# OctoAcme Project Management Docs

This folder contains the operating guidance for OctoAcme's project lifecycle. The documents are designed to help teams initiate work, plan delivery, track execution, manage risks, release changes safely, and improve the process over time.

OctoAcme manages work through a structured lifecycle: initiate and validate the problem, plan scope and milestones, execute in iterative delivery cycles, release with verification and rollback readiness, and close with a retrospective. The project charter and one-pager help align stakeholders and define the business goal, success metrics, and timeline before a team commits to delivery. Once approved, planning breaks work into a prioritized backlog with acceptance criteria, estimates, responsibilities, dependencies, and a Definition of Done so the team can move from idea to implementation with clarity.

The process is grounded in clear ownership and repeatable communication. Core roles include the Project Manager, Product Manager, developers, QA/testing, and stakeholders, each with distinct responsibilities for planning, prioritization, implementation, validation, and decision-making. Teams use daily or twice-weekly standups, PM/Product syncs, milestone reviews, and stakeholder updates to keep work visible, escalate blockers early, and maintain a shared source of truth. Risks, dependencies, and decisions are tracked so issues can move from team-level triage to product and sponsor escalations when necessary.

Quality is built into delivery rather than treated as a final step. New work should include unit tests, integration coverage where relevant, and smoke tests for high-impact flows before release. CI validates linting, automated checks, and security scans, and manual QA is used when acceptance needs human confirmation. Before a deployment, the team verifies acceptance criteria, prepares release notes, confirms rollback readiness, and performs post-deploy checks to reduce operational risk. After each sprint, release, or major milestone, the team documents learnings in a retrospective and converts action items into backlog work or issue tracking to drive continuous improvement.

## Documentation Index

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md) — high-level summary of the lifecycle, principles, roles, artifacts, and communication cadence.
- [OctoAcme — Project Initiation Guide](octoacme-project-initiation.md) — how to validate ideas, align stakeholders, and create the initial plan and one-pager.
- [OctoAcme — Project Planning](octoacme-project-planning.md) — how to turn an approved initiative into a backlog, milestones, and release plan.
- [OctoAcme — Execution & Tracking](octoacme-execution-and-tracking.md) — day-to-day project operations, tracking practices, quality gates, and escalation paths.
- [OctoAcme — Risk Management & Communication](octoacme-risks-and-communication.md) — risk register, communication templates, and stakeholder escalation guidance.
- [OctoAcme — Release & Deployment Guide](octoacme-release-and-deployment.md) — pre-release checks, deployment process, rollback playbooks, and release documentation.
- [OctoAcme — Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — how to capture lessons, assign improvements, and sustain a learning culture.
- [OctoAcme Personas](octoacme-roles-and-personas.md) — role definitions for developers, product managers, and project managers used in the exercise and docs.

## Related resources

- [Project management overview](octoacme-project-management-overview.md)
- [Issue template for process doc updates](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
