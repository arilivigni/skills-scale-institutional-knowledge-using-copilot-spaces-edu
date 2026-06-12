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

## Additional Personas

---

## Delivery Lead

### Role Summary
The Delivery Lead owns day-to-day delivery execution for a release or initiative. They coordinate sprint commitments, manage release readiness checklists, and track cross-team dependencies to keep delivery on track.

### Responsibilities
- Own daily delivery execution and sprint commitment coordination
- Maintain and review release readiness checklists before each release
- Track and surface cross-team dependencies to the appropriate owners
- Escalate blockers and unresolved dependencies to [Project Managers](#project-managers)
- Facilitate cross-functional delivery syncs and stand-ups

### Goals
- Ensure each sprint closes with committed scope delivered or re-scoped transparently
- Remove blockers quickly so [Developers](#developers) can maintain flow
- Give [Project Managers](#project-managers) and stakeholders reliable, up-to-date delivery status

### Typical Communication
- Daily delivery stand-ups and blocker triage
- Release readiness check-ins with [Project Managers](#project-managers)
- Dependency status updates shared with [Product Managers](#product-managers) and stakeholders

---

## Engineering Manager

### Role Summary
The Engineering Manager is responsible for team capacity planning, career growth, technical debt prioritization, and resource allocation. They create the conditions for [Developers](#developers) to do their best work sustainably.

### Responsibilities
- Plan team capacity and align it to the roadmap with [Project Managers](#project-managers)
- Support [Developers](#developers) with estimation, technical guidance, and unblocking
- Prioritize technical debt reduction alongside feature work
- Identify and flag hiring or training needs to [Project Managers](#project-managers)
- Drive performance conversations and career development for direct reports

### Goals
- Maintain a healthy, sustainable team velocity
- Reduce technical debt and improve long-term system quality
- Ensure [Developers](#developers) have the skills and headcount needed to meet commitments

### Typical Communication
- Capacity planning sessions with [Project Managers](#project-managers)
- 1:1s and team retrospectives with [Developers](#developers)
- Hiring and training proposals to leadership

---

## Design Lead

### Role Summary
The Design Lead owns UX consistency, accessibility standards, and design handoff artifacts. They ensure that design acceptance criteria are clear and that the implemented experience matches the intended design.

### Responsibilities
- Define and maintain UX consistency guidelines and component standards
- Conduct accessibility checks and ensure designs meet WCAG requirements
- Produce and manage design handoff artifacts (specs, prototypes, annotations)
- Define design acceptance criteria in collaboration with [Product Managers](#product-managers)
- Review implemented UIs with [Developers](#developers) and QA to close gaps

### Goals
- Deliver a consistent, accessible user experience across the product
- Minimize rework caused by ambiguous or late design changes
- Ensure QA has clear UX acceptance scenarios to validate against

### Typical Communication
- Design reviews and handoff sessions with [Developers](#developers)
- Alignment meetings with [Product Managers](#product-managers) on product goals and user needs
- UX acceptance scenario walkthroughs with QA

---

## Security Liaison

### Role Summary
The Security Liaison coordinates security reviews, maintains threat model updates, and ensures CI security scans are configured and acted on. They bridge security requirements and day-to-day engineering practices.

### Responsibilities
- Schedule and facilitate security reviews at key project milestones
- Maintain and update the project threat model as the design evolves
- Ensure security scanning tools are integrated into CI pipelines with [Platform / DevOps Engineer](#platform--devops-engineer)
- Partner with [Developers](#developers) to triage and remediate identified vulnerabilities
- Escalate high-impact or unresolved findings to [Product Managers](#product-managers) and leadership

### Goals
- Prevent security issues from reaching production
- Reduce mean time to remediate identified vulnerabilities
- Ensure compliance with organizational security policies and standards

### Typical Communication
- Security review reports shared with [Developers](#developers) and [Platform / DevOps Engineer](#platform--devops-engineer)
- Escalation notices for high-severity findings to [Product Managers](#product-managers)
- Threat model updates distributed to the delivery team

---

## Data Analyst

### Role Summary
The Data Analyst defines success metrics, builds dashboards, validates telemetry and experiments, and supports post-release analysis. They ensure the team can measure whether delivered work is achieving its intended outcomes.

### Responsibilities
- Define and document success metrics in collaboration with [Product Managers](#product-managers)
- Build and maintain dashboards for key product and delivery metrics
- Validate that telemetry and instrumentation are correctly implemented with [Developers](#developers) and [Platform / DevOps Engineer](#platform--devops-engineer)
- Design and analyze experiments (A/B tests, feature flags) to evaluate impact
- Provide post-release analysis reports to [Project Managers](#project-managers) and [Product Managers](#product-managers)

### Goals
- Give the team reliable data to evaluate feature impact and guide prioritization
- Ensure instrumentation is in place before features ship
- Surface actionable insights from post-release data to inform the next iteration

### Typical Communication
- Metrics definition sessions with [Product Managers](#product-managers)
- Instrumentation reviews with [Developers](#developers) and [Platform / DevOps Engineer](#platform--devops-engineer)
- Post-release analysis reports shared with [Project Managers](#project-managers) and stakeholders

---

## Support / Customer Success Liaison

### Role Summary
The Support / Customer Success Liaison represents customer-facing teams in the delivery process. They surface known issues from the field, help draft customer communications, and contribute to runbooks so support teams can handle incidents effectively.

### Responsibilities
- Represent customer-facing teams in planning and release readiness discussions
- Provide input on known customer issues that should influence backlog prioritization
- Collaborate with [Developers](#developers) to reproduce and document reported issues
- Draft customer-facing communications for incidents and feature launches with [Project Managers](#project-managers)
- Contribute to operational runbooks alongside [Platform / DevOps Engineer](#platform--devops-engineer)

### Goals
- Reduce customer impact from incidents through timely, accurate communications
- Ensure support teams have the documentation needed to handle common issues
- Influence hotfix prioritization based on customer severity with [Product Managers](#product-managers)

### Typical Communication
- Release readiness and incident communications with [Project Managers](#project-managers)
- Hotfix and prioritization discussions with [Product Managers](#product-managers)
- Issue reproduction sessions with [Developers](#developers)

---

## Platform / DevOps Engineer

### Role Summary
The Platform / DevOps Engineer owns CI/CD pipelines, deployment automation, observability infrastructure, and runbook maintenance. They ensure the team can ship reliably and recover quickly from incidents.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines for automated build, test, and deployment
- Manage deployment automation and environment configuration
- Build and maintain observability tooling (logging, metrics, alerting)
- Author and keep runbooks current for common operational scenarios
- Partner with [Security Liaison](#security-liaison) to harden pipelines and infrastructure
- Coordinate release windows and rollback plans with [Project Managers](#project-managers)

### Goals
- Achieve fast, reliable, and repeatable deployments with minimal manual intervention
- Maintain high observability so incidents are detected and diagnosed quickly
- Ensure rollback procedures are tested and ready before every release

### Typical Communication
- Build and deploy troubleshooting with [Developers](#developers)
- Pipeline hardening and security scan configuration with [Security Liaison](#security-liaison)
- Release window and rollback plan coordination with [Project Managers](#project-managers)

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

