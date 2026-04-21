# OctoAcme Roles and Personas

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

## QA / Testing Lead

### Role Summary
QA / Testing Leads own test strategy and release-readiness quality signals across the lifecycle.

### Responsibilities
- Define and maintain test strategy (unit, integration, e2e, and manual acceptance as needed)
- Ensure acceptance criteria are testable and traceable to verification
- Coordinate defect triage and quality gates before release
- Publish quality status and unresolved risk summaries

### Goals
- Prevent escaped defects in critical user workflows
- Make quality status visible early and continuously
- Support predictable go/no-go release decisions

### Typical Communication
- Test plans and test result summaries
- Defect triage updates with severity and owner
- Release-readiness quality sign-off notes

### Interaction Model
- Works with **Developers** on testability, automation, and defect fixes
- Works with **Product Managers** to clarify acceptance criteria and user-impact priority
- Works with **Project Managers** to schedule validation windows and escalate quality risks
- Partners with **DevOps / Release Engineers** on staging/prod smoke checks

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors provide strategic direction, funding support, and final business-level escalation decisions.

### Responsibilities
- Confirm business outcomes, constraints, and investment priorities
- Approve major scope, timeline, or risk trade-offs
- Remove organizational blockers outside the delivery team's control
- Review milestone outcomes and authorize continuation when needed

### Goals
- Ensure project outcomes align to business priorities
- Keep decision latency low for escalated blockers
- Improve delivery confidence for cross-functional initiatives

### Typical Communication
- Milestone reviews and steering updates
- Escalation decisions and approvals
- Outcome and KPI progress updates

### Interaction Model
- Receives structured updates from **Project Managers** and **Product Managers**
- Aligns with **Product Managers** on outcome expectations and success metrics
- Supports **Project Managers** during Level 3 escalation
- Coordinates with other **Stakeholders** when cross-org decisions are required

---

## UX / Design Lead

### Role Summary
UX / Design Leads ensure solutions are usable, consistent, and aligned with customer needs.

### Responsibilities
- Create and iterate user flows, wireframes, and interaction designs
- Validate usability assumptions through lightweight research or feedback
- Partner on acceptance criteria that reflect user experience outcomes
- Support design QA during implementation and release

### Goals
- Reduce usability issues and rework
- Improve task completion and user satisfaction
- Align delivered experience to product intent

### Typical Communication
- Design reviews and annotated mocks/prototypes
- UX acceptance notes and usability findings
- Async feedback on implementation fidelity

### Interaction Model
- Works with **Product Managers** to translate problem statements into usable experiences
- Works with **Developers** to clarify implementation details and constraints
- Works with **QA / Testing Lead** on UX-focused acceptance and defect triage
- Coordinates with **Project Managers** on design milestones and dependencies

---

## DevOps / Release Engineer

### Role Summary
DevOps / Release Engineers own deployment reliability, runtime observability, and release safety controls.

### Responsibilities
- Maintain CI/CD pipelines and environment readiness
- Define deployment, rollback, and post-deploy verification procedures
- Monitor production health signals and incident triggers
- Support operational readiness and handoffs to support teams

### Goals
- Increase release reliability and recovery speed
- Reduce deployment risk and manual errors
- Improve visibility into production behavior after launch

### Typical Communication
- Release readiness updates and deployment plans
- Incident and rollback communication during live issues
- Environment status and operational constraints

### Interaction Model
- Works with **Developers** on build/deploy requirements and operational fixes
- Works with **QA / Testing Lead** on staging parity and smoke test execution
- Works with **Project Managers** to align release windows and risk planning
- Works with **Support / Customer Success** during post-release monitoring and escalation

---

## Support / Customer Success Lead

### Role Summary
Support / Customer Success Leads represent customer impact, readiness, and post-release feedback loops.

### Responsibilities
- Prepare support readiness (known issues, runbooks, response guidance)
- Triage incoming customer issues and route them by severity
- Share customer-impact trends and recurring pain points
- Confirm communication plans for releases and incidents

### Goals
- Reduce customer-facing incident duration
- Improve adoption and satisfaction after release
- Close the loop between production feedback and backlog prioritization

### Typical Communication
- Customer-impact summaries and escalation alerts
- Launch readiness and support handoff notes
- Retrospective input from support trends

### Interaction Model
- Works with **Project Managers** on communication cadence and escalation paths
- Works with **Product Managers** to prioritize customer-facing fixes and enhancements
- Works with **Developers** and **QA / Testing Lead** to reproduce and validate reported issues
- Works with **DevOps / Release Engineers** during live incidents and post-release watch windows

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
