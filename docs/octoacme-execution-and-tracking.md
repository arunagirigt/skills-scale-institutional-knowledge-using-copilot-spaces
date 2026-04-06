# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone
- Design reviews / handoff checkpoints when designs are non-trivial
- Post-release verification session with Support and Product (first 48–72 hours)

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)
- Design handoff:
  - UX provides design specs, assets, and acceptance criteria in a linked doc/PR
  - Developer acknowledges design and raises feasibility questions before work starts
- Deployment coordination:
  - DevOps owns automated pipelines; Developers & Project Manager coordinate deploy windows and post-deploy checks
- Support handover:
  - Support creates triage tickets and maintains a support backlog; recurring issues are reviewed in weekly syncs for prioritization

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- Verify instrumentation and dashboards before feature launch (Data Analyst)

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)
- Add post-release health checks for at least the first 72 hours

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues
- Security incidents: follow Security Lead escalation path and incident runbook

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Design assets and acceptance criteria are linked in the related issue/PR
- [ ] Deployment runbook and rollback steps documented and tested
- [ ] Post-release verification tasks assigned (Support / QA / Data)
