# OctoAcme Project Management Docs

This repository documents the operating model OctoAcme uses to manage projects from concept through delivery and continuous improvement. The team follows a customer-first, iterative lifecycle: initiate and align on measurable outcomes; plan scope, ownership, milestones, risks, and dependencies; execute and track work with regular communication and quality checks; release with verification and rollback readiness; then retrospect and improve.

## Overview of the OctoAcme process

OctoAcme starts each initiative by validating the business need, identifying stakeholders, defining success criteria, and producing a lightweight project one-pager. Once the initiative is approved, the team creates a prioritized backlog, estimates work, defines acceptance criteria and a Definition of Done, and plans milestones and dependencies. Delivery is managed through a project board, with work moving through backlog, readiness, execution, review, QA, and done states. Weekly standups, PM/Product reviews, demos, and status reporting keep the team aligned while enabling early risk identification and escalation.

Quality is treated as a shared responsibility across the project lifecycle. Teams define clear acceptance criteria, run unit and integration tests when appropriate, validate critical flows with smoke tests, and require passing CI checks, security scans, and manual QA where needed. Release readiness includes staging validation, deployment planning, rollback preparation, and post-deployment verification. After each sprint, release, or key milestone, the team uses retrospectives to capture lessons learned and convert them into focused improvement actions.

## Roles and responsibilities

The OctoAcme process depends on strong role clarity. Project Managers coordinate planning, schedules, risks, and stakeholder communication; Product Managers define the problem, prioritize value, and measure outcomes; Developers build and test software; QA validates quality and acceptance; and stakeholders provide input, approval, and business context. The project docs emphasize ownership, clear communication, and consistent documentation so teams can deliver efficiently without confusion.

## Process documents

- [Project management overview](octoacme-project-management-overview.md) — principles, roles, lifecycle, artifacts, and communication cadence.
- [Project initiation guide](octoacme-project-initiation.md) — validate the business need, align stakeholders, define outcomes, and decide whether to proceed to planning.
- [Project planning guide](octoacme-project-planning.md) — create a prioritized backlog, define acceptance criteria and the Definition of Done, and plan milestones, risks, and dependencies.
- [Execution and tracking guide](octoacme-execution-and-tracking.md) — track delivery on the project board, follow PR and testing practices, report progress, and escalate blockers.
- [Risk management and communication guide](octoacme-risks-and-communication.md) — maintain and monitor the risk register, communicate status, and follow escalation paths.
- [Release and deployment guide](octoacme-release-and-deployment.md) — meet pre-release requirements, deploy and verify releases, and prepare rollback/incident response.
- [Retrospective and continuous improvement guide](octoacme-retrospective-and-continuous-improvement.md) — capture learnings after sprints, releases, milestones, or incidents and track improvement actions.
- [Roles and personas](octoacme-roles-and-personas.md) — describe the responsibilities and communication patterns of key project roles.

## Suggested use

Use these documents together as the team’s operating playbook for project planning, delivery, communication, and continuous improvement. For any new project, start with initiation, move into planning, and then follow the execution, release, and retrospective guidance as work progresses.
