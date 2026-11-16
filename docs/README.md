# OctoAcme Project Management Docs

A central entry point to OctoAcme's project management guidance.

## Project management processes at a glance

OctoAcme manages work through a lightweight, iterative lifecycle. Projects begin by validating the business need, aligning stakeholders, and agreeing on measurable outcomes. Approved initiatives are planned into prioritized, estimable work with acceptance criteria, milestones, dependencies, and risks. Teams execute in small increments, track progress on a project board, test and review changes, and communicate status and blockers regularly. Releases follow readiness checks, deployment verification, and rollback planning. After sprints, releases, milestones, or incidents, teams capture lessons and track improvement actions.

### People and responsibilities

The Project Manager (PM) coordinates delivery, schedules, risks, dependencies, and communication. The Product Manager (PdM) defines outcomes, prioritizes work, and measures success. Developers build and test the solution, QA validates quality and acceptance criteria, and stakeholders provide input and approvals. Clear ownership and collaboration help teams deliver customer value in manageable increments.

### Communication and quality

Teams use regular check-ins and shared sources of truth, such as a project board, README, or release document, to make progress, risks, blockers, and decisions visible. The exact cadence is agreed by the team and may include daily standups, PM–PdM alignment, stakeholder updates, and demos. Risks and dependencies are tracked with owners and mitigation plans; blockers are escalated from the team through the PM and Product Lead to the sponsor when needed.

Quality is part of each delivery stage. Teams write unit tests for new logic, add integration tests where applicable, and run end-to-end smoke tests for critical flows. Automated tests, linting, and security scans run in CI; pull requests include acceptance criteria and receive review before merging. Before release, teams confirm acceptance criteria and CI checks, prepare release notes and rollback plans, test in staging, and verify production deployments. Retrospectives turn experience into a small set of owned, trackable improvements.

## Process documents

- [Project Management Overview](octoacme-project-management-overview.md) — principles, roles, artifacts, lifecycle, and communication cadence.
- [Project Initiation Guide](octoacme-project-initiation.md) — validate and authorize new work, align stakeholders, and prepare a one-pager.
- [Project Planning](octoacme-project-planning.md) — turn approved work into a prioritized backlog, release plan, and risk/dependency approach.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — team rhythm, project-board workflow, quality practices, reporting, and blocker escalation.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — identify, assess, mitigate, monitor, and communicate risks and dependencies.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — release readiness, deployment checks, verification, and rollback/incident response.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — capture learnings and track actionable improvements.
- [Roles and Personas](octoacme-roles-and-personas.md) — responsibilities, goals, and communication patterns for Developers, Product Managers, and Project Managers.

## Related docs

- [Project System Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
