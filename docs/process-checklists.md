# OctoAcme — Process Checklists (Role-focused)

This file collects short, actionable checklists to reduce handoff friction and make responsibilities explicit.

## Design Handoff Checklist (UX → Dev)
- [ ] User flows and key edge cases documented
- [ ] Wireframes / prototypes accessible in the repo or design tool with links
- [ ] Acceptance criteria and success metrics included
- [ ] Accessibility requirements documented
- [ ] Design assets and tokens exported or referenced in the repo
- [ ] Data instrumentation needs listed (events, properties, dashboards)

## Deployment Checklist (Dev/DevOps)
- [ ] All PRs merged and green in CI
- [ ] Smoke tests defined and passing in staging
- [ ] Runbook includes rollback steps and contact list
- [ ] Monitoring/dashboards configured for new feature signals
- [ ] Communication plan for stakeholders and Support
- [ ] Post-deploy verification tasks assigned and timeboxed

## Support / Customer Success Handover (Pre-release)
- [ ] Support has preview access to staging if needed
- [ ] Known limitations and workarounds documented
- [ ] FAQs and release notes drafted
- [ ] Escalation path and on-call assignment shared
- [ ] Expected user impact and monitoring thresholds communicated

## Security Review Checklist (Security Lead)
- [ ] Threat model or security considerations updated for the feature
- [ ] Static analysis and dependency checks completed and triaged
- [ ] Secrets and credential handling validated
- [ ] Compliance requirements (if any) documented
- [ ] Mitigations and acceptance criteria defined for any remaining findings

## Data & Instrumentation Checklist (Data Analyst)
- [ ] Events and metrics defined with owners
- [ ] Dashboards and alerts created for success and failure signals
- [ ] Data retention and privacy considerations documented
- [ ] QA of events verified in staging before release

## How to use these checklists
- Add the relevant checklist(s) as a linked doc in the Project One-pager or the related issue/PR.
- Mark items as done during planning and again as part of release verification.
