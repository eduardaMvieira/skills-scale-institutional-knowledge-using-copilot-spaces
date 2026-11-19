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

## Release Manager

### Role Summary
The Release Manager coordinates release readiness, deployment, rollback planning, and post-release verification. This role provides a clear owner for production transitions.

### Responsibilities
- Confirm that release criteria, CI checks, release notes, and rollback plans are complete
- Coordinate deployment windows and release sequencing
- Monitor deployment and post-release verification
- Initiate rollback or mitigation when agreed thresholds are breached
- Communicate release status to delivery and support teams

### Goals
- Reduce deployment risk and service disruption
- Ensure repeatable, observable releases
- Complete clear operational handoffs

### Interactions with Existing Roles
- Aligns timing and dependencies with the **Project Manager** and release scope with the **Product Manager**.
- Works with **Developers** on implementation readiness and rollback steps.
- Partners with **QA/Testing** on acceptance, smoke testing, and verification evidence.
- Coordinates handoffs with the **Support/Operations Lead** and stakeholders.

---

## Scrum Master / Delivery Facilitator

### Role Summary
The Scrum Master or Delivery Facilitator improves team flow by facilitating ceremonies, surfacing impediments, and supporting continuous improvement. The role focuses on process health rather than delivery or scope ownership.

### Responsibilities
- Facilitate planning, daily coordination, reviews, and retrospectives
- Identify and help resolve team-level blockers and workflow issues
- Encourage transparent progress, ownership, and psychological safety
- Coach the team on agreed delivery practices
- Track and follow up on retrospective improvements

### Goals
- Improve delivery flow and predictability
- Reduce avoidable meeting and handoff friction
- Strengthen team learning and continuous improvement

### Interactions with Existing Roles
- Coordinates cross-team dependencies and delivery risks with the **Project Manager**.
- Supports the **Product Manager** in preserving a focused, well-understood backlog.
- Helps **Developers** and **QA/Testing** improve review, testing, and workflow practices.
- Escalates persistent organizational blockers that exceed team authority.

---

## Business Analyst / Requirements Analyst

### Role Summary
The Business Analyst or Requirements Analyst translates stakeholder needs into clear, testable requirements and maintains traceability from outcomes to delivered work.

### Responsibilities
- Clarify business needs, users, constraints, and acceptance rules
- Convert approved concepts into requirements and process examples
- Maintain traceability between requirements, backlog items, tests, and outcomes
- Validate assumptions and changes with stakeholders
- Surface requirement conflicts and unresolved decisions

### Goals
- Reduce ambiguous or reworked requirements
- Improve alignment between stakeholder needs and implementation
- Maintain a clear basis for acceptance and traceability

### Interactions with Existing Roles
- Partners with the **Product Manager** on outcome definition, prioritization, and scope.
- Validates requirements and decisions with stakeholders.
- Clarifies implementation details with **Developers** and test coverage with **QA/Testing**.
- Raises unresolved requirement risks or decisions to the **Project Manager**.

---

## UX / Design Lead

### Role Summary
The UX or Design Lead owns usability, user experience, and design-validation practices across the project.

### Responsibilities
- Define user flows, interaction patterns, and design requirements
- Validate designs through reviews and appropriate user research
- Communicate usability trade-offs and accessibility considerations
- Maintain design consistency and reusable patterns
- Document design decisions and unresolved risks

### Goals
- Improve usability and accessibility
- Reduce late-stage design rework
- Deliver consistent experiences across features

### Interactions with Existing Roles
- Aligns customer needs and prioritization with the **Product Manager**.
- Works with **Developers** on feasibility, implementation details, and design review.
- Contributes test scenarios and acceptance evidence with **QA/Testing**.
- Coordinates research and significant trade-offs with stakeholders and the **Project Manager**.

---

## Data / Analytics Lead

### Role Summary
The Data or Analytics Lead defines outcome metrics, measurement plans, and evidence needed to evaluate project success.

### Responsibilities
- Define success and health metrics for project outcomes
- Design instrumentation and reporting requirements
- Validate data quality and interpretation
- Analyze adoption, performance, and other project signals
- Recommend measurable experiments and follow-up improvements

### Goals
- Enable evidence-based decisions
- Ensure reliable measurement of agreed outcomes
- Identify unintended impacts early

### Interactions with Existing Roles
- Works with the **Product Manager** to define and prioritize success metrics.
- Partners with **Developers** on telemetry, instrumentation, and data availability.
- Provides reports and evidence to the **Project Manager** and stakeholders.
- Collaborates with **QA/Testing** on data quality, validation, and acceptance checks.

---

## Support / Operations Lead

### Role Summary
The Support or Operations Lead prepares operational readiness and feeds production insights back into delivery planning.

### Responsibilities
- Define support, monitoring, runbook, and escalation needs
- Prepare support teams for new features and known issues
- Triage and communicate operational issues
- Identify recurring problems and improvement opportunities
- Support release handoff and post-release stability checks

### Goals
- Improve operational readiness and time to resolution
- Reduce avoidable production support burden
- Turn production experience into actionable improvements

### Interactions with Existing Roles
- Coordinates deployment handoff with the **Release Manager**.
- Shares operational risks and defect feedback with **Developers** and **QA/Testing**.
- Provides incident and support trends to the **Project Manager** for planning and escalation.
- Raises customer impact and unmet outcomes to the **Product Manager** and stakeholders.

---

## Security / Compliance Lead

### Role Summary
The Security or Compliance Lead identifies security and compliance requirements, assesses related risks, and advises the team on acceptable controls and approvals.

### Responsibilities
- Define applicable security, privacy, and compliance requirements
- Review designs and implementation for relevant risks
- Define required evidence, assessments, and approvals
- Advise on mitigations and residual risk
- Coordinate incident and regulatory escalation when applicable

### Goals
- Reduce security and compliance exposure
- Make risk decisions explicit and evidence-based
- Embed controls without unnecessary delivery disruption

### Interactions with Existing Roles
- Works with **Developers** to define and review technical controls.
- Partners with **QA/Testing** on security checks and acceptance evidence.
- Advises the **Project Manager** on risk, schedule, and escalation needs.
- Helps the **Product Manager** evaluate customer, product, and compliance trade-offs.
- Engages stakeholders when risk acceptance or approvals are required.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Project teams should assign the roles needed for their scale and avoid duplicating ownership across personas.
