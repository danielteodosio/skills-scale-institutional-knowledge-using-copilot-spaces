# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas (requested update)

The following personas expand accountability and clarify handoffs across design, delivery, operations, security, and support.

### Delivery Lead (Technical Project Lead)

Role Summary
- Day-to-day technical coordination and delivery execution for a project or major feature.

Responsibilities
- Coordinate technical tasks across engineers and ensure work aligns with acceptance criteria
- Identify and remove engineering blockers; escalate scheduling conflicts to the PM
- Drive technical implementation decisions in collaboration with engineering stakeholders
- Track technical progress and risk, and communicate status in delivery syncs

Interactions
- Works closely with the Project Manager for timeline and dependency coordination
- Partners with Developers on implementation details and with QA for release readiness
- Coordinates with the Engineering Manager on resourcing and technical risks

---

### Engineering Manager

Role Summary
- People management and technical leadership responsible for team health, capacity, and code quality.

Responsibilities
- Capacity planning and resourcing decisions
- Performance reviews, mentoring, and career development for engineers
- Participate in technical design reviews and help manage technical debt
- Escalate and mitigate technical risks that impact delivery

Interactions
- Aligns with PM/PdM on resourcing and hiring needs
- Works with Delivery Lead and Developers on technical direction and staffing
- Engages with QA and SRE where cross-cutting technical concerns exist

---

### UX Researcher / Designer

Role Summary
- Owns user research, interaction design, accessibility checks, and design validation.

Responsibilities
- Run user research and usability testing to validate assumptions
- Produce interaction and visual designs and provide clear handoffs to engineering
- Ensure accessibility and inclusive design requirements are met
- Participate in acceptance criteria for usability and UX outcomes

Interactions
- Partners with PdM on requirements and success criteria
- Works with Developers to clarify implementation details and with QA on usability tests
- Shares research findings with stakeholders to inform prioritization

---

### Observability / Monitoring Owner

Role Summary
- Defines and maintains metrics, dashboards, and alerting for features and services.

Responsibilities
- Define key metrics and SLIs/SLOs tied to product success
- Create dashboards and alerting rules; maintain runbooks for common alerts
- Validate instrumentation and telemetry during implementation and after releases

Interactions
- Works with Developers and SRE to instrument systems and ensure metrics are reliable
- Partners with PdM and Data Analyst on success metrics and measurement approaches
- Notifies PM/Release Manager when post-release signals indicate regressions

---

### Release Manager

Role Summary
- Coordinates the release process, communication, and rollback/runbook ownership.

Responsibilities
- Schedule release windows and coordinate dependencies across teams
- Maintain release runbooks, rollback plans, and communications templates
- Coordinate pre-release checks (smoke tests, migrations, backup) and post-release verifications

Interactions
- Works with PM, Delivery Lead, SRE/DevOps, and QA to confirm readiness
- Coordinates stakeholder and support communications with Customer Success and Support reps
- Triggers incident response and escalation as needed post-release

---

### Security Liaison

Role Summary
- Primary cross-functional contact for security reviews, threat modeling, and triage.

Responsibilities
- Conduct security reviews and threat modeling for features
- Triage security findings and track remediation with engineering
- Ensure features meet compliance requirements and notify Legal/Compliance when required

Interactions
- Works with Developers, SRE, and Security teams to fix vulnerabilities
- Escalates high-impact risks to the Product Lead and PM for prioritization
- Coordinates with Legal/Compliance Liaison on regulatory requirements

---

### Data Analyst / Measurement Owner

Role Summary
- Owns definition and validation of success metrics and instrumentation.

Responsibilities
- Define analytical metrics and ensure data capture for success criteria
- Validate data quality and implement dashboards or reports for stakeholders
- Run analyses to inform product decisions and post-release impact reviews

Interactions
- Partners with PdM on success metrics and hypothesis definition
- Works with Developers and Observability Owner to implement telemetry
- Shares findings with PM and stakeholders to guide prioritization

---

### Customer Success / Support Representative

Role Summary
- Connects customer feedback and support signals back to product and delivery teams.

Responsibilities
- Surface customer feedback, recurring issues, and feature requests
- Define and maintain support escalation paths and runbook feedback
- Validate user-facing documentation and runbooks from a support perspective

Interactions
- Feeds input to PM/PdM and coordinates with Release Manager for customer communications
- Works with Technical Writer to ensure support-facing docs are accurate
- Participates in post-release triage when customers report issues

---

### Technical Writer / Documentation Owner

Role Summary
- Owns user-facing documentation, runbooks, and internal guides.

Responsibilities
- Produce and maintain release notes, runbooks, README updates, and user docs
- Ensure documentation follows accessibility and clarity standards
- Coordinate doc reviews with developers and support teams before release

Interactions
- Works across Developers, PM, and Support to publish accurate documentation
- Partners with Release Manager to ensure docs are updated as part of releases

---

### Site Reliability Engineer (SRE) / DevOps Owner

Role Summary
- Owns deployment pipelines, infra automation, reliability engineering, and on-call practices.

Responsibilities
- Build and maintain CI/CD pipelines and infrastructure as code
- Define runbooks and remediation steps for operational incidents
- Operate on-call rotations and perform post-incident reviews

Interactions
- Works with Developers and Delivery Lead to ensure safe rollouts
- Partners with Release Manager on deployment scheduling and rollback
- Coordinates with Observability Owner to ensure monitoring and alerts are effective

---

### Legal / Compliance Liaison (when applicable)

Role Summary
- Provides legal and compliance guidance on features with regulatory or contractual impact.

Responsibilities
- Review features for data protection, contractual obligations, and regulatory requirements
- Advise on contract language, data handling, and necessary approvals
- Escalate compliance risks and required controls to Product Lead and stakeholders

Interactions
- Engages with PdM and Security Liaison to ensure compliance needs are integrated early
- Works with PM to schedule required reviews and approvals before release

---

## How these additions improve outcomes
- Clear accountability reduces delays and finger-pointing.
- Faster onboarding: new hires can see explicit role responsibilities.
- Better handoffs between design, build, release, and support.
- Improved observability, security posture, and measurement of success.

---

## Suggested next steps
1. Review and iterate this section with PM, PdM, Engineering Management, Security, and Support representatives.
2. Link these personas to relevant process docs (planning, execution, release) for cross-reference.
3. Add owner and contact fields to personas in future updates if helpful for larger organizations.
