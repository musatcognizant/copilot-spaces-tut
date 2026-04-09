# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It also adds additional personas commonly required for modern delivery teams and clarifies interactions and handoffs between roles.

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

## QA / Testing

### Role Summary
QA/Testers ensure delivered work meets acceptance criteria, is reliable, and satisfies quality standards.

### Responsibilities
- Define test plans and acceptance criteria
- Execute manual/automated tests and report defects
- Validate fixes and regression coverage
- Participate in design and planning to advise on testability

### Typical Communication
- Test reports, bug tickets, and test automation pipelines
- Collaboration in sprint planning and demos

---

## Stakeholders

### Role Summary
Stakeholders provide input, funding, and decisions required to steer the project to successful outcomes.

### Responsibilities
- Provide business context and priorities
- Make or ratify key decisions
- Provide domain or compliance input as needed

---

## Additional Personas (Proposed Additions)

The following personas are often missing in concise role lists but improve clarity and accountability when defined.

### Scrum Master

#### Role Summary
Facilitates Agile ceremonies and helps the delivery team adopt and improve agile practices.

#### Responsibilities
- Facilitate daily standups, sprint planning, review, and retrospective
- Remove impediments or escalate as needed
- Coach team on agile practices and continuous improvement
- Track team health and process indicators (e.g., flow, WIP)

#### Interaction with existing roles
- Works closely with Project Manager and Product Manager to align cadence and remove blockers.
- Supports Developers and QA to surface process impediments and implement improvements.
- Communicates team risks and capacity constraints to PM.

---

### UX Designer

#### Role Summary
Designs user flows, wireframes, and prototypes; ensures solutions deliver usable value to end users.

#### Responsibilities
- Conduct/design user research, wireframes, and prototypes
- Define interaction and visual design guidance
- Validate designs with users and stakeholders
- Provide assets and specs to Developers, and consult on implementation

#### Interaction with existing roles
- Collaborates with Product Manager to clarify user needs and acceptance criteria.
- Works with Developers and QA to ensure design intent is preserved.
- Participates in backlog refinement to ensure UX work is planned and scoped.

---

### Business Analyst (BA)

#### Role Summary
Translates stakeholder needs into clear, actionable requirements and acceptance criteria.

#### Responsibilities
- Elicit and document requirements and acceptance criteria
- Model processes and define success scenarios
- Support prioritization by clarifying impacts and scope
- Coordinate requirements validation with stakeholders

#### Interaction with existing roles
- Liaises between Product Manager, Project Manager, Developers, and QA.
- Helps ensure user stories are ready for implementation and have clear acceptance criteria.

---

### DevOps Engineer / Platform Engineer

#### Role Summary
Maintains CI/CD pipelines, infrastructure as code, and operational readiness for deployments.

#### Responsibilities
- Build/maintain pipelines, infrastructure, and monitoring
- Ensure deployment automation and rollback capabilities
- Support incident response and post-incident reviews
- Advise on performance, scalability, and security aspects

#### Interaction with existing roles
- Partners with Developers to make deployments reliable and observable.
- Works with Project Manager to schedule deployments and plan rollbacks.
- Coordinates with QA to validate production-like environments and run smoke tests.

---

## How these personas interact (high-level)

- Product Manager sets direction; Project Manager coordinates; Developers, QA, UX, BA, and DevOps deliver.
- Scrum Master helps flow and process; BA and UX provide discovery/requirements/design inputs early.
- DevOps ensures safe and repeatable release path; QA validates release readiness.
- Clear handoffs between these roles reduce ambiguity. See docs/octoacme-role-handoffs-and-checklists.md for practical checklists and handoff points.

---

## How these personas are used in exercises and templates

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Use the role-responsibility template (docs/templates/role-responsibility-template.md) to standardize new entries.
