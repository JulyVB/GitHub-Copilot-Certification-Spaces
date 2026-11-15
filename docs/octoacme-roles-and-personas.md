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

## UX/UI Designers and User Researchers

### Role Summary
UX/UI Designers and User Researchers turn customer needs and product goals into usable, accessible experiences. They help the team understand user behavior, translate requirements into design decisions, and validate that solutions are intuitive and effective.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Define user flows, interaction patterns, and interface design direction
- Partner with Product Managers to align designs to customer outcomes and success metrics
- Work with Developers to validate feasibility and implementation quality
- Collaborate with QA/Testing to confirm the experience meets usability and accessibility criteria

### Goals
- Improve customer satisfaction and product usability
- Reduce rework caused by unclear requirements or weak user experience
- Ensure design decisions are grounded in evidence and user feedback

### Typical Communication
- Product discovery and design review sessions
- UX critiques, research synthesis, and usability findings
- Cross-functional planning and handoff discussions with Product, Engineering, and QA

### Interaction with Existing Roles
- With Product Managers: translate product goals, customer needs, and research insights into prioritized experience improvements.
- With Developers: clarify interaction patterns, accessibility expectations, and implementation trade-offs.
- With QA/Testing: validate usability, accessibility, and acceptance criteria before release.

---

## Engineering / Technical Leads

### Role Summary
Engineering or Technical Leads guide architecture, technical decision-making, and implementation quality across a project. They balance delivery speed with technical sustainability and support the team in resolving dependencies and technical risks.

### Responsibilities
- Define technical approach, architecture patterns, and standards
- Guide implementation planning and technical risk mitigation
- Support estimation, sequencing, and dependency management with Project Managers
- Mentor Developers and review design and implementation quality
- Partner with Product Managers on scope trade-offs and feasibility

### Goals
- Deliver technically sound, maintainable solutions
- Reduce delivery risk and avoid architectural drift
- Keep engineering decisions aligned with business priorities and quality standards

### Typical Communication
- Technical design reviews and architecture planning
- Daily delivery coordination and dependency management
- Planning discussions with PMs, Product, and QA on delivery readiness

### Interaction with Existing Roles
- With Project Managers: identify delivery risks, dependencies, and sequencing needs.
- With Product Managers: assess feasibility, trade-offs, and impact of scope changes.
- With Developers: set technical direction, review implementation, and resolve blockers.
- With QA/Testing: align on testability, edge cases, and release readiness.

---

## DevOps / SRE / Release Managers

### Role Summary
DevOps, SRE, and Release Managers ensure the team can build, deploy, monitor, and recover software reliably. They keep delivery pipelines, production health, and release readiness aligned with project commitments.

### Responsibilities
- Manage CI/CD pipelines, deployment automation, and release workflows
- Monitor system health, reliability, and operational performance
- Coordinate deployment windows, rollback plans, and post-release verification
- Partner with engineering teams on platform and infrastructure needs
- Support incident response and operational readiness planning

### Goals
- Increase release confidence and reduce production risk
- Improve system stability, observability, and recovery time
- Keep deployment processes predictable and repeatable

### Typical Communication
- Release planning and deployment readiness reviews
- Operational dashboards, incident updates, and post-deployment check-ins
- Coordination with PMs, Product Managers, and stakeholders on launch timing

### Interaction with Existing Roles
- With Project Managers: align release schedules, dependencies, and communication plans.
- With Product Managers: support launch readiness and stakeholder communication.
- With Developers and Engineering Leads: ensure pipelines, environments, monitoring, and rollback procedures are ready.
- With Security/Privacy Leads: coordinate secure deployment controls and compliance checks.

---

## Security / Privacy Leads

### Role Summary
Security and Privacy Leads help teams design and deliver work that protects customer trust, data, and compliance obligations. They identify risks early and help embed security and privacy considerations into the product lifecycle.

### Responsibilities
- Assess risks related to security, privacy, and compliance requirements
- Define and review controls, guardrails, and approval requirements
- Partner with Product Managers to prioritize requirements and constraints
- Work with Developers and Engineering Leads to validate secure implementation
- Support QA and release checks to confirm controls are effective

### Goals
- Reduce security and privacy risk across the product lifecycle
- Ensure compliance with relevant standards and contractual obligations
- Build trust with customers, stakeholders, and regulators

### Typical Communication
- Threat reviews, risk assessments, and compliance checkpoints
- Security design and privacy requirement discussions
- Escalation and incident coordination when issues arise

### Interaction with Existing Roles
- With Product Managers: validate requirements, trade-offs, and risk tolerance.
- With Developers and Engineering Leads: review implementation and control coverage.
- With Project Managers: coordinate risk tracking, approvals, and timelines.
- With QA/Testing: confirm security-related acceptance criteria are verified.

---

## Business Analysts / Data & Analytics Leads

### Role Summary
Business Analysts and Data & Analytics Leads clarify business processes, metrics, and decision quality. They help teams translate operational needs into clear requirements and measure whether the product is delivering value.

### Responsibilities
- Capture workflows, business rules, and cross-functional requirements
- Define measurable outcomes, KPIs, and reporting needs
- Support acceptance criteria refinement and traceability to business goals
- Analyze usage and performance data to inform iteration decisions
- Partner with Product Managers and stakeholders to validate decisions based on evidence

### Goals
- Improve business clarity, requirement quality, and decision-making
- Connect delivery work to measurable outcomes and customer value
- Reduce ambiguity in scope and prioritization

### Typical Communication
- Requirements workshops and stakeholder interviews
- KPI tracking, reporting, and outcome reviews
- Cross-functional alignment on business constraints and dependencies

### Interaction with Existing Roles
- With Product Managers: clarify customer and business needs, scope, and success metrics.
- With Developers and QA/Testing: translate requirements into acceptance criteria and verify outcomes.
- With Project Managers: provide status signals, operational insights, and dependency context.
- With Stakeholders: share progress, risks, and measured business impact.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- In larger projects, these roles may be separate; in smaller teams, one person may cover multiple responsibilities while keeping ownership and accountability explicit.

