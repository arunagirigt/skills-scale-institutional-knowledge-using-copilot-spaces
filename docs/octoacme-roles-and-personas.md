# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It also expands the set of personas to include cross-functional specialists that improve clarity and accountability in modern delivery teams.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## UX Designer (new)

### Role Summary
UX Designers are responsible for ensuring the product is usable, accessible, and meets user needs through research, design, and validation.

### Responsibilities
- Conduct lightweight user research and usability testing
- Create user flows, wireframes, and prototypes
- Produce accessible and consistent designs (design system artifacts)
- Provide design specs and acceptance criteria for implementation
- Participate in sprint reviews to validate delivered UX

### Interactions
- Works with Product Managers to translate user needs into prioritized requirements
- Handoffs design artifacts and acceptance criteria to Developers and QA
- Collaborates with Data Analysts to define usability metrics
- Engages Project Manager to ensure design milestones are scheduled

### Accountability
- Responsible for design artifacts being complete for development (covering user flows, acceptance criteria, and accessibility considerations)

---

## DevOps / Platform Engineer (new)

### Role Summary
DevOps or Platform Engineers enable reliable delivery by managing CI/CD, infrastructure, and monitoring.

### Responsibilities
- Build and maintain CI/CD pipelines, deployment automation, and test environments
- Define runbooks and rollback procedures for releases
- Ensure infrastructure as code and environment parity across stages
- Monitor system health and provide alerts and observability guidance
- Assist in incident response and post-mortem analysis

### Interactions
- Works with Developers to ensure builds and releases are automated and testable
- Partners with Project Manager and Product Manager to schedule deploy windows and validate release readiness
- Coordinates with Security Lead for secure configuration and vulnerability fixes

### Accountability
- Accountable for pipeline reliability, deployment documentation, and operational readiness of releases

---

## Support / Customer Success (new)

### Role Summary
Support and Customer Success functions act as the frontline for users, capturing feedback and escalating product-impacting issues.

### Responsibilities
- Triage user reports, reproduce issues or collect context for engineering
- Maintain and update user-facing documentation and FAQs
- Escalate bugs and feature requests to Product and Project teams with priority and impact
- Provide release notes and customer communication where applicable
- Track and communicate recurring user patterns and product gaps

### Interactions
- Reports operational/user issues to Developers and Project Managers
- Works with Product Managers to inform prioritization based on customer impact
- Participates in release readiness and post-release validation efforts

### Accountability
- Accountable for the quality of customer communications and the completeness of issue reports for triage

---

## Security Lead (new)

### Role Summary
Security Leads ensure systems meet organizational security standards and help manage risk throughout the lifecycle.

### Responsibilities
- Perform threat modeling and architecture security reviews for new features
- Run security scanning and triage findings
- Define and communicate security acceptance criteria
- Lead incident response coordination for vulnerabilities and breaches
- Ensure compliance with relevant policies and regulatory requirements

### Interactions
- Works with Developers and DevOps for secure implementations and fixes
- Advises Product and Project Managers on security trade-offs and timelines
- Coordinates escalations with stakeholders during security incidents

### Accountability
- Accountable for security review completion and tracking remediation of critical findings

---

## Data Analyst (new)

### Role Summary
Data Analysts define measurement, interpret data, and provide insight to guide product decisions and demonstrate success.

### Responsibilities
- Define key metrics and instrumentation requirements early in planning
- Build dashboards and reports to monitor feature performance and health
- Support hypothesis validation through A/B analysis and cohort analysis
- Provide actionable insights to Product Managers and Developers

### Interactions
- Works with Product Managers to tie success metrics to business objectives
- Collaborates with Developers and DevOps to ensure data collection and pipeline reliability
- Shares findings during planning, reviews, and retrospectives

### Accountability
- Accountable for the accuracy and timeliness of the metrics used to make product decisions

---

## How these personas interact

- Handoffs: Product defines the problem and acceptance criteria → UX designs the user experience → Devs implement → QA validates → DevOps deploys → Support handles users and closes the loop with Product.
- Cross-functional ceremonies: All applicable personas should attend kickoffs, relevant planning, demos, and retrospectives. Not every role needs to be present for every meeting; presence should be defined per milestone.
- RACI (recommended): For each key deliverable (e.g., release, security review, instrumentation), add a RACI table in the project One-pager to clarify who is Responsible / Accountable / Consulted / Informed.

---

## Using these personas in exercises and onboarding

- Reference these expanded personas when creating Project One-pagers and putting together "Proposed team / roles".
- Add role-specific checklists (see docs/process-checklists.md) to ensure handoffs and responsibilities are explicit and repeatable.
