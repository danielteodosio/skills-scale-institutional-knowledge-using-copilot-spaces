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

## Delivery Lead (Technical Project Lead)

### Role Summary
The Delivery Lead focuses on the day-to-day coordination of technical tasks and delivery details to keep implementation on track.

### Responsibilities
- Coordinate technical tasks and sprints with Developers
- Remove technical blockers or escalate them appropriately
- Ensure implementation aligns with acceptance criteria and DoD
- Track technical dependencies and sequencing

### Interactions
- Works closely with Project Manager for scheduling and dependency management
- Partners with Developers and Engineering Manager on technical decisions and capacity
- Coordinates with QA to ensure readiness for testing

---

## Engineering Manager

### Role Summary
Engineering Managers are responsible for people management, team capacity, technical quality, and long-term engineering health.

### Responsibilities
- Manage hiring, performance, and coaching for the engineering team
- Capacity planning and resource allocation
- Drive technical quality, code review standards, and long-term architecture decisions
- Identify and mitigate technical risks

### Interactions
- Aligns with Product Manager and Project Manager on resourcing and timelines
- Mentors Developers and provides input during planning and retrospectives
- Coordinates with SRE/DevOps on reliability and operational needs

---

## UX Researcher / Designer

### Role Summary
Design and UX research ensure the product meets user needs and is usable and accessible.

### Responsibilities
- Conduct user research and usability testing
- Create and validate designs and user flows
- Provide design assets and specifications for implementation
- Ensure accessibility and usability criteria are defined

### Interactions
- Partners with Product Manager to define user requirements and acceptance criteria
- Handoffs designs to Developers and supports implementation clarifications
- Works with QA on usability-based acceptance tests

---

## Observability / Monitoring Owner

### Role Summary
Owns the definition of success metrics, monitoring, and alerting to ensure production health and instrumentation quality.

### Responsibilities
- Define key metrics and SLOs for features
- Create and maintain dashboards and alerts
- Validate instrumentation and telemetry during development and after release
- Support post-release monitoring and incident analysis

### Interactions
- Works with Product Manager on success metrics and measurement needs
- Partners with Developers and SRE to implement telemetry
- Provides dashboards and signals to Project Manager and stakeholders

---

## Release Manager

### Role Summary
Coordinates releases across teams, owns runbooks and rollback plans, and ensures smooth deployments.

### Responsibilities
- Plan and schedule release windows
- Produce and maintain release runbooks and rollback procedures
- Coordinate cross-team release readiness and communications
- Trigger incident/rollback processes if needed

### Interactions
- Coordinates closely with Project Manager, SRE/DevOps, and Developers
- Notifies Stakeholders and Support/Customer Success about release impact and timing
- Works with QA to validate release readiness

---

## Security Liaison

### Role Summary
Acts as the primary contact for security reviews, threat modeling, and triage of security findings.

### Responsibilities
- Conduct security reviews and threat modeling for features
- Triage security findings and track remediation
- Ensure compliance and secure defaults are applied
- Escalate high-risk issues to Product Lead and relevant stakeholders

### Interactions
- Works with Developers and SRE to remediate findings
- Advises Product Manager on security-related trade-offs
- Coordinates with Legal/Compliance when necessary

---

## Data Analyst / Measurement Owner

### Role Summary
Defines how success is measured and ensures the product is instrumented to capture reliable data.

### Responsibilities
- Define success metrics and KPIs for features
- Specify instrumentation requirements and validate data quality
- Analyze post-release data to evaluate outcomes
- Support A/B testing and experimentation when applicable

### Interactions
- Partners with Product Manager on metric definitions and targets
- Works with Developers and Observability Owner to implement telemetry
- Provides analysis and insights to Project Manager and stakeholders

---

## Customer Success / Support Representative

### Role Summary
Represents customer-facing perspectives, surfaces customer feedback, and defines support/operational needs.

### Responsibilities
- Triage and escalate customer-reported issues
- Provide input on customer impact and use cases
- Validate documentation and runbooks from a support perspective
- Coordinate communications to customers when needed

### Interactions
- Feeds customer insights to Product Manager and Project Manager
- Works with Release Manager on customer-facing announcements
- Collaborates with Technical Writer for support documentation

---

## Technical Writer / Documentation Owner

### Role Summary
Ensures user-facing and operational documentation is accurate, accessible, and up-to-date.

### Responsibilities
- Produce and maintain user guides, runbooks, and README files
- Ensure documentation is reviewed during release and handoffs
- Coordinate documentation updates with Developers and Support

### Interactions
- Works across Developers, Product Manager, and Support to gather accurate information
- Reviews release notes with Release Manager
- Ensures on-call runbooks are accessible to SRE/Support

---

## Site Reliability Engineer (SRE) / DevOps Owner

### Role Summary
Responsible for infrastructure, deployment pipelines, reliability engineering, and operational readiness.

### Responsibilities
- Maintain deployment pipelines and infrastructure-as-code
- Own on-call rotations and operational playbooks
- Drive reliability improvements and incident response
- Assist with capacity planning and scaling

### Interactions
- Works with Developers and Engineering Manager to ensure safe rollouts
- Partners with Observability Owner to validate alerts and dashboards
- Coordinates with Release Manager for deployment execution

---

## Legal / Compliance Liaison

### Role Summary
Provides guidance on legal, regulatory, and contractual requirements that affect product features.

### Responsibilities
- Review features for data protection and regulatory compliance
- Advise on contractual obligations and required controls
- Coordinate necessary approvals or documentation for releases

### Interactions
- Engages with Product Manager and Security Liaison on compliance risk
- Provides input to Product Lead and stakeholders when approvals are required

---

## How adding these personas improves outcomes
- Clear accountability reduces delays and finger-pointing.
- Faster onboarding: new hires can see explicit role responsibilities.
- Better handoffs between design, build, release, and support.
- Improved observability, security posture, and measurement of success.

