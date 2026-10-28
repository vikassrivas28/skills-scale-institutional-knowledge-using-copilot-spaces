# OctoAcme Project Management Docs

This folder contains the core project management guidance used by OctoAcme. The documents are designed to help teams initiate work, plan delivery, communicate clearly, track execution, release changes, and continuously improve.

## OctoAcme project management process overview

OctoAcme follows a simple lifecycle for project work: initiation, planning, execution, release, and retrospective. During initiation, teams validate the business need, define stakeholders, document success metrics, and decide whether to move forward into planning. Planning turns the approved idea into a backlog with clear priorities, estimates, acceptance criteria, milestones, and dependencies. Execution focuses on disciplined delivery through standups, progress tracking, quality checks, issue triage, and cross-functional coordination. Release and deployment standardize how work moves to production, with checks for validation, rollback readiness, and stakeholder communication. After each milestone or release, teams hold a retrospective to capture what worked, what needs improvement, and which actions should be tracked going forward.

This process is grounded in clear ownership and consistent communication. OctoAcme defines typical roles such as Product Managers, Project Managers, and Developers, each with distinct responsibilities for defining outcomes, coordinating delivery, and building the solution. A well-structured communication cadence—weekly PM and product alignment, team standups, milestone reviews, and stakeholder updates—helps keep the project visible and reduces surprises. Risk management is handled through ongoing assessment, escalation paths, and a central risk register so issues can be addressed before they become blockers.

Quality is treated as a delivery requirement rather than a final-stage activity. Teams are expected to define acceptance criteria, test new logic, run CI checks, conduct security scans, and complete smoke testing for critical flows before release. Pull requests are expected to be small, reviewable, and tied to an issue with clear acceptance criteria. This helps maintain quality, accelerate feedback, and reduce rework.

## Documentation index

- [Project Management Overview](./octoacme-project-management-overview.md) — high-level overview of the project lifecycle, roles, artifacts, and communication cadence.
- [Project Initiation Guide](./octoacme-project-initiation.md) — how to validate a project idea and prepare the initial planning artifacts.
- [Project Planning](./octoacme-project-planning.md) — how to convert an initiative into a backlog, milestones, and delivery plan.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — day-to-day execution rhythm, project board usage, PR expectations, testing, and escalation.
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — How to identify, track, mitigate, and communicate project risks and dependencies.
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — deployment readiness, smoke testing, release notes, and rollback steps.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — how to capture lessons learned and drive follow-up action items.
- [Roles and Personas](./octoacme-roles-and-personas.md) — summaries of key personas and their responsibilities in OctoAcme project work.

## How to use these docs

Use these guides as the shared operating model for OctoAcme initiatives. Start with the Project Management Overview and Project Initiation Guide when launching a new effort, then move into planning, execution, release, and retrospective activities as the project progresses. Keeping these artifacts updated in the project repo supports continuity, onboarding, and consistent delivery across the team.
