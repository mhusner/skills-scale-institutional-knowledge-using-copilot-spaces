# OctoAcme Project Management Docs

This folder is the onboarding and reference hub for how OctoAcme delivers cross-functional projects from idea to outcomes. Our lifecycle is intentionally lightweight and repeatable: **Initiation → Planning → Execution → Release → Close & Retrospective**, with clear decision gates and shared artifacts at each stage.

Work starts in **Initiation**, where the PM and Product Lead/PdM align on business need, stakeholders/sponsors, measurable success metrics, risks, and a high-level timeline in a one-pager. A project moves to planning when outcomes are clear, priority is aligned, and team capacity is confirmed.

In **Planning** and **Execution**, teams break work into shippable increments, define acceptance criteria and Definition of Done, and track delivery on a shared board (**Backlog → Ready → In Progress → In Review → QA → Done**). Communication follows a steady cadence: daily standups, weekly delivery/risk syncs, and milestone demos. PRs should stay small when possible, include the related issue and acceptance criteria, pass CI (tests/lint/security checks), and receive required approvals before merge.

Quality, release discipline, and learning loops are built into delivery. QA/Testing and Developers validate unit, integration, and e2e smoke coverage as appropriate. PM and Product Manager roles keep risks visible through the risk register and escalation path (team triage → PM/Product Lead coordination → sponsor escalation for business-impacting blockers). Releases follow a checklist (notes, rollback plan, staging/prod verification, stakeholder communication). Retrospectives convert insights into owned, time-bound action items tracked in the backlog.

## Quick links

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution and Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management and Communication](./octoacme-risks-and-communication.md)
- [Release and Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## How to propose improvements

To request updates to these process docs, open an issue using the templates in [`.github/ISSUE_TEMPLATE/`](../.github/ISSUE_TEMPLATE/).
Include the target document, the proposed change, and why it should be updated so all stakeholders can review with shared context.
