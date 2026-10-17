# OctoAcme Project Management Docs

This folder contains the OctoAcme project management process documents and serves as the single entrypoint for contributors and stakeholders to discover our project management artifacts.

Summary of project management processes

OctoAcme runs projects iteratively from a clear initiation gate into planning and execution. Work begins with a Project One-pager (problem, goal, success metrics) and follows a lightweight initiation checklist before moving into backlog creation, estimation, and sprint/iteration planning. Backlog items use a consistent template (title, description, acceptance criteria, priority, estimate, owner) and the team defines a Definition of Done to ensure items are work-ready before being pulled into an iteration. Release planning maps milestones and release types (patch/minor/major) with pre-release requirements and a deployment checklist to minimize risk.

Day-to-day workflows center on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined pull-request process: smaller PRs when possible, CI/lint/tests run before review, PRs linked to issues and acceptance criteria, and at least one approval required. Team cadence includes short daily standups, a weekly delivery sync, and demo/review at the end of each sprint or milestone; stakeholder communication is supported by templates for weekly status and incident updates and a formal escalation path (team → PM → Product Lead → Sponsor).

Quality, risk, and continuous improvement are integral. Quality assurance requires unit, integration, and end-to-end smoke tests where appropriate, plus CI security scanning and manual QA for acceptance. Releases require smoke testing, rollback/mitigation plans, and post-deploy verifications. Risks are tracked in a simple Risk Register (ID, impact, likelihood, owner, mitigation, status) and are reviewed regularly; retrospectives are timeboxed and generate prioritized action items that are added to the backlog and monitored in weekly PM syncs to close the improvement loop.

## Docs
- [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) — Overview and lifecycle
- [octoacme-project-initiation.md](./octoacme-project-initiation.md) — Project initiation guide and one-pager template
- [octoacme-project-planning.md](./octoacme-project-planning.md) — Planning activities, backlog template, and checklists
- [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) — Team rhythm, workflows, and execution checklist
- [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) — Release types, deployment checklist, and rollback playbook
- [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure and tracking
- [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) — Risk register, communication templates, and escalation
- [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) — Role summaries and responsibilities

---

*This README was added to satisfy issue #2: Add a README at docs/README.md that lists and links to all OctoAcme project management process documents and includes a short summary of the project's project management processes.*