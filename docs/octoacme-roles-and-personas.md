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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas (proposed)

The following personas are commonly involved in cross-functional projects. Add short Responsibilities and Interactions sections for each persona to clarify handoffs and ownership. This content responds to issue #4 ("Adding more personas and roles to the project management processes").

### Technical Lead

#### Role Summary
Drive technical design and architecture choices for the project. Ensure solutions are scalable, maintainable, and aligned with the product goals.

#### Responsibilities
- Drive technical design and architecture decisions
- Define non-functional requirements and ensure they are met
- Mentor developers and guide implementation choices
- Ensure code quality through reviews and standards

#### Interactions
- Works with PM and PdM on feasibility and trade-offs
- Pairs with Developers on implementation details
- Coordinates with QA and DevOps for testability and operability

---

### Engineering Manager

#### Role Summary
Support team health and capability by managing people, capacity, and enabling execution at scale.

#### Responsibilities
- People management, performance coaching, and career development
- Capacity planning and resource allocation
- Removing organizational blockers and supporting team growth

#### Interactions
- Aligns with PM on resourcing and delivery risk
- Supports Technical Lead on technical enablement and priorities
- Engages with HR and leadership for staffing needs

---

### QA Lead / Test Architect

#### Role Summary
Define and own the test strategy and quality standards across the project.

#### Responsibilities
- Define test strategy (automation + manual where needed)
- Drive test coverage and validation approach
- Ensure testability is considered in designs

#### Interactions
- Partners with Developers and Technical Lead to embed testing in PRs
- Reports quality metrics and risks to PM and PdM
- Coordinates acceptance testing with Stakeholders and Release Manager

---

### DevOps / Platform Engineer

#### Role Summary
Own CI/CD pipelines, platform reliability, and deployment automation.

#### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Implement observability, alerting, and platform reliability measures
- Support incident response and post-incident remediation

#### Interactions
- Works with Developers and Release Manager during releases
- Collaborates with Technical Lead on architecture and operability requirements
- Assists Support/Customer Success for production troubleshooting

---

### Release Manager

#### Role Summary
Coordinate release planning and execution across teams to minimize risk and ensure smooth deployment.

#### Responsibilities
- Coordinate release windows, runbooks, and rollback plans
- Communicate release status and impact to stakeholders
- Validate readiness (QA, monitoring, rollback) before production deploy

#### Interactions
- Coordinates across PM, DevOps, QA, and Support
- Escalates release blockers to Project Manager or Product Lead as needed

---

### Security Liaison

#### Role Summary
Ensure security considerations are integrated early in design and throughout delivery.

#### Responsibilities
- Surface security requirements and run threat/risk reviews
- Ensure compliance with security standards and remediation plans
- Help prioritize security fixes and mitigations

#### Interactions
- Engages with Technical Lead and DevOps early in design
- Escalates critical findings to Product Lead or Security team
- Works with Developers on fixes and secure implementation

---

### UX Researcher / Product Designer

#### Role Summary
Represent user needs through research, design, and accessibility practices.

#### Responsibilities
- Conduct user research and usability testing
- Produce designs, prototypes, and interaction specs
- Ensure accessibility and UX quality

#### Interactions
- Partners with PdM to define user problems and acceptance criteria
- Hands off designs to Developers and QA with clear specs
- Collaborates with Technical Lead on feasibility trade-offs

---

### Data Analyst / Data Engineer

#### Role Summary
Provide data instrumentation, analysis, and dashboards to measure outcomes and inform decisions.

#### Responsibilities
- Define instrumentation and success metrics
- Build dashboards and reports for stakeholders
- Analyze data to inform prioritization and product improvements

#### Interactions
- Works with PdM on metrics and experiments
- Coordinates with Developers to implement telemetry
- Shares insights with PM for progress reporting

---

### Support / Customer Success Liaison

#### Role Summary
Act as the voice of the customer for support issues and coordinate post-release support activities.

#### Responsibilities
- Triage customer-reported issues and collect context
- Communicate critical problems and user impact to the delivery team
- Coordinate post-release support and handoffs

#### Interactions
- Feeds critical bugs and feature requests to PM and PdM
- Collaborates with DevOps and Developers for fixes and patches
- Informs Release Manager of support windows or customer-impacting releases

---

### Technical Writer / Documentation Owner

#### Role Summary
Maintain user-facing documentation, runbooks, and internal knowledge articles.

#### Responsibilities
- Produce and maintain release notes, user docs, and runbooks
- Ensure documentation is updated with code and release changes
- Improve discoverability of operational and onboarding content

#### Interactions
- Works with Developers, QA, and Release Manager to publish accurate docs
- Supports onboarding by maintaining clear guides and examples

---

## How to use these personas in the Roles & Personas doc
- For each persona, add a short Responsibilities section and a short Interactions section in docs/octoacme-roles-and-personas.md.
- Include brief examples of typical handoffs (e.g., design -> implementation -> release) and RACI-style notes where helpful.
- Add a short onboarding snippet describing when and how to engage each persona.

---

*This addition expands the Personas doc to cover specialized and cross-functional roles. See issue #4 for the original proposal and acceptance criteria.*
