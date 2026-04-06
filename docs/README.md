# OctoAcme Project Management Docs

Welcome to the OctoAcme project management process documentation. This folder contains the core process documents and a concise overview of how OctoAcme runs projects so team members and stakeholders can quickly find and use the practices that support reliable, repeatable delivery.

OctoAcme organizes delivery around a clear, iterative lifecycle that moves work from initiation through planning, execution, release, and retrospective. Projects begin with a lightweight Project One-pager that captures the problem, measurable goals, stakeholders, and success metrics; the Decision Gate moves work into planning once success metrics and stakeholder buy-in are confirmed. Planning breaks approved initiatives into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release/milestone map. The team uses a project board (Backlog → Ready → In Progress → In Review → QA → Done) to manage flow and surface dependencies.

Day-to-day execution follows a CI- and Pull Request-driven workflow: small PRs where possible, each PR links to its issue and acceptance criteria, and automated tests and linting run in CI before review. Required approvals are enforced for merging; deployments follow release notes and rollback plans when needed. Reporting and dashboards surface velocity and key signals (errors, latency, usage) and regular demos/reviews at the end of sprints or milestones validate outcomes against success metrics.

Roles and responsibilities are explicit to make ownership clear: Product Managers set vision and success metrics; Project Managers coordinate schedules, risks, and communications; Developers implement features and tests; QA validates acceptance criteria; and stakeholders provide input and approvals. Quality assurance and risk management are built into the process: unit and integration tests, smoke tests before release, security scanning in CI, and a simple Risk Register with clear escalation paths. Continuous improvement is formalized through retrospectives that produce action items tracked back into the backlog.

## Process Document Links

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risks and Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## Acceptance Criteria

- Content aligns with the existing process docs in this folder.
- Provides a clear entry point and summary that improves discoverability and onboarding.
- Contains direct links to every process document found in this directory.
