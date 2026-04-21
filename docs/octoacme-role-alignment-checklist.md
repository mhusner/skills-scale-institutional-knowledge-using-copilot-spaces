# OctoAcme — Role Alignment Checklist (Kickoff + RACI-lite)

## Purpose
Reduce ambiguity by confirming role ownership, escalation paths, and communication cadence at kickoff.

Use with:
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## Kickoff Role Alignment Checklist
- [ ] A named owner exists for each core role: Project Manager, Product Manager, Developers, QA / Testing Lead
- [ ] Sponsor / Executive Stakeholder is named and escalation expectations are documented
- [ ] UX / Design Lead and DevOps / Release Engineer ownership is confirmed (or explicitly deferred with rationale)
- [ ] Support / Customer Success contact is identified for release readiness and incident communication
- [ ] Responsibilities and handoffs are reviewed against [Roles and Personas](./octoacme-roles-and-personas.md)
- [ ] Communication cadence is agreed (standups, weekly status, milestone reviews)
- [ ] Escalation path is confirmed (Team -> PM -> Product Lead -> Sponsor; Security incidents notify Security on-call)
- [ ] Decision log and risk register owners are assigned

## RACI-lite by Project Phase
Use these labels per phase:
- **A** = Accountable (single owner)
- **R** = Responsible (executes work)
- **C** = Consulted
- **I** = Informed

| Phase | PM | PdM | Dev | QA | Sponsor | UX | DevOps | Support |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Initiation | A/R | A/R | C | I | C/I | C | I | I |
| Planning | A | A/R | R | C | I | R/C | C | I |
| Execution | A | C | A/R | R | I | C | R | C |
| Release | A | C | R | A/R | I | I | A/R | R |
| Retro | A | C | R | R | I | C | C | R |

> Adjust assignments for project size, but keep one clear **A** per phase decision.
