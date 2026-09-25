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

## Security Engineers

### Role Summary
Security Engineers identify and reduce security risks across the product lifecycle. They help teams build secure solutions and verify that security requirements are addressed before release.

### Responsibilities
- Perform threat assessments and security reviews
- Define security requirements and recommend controls
- Partner with developers to remediate vulnerabilities
- Coordinate security testing and track findings to resolution
- Advise on security incidents and escalation paths

### Interaction with Existing Roles
- Work with Product Managers to translate customer, regulatory, and business risks into security requirements
- Collaborate with Developers and Technical Leads during design, implementation, and code review
- Provide risk updates to Project Managers for the risk register and escalation process
- Partner with Release Managers to confirm security readiness before deployment

---

## QA Leads / Test Managers

### Role Summary
QA Leads and Test Managers coordinate quality strategy and validation so that delivered work meets acceptance criteria and is ready for users.

### Responsibilities
- Define the test strategy for features and releases
- Coordinate integration, regression, end-to-end, and user acceptance testing
- Confirm test coverage and quality evidence for release decisions
- Track defects, risks, and unresolved quality issues
- Improve test automation and quality practices

### Interaction with Existing Roles
- Work with Product Managers to clarify acceptance criteria and user scenarios
- Coordinate with Developers to plan testability, investigate defects, and verify fixes
- Report quality status, dependencies, and release risks to Project Managers
- Partner with Release Managers to confirm smoke tests and operational validation are complete

---

## Technical Leads / Architects

### Role Summary
Technical Leads and Architects guide technical direction, design quality, and integration decisions across the project.

### Responsibilities
- Define and review solution architecture and technical designs
- Identify technical dependencies, constraints, and integration points
- Facilitate decisions about trade-offs, standards, and maintainability
- Support estimation and decomposition of complex work
- Identify technical risks and guide mitigation plans

### Interaction with Existing Roles
- Collaborate with Product Managers to evaluate technical options against product outcomes
- Guide Developers through design reviews, implementation decisions, and technical standards
- Provide Project Managers with dependency, effort, and risk information
- Work with Security Engineers and QA Leads to include security and quality requirements in designs

---

## Release Managers / Operations Owners

### Role Summary
Release Managers and Operations Owners coordinate deployment readiness and operational support so changes can be released safely and observed in production.

### Responsibilities
- Coordinate release sequencing, deployment windows, and stakeholder notifications
- Confirm rollback, mitigation, backup, and monitoring plans
- Coordinate staging validation, smoke tests, and post-deployment verification
- Track operational readiness and unresolved release blockers
- Lead deployment communication and support handoffs

### Interaction with Existing Roles
- Work with Project Managers to align release milestones, dependencies, and escalation decisions
- Coordinate with Product Managers and Stakeholders on release scope and communications
- Partner with Developers, Technical Leads, QA Leads, and Security Engineers to verify technical, quality, and security readiness
- Coordinate with Customer Success / Support Partners on known issues and user-facing guidance

---

## Data / Analytics Leads

### Role Summary
Data and Analytics Leads ensure that projects define measurable outcomes and have the instrumentation and reporting needed to evaluate impact.

### Responsibilities
- Define metrics, measurement plans, and reporting requirements
- Specify instrumentation and data-quality expectations
- Build or coordinate dashboards for usage, errors, latency, and outcomes
- Validate that collected data supports product and project decisions
- Communicate insights and limitations to decision-makers

### Interaction with Existing Roles
- Work with Product Managers to translate success criteria into measurable indicators
- Coordinate with Developers and Technical Leads on instrumentation and data flows
- Help Project Managers monitor delivery and outcome metrics in project reporting
- Provide Stakeholders with evidence for prioritization, release evaluation, and continuous improvement

---

## Customer Success / Support Partners

### Role Summary
Customer Success and Support Partners represent user needs after delivery and help the team prepare for adoption, support, and feedback.

### Responsibilities
- Share customer needs, recurring issues, and user feedback
- Review release notes, support guidance, and known issues
- Prepare support teams and customer-facing materials for releases
- Monitor adoption and post-release concerns
- Feed validated customer insights back into prioritization and retrospectives

### Interaction with Existing Roles
- Work with Product Managers to connect customer feedback to roadmap priorities and success metrics
- Coordinate with Project Managers on stakeholder updates, readiness activities, and escalations
- Partner with Release Managers on announcements, support handoffs, and incident communication
- Collaborate with Developers, QA Leads, and Data / Analytics Leads to reproduce issues and assess customer impact

---

## Cross-Role Accountability
- The Project Manager coordinates the delivery plan, dependencies, risk register, decisions, and escalations across all roles.
- The Product Manager owns product outcomes, prioritization, and customer value while incorporating technical, quality, security, operational, and support input.
- Technical Leads, Security Engineers, QA Leads, and Release Managers provide specialist readiness guidance; they should surface blockers early rather than leave ownership implicit.
- Developers implement and validate solutions in collaboration with specialist roles and document decisions when trade-offs affect delivery or operations.
- Data / Analytics Leads and Customer Success / Support Partners extend accountability beyond deployment by measuring outcomes and closing the feedback loop.
- Stakeholders provide context, decisions, and approvals through the communication cadence coordinated by the Project Manager and Product Manager.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Use the interaction guidance to make ownership, handoffs, decision rights, and escalation paths explicit in project scenarios.
