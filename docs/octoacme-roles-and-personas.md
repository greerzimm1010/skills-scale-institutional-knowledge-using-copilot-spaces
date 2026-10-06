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

## QA / Testing Lead

### Role Summary
QA / Testing Leads define and execute quality assurance strategies. They own test planning, acceptance criteria validation, and quality metrics. They collaborate with Product Managers, developers, and stakeholders to ensure features meet defined quality standards before release.

### Responsibilities
- Create and maintain test plans aligned with acceptance criteria
- Design and execute unit, integration, and end-to-end tests
- Validate features against Definition of Done and acceptance criteria
- Report quality metrics and test coverage status
- Identify and escalate quality blockers
- Participate in retrospectives to improve testing processes

### Goals
- Ensure every feature meets quality standards before release
- Reduce defects and rework cycles
- Provide confidence to stakeholders that features are production-ready
- Balance thorough testing with delivery timelines

### Typical Communication
- QA sign-off in PR reviews
- Test status in sprint standups and delivery syncs
- Test plans during planning and kickoff
- Quality metrics in stakeholder updates

### Interaction with Existing Roles
- Works closely with Developers to review implementation quality and identify gaps before release
- Partners with Product Managers to confirm that acceptance criteria and user outcomes are being validated
- Supports Project Managers by surfacing quality risks, timeline impacts, and release readiness concerns
- Provides stakeholders with confidence that delivery meets agreed standards and reduces business risk

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and sponsors provide business context, prioritization guidance, and decision authority. They invest in project outcomes and help remove organizational blockers that could slow delivery.

### Responsibilities
- Define business objectives and success criteria
- Approve the project charter and major decisions
- Provide resourcing and remove organizational barriers
- Communicate the importance of the initiative across the organization
- Review progress and provide feedback at key milestones
- Escalate risks and blockers at the sponsor level when needed

### Goals
- Ensure the project delivers measurable business value
- Maintain alignment between technical delivery and business priorities
- Reduce external dependencies and organizational friction
- Support team success through active sponsorship and decision-making

### Typical Communication
- Monthly stakeholder briefings
- Approval of project charter and major decisions
- Escalation path for critical risks and blockers
- Feedback on demos, milestones, and releases

### Interaction with Existing Roles
- Works with Product Managers to define priorities, success metrics, and trade-offs
- Collaborates with Project Managers to align approvals, milestones, and stakeholder updates
- Provides Developers and technical teams with clear business direction and removes blockers affecting delivery
- Relies on QA and release checkpoints to confirm project health before making key decisions

---

## Technical Architect

### Role Summary
Technical Architects define technical direction, scalability, and integration strategies. They work with Product Managers, Developers, and Project Managers to design solutions that meet current needs while enabling future growth.

### Responsibilities
- Design technical solutions and architecture for features
- Evaluate technology choices and trade-offs
- Identify integration points with existing systems
- Review technical designs for scalability and maintainability
- Document architecture decisions and rationale
- Mentor developers on technical best practices

### Goals
- Deliver scalable, maintainable technical solutions
- Reduce technical debt and architectural complexity
- Enable faster future delivery through strong design decisions
- Build resilient systems that support business growth

### Typical Communication
- Architecture reviews and design docs during planning
- Technical design feedback in code reviews
- Escalation of technical risks and dependencies
- Architecture documentation and decision logs

### Interaction with Existing Roles
- Works with Product Managers to translate business goals into viable technical solutions
- Guides Developers on design standards, trade-offs, and implementation practices
- Advises Project Managers on delivery risk, dependency management, and technical feasibility
- Coordinates with QA teams to ensure the architecture supports testability, observability, and release confidence

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps / Infrastructure Engineers own deployment infrastructure, CI/CD pipelines, and production monitoring. They enable teams to deliver features reliably and observably to customers.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage deployment infrastructure and environments
- Implement security scanning and compliance checks in CI
- Monitor production systems and alert on issues
- Support incident response and rollback procedures
- Collaborate on disaster recovery and business continuity

### Goals
- Enable fast, reliable, repeatable deployments
- Minimize production incidents and mean-time-to-recovery
- Maintain high system observability and reliability
- Support team velocity through automated infrastructure

### Typical Communication
- CI/CD configuration and pipeline updates
- Deployment readiness reviews
- Production monitoring and incident response
- Infrastructure requirements in planning and release activities

### Interaction with Existing Roles
- Partners with Developers to support environment readiness, deployment automation, and release quality
- Works with Project Managers to align release windows, rollback plans, and risk communication
- Supports Product Managers and Stakeholders through operational readiness and service reliability signals
- Coordinates with QA / Testing Leads to validate production readiness and release confidence

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
