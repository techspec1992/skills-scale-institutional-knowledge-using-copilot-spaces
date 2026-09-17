# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. In addition to the core delivery roles, the project team may include specialized partners who add domain, design, quality, security, operational, and measurement expertise.

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

## UX / Product Designers

### Role Summary
UX and Product Designers turn user needs and business goals into clear experiences, flows, prototypes, and interaction decisions that can be implemented effectively.

### Responsibilities
- Frame user problems and desired outcomes
- Create wireframes, prototypes, and interaction patterns
- Collaborate with Product Managers on problem definition and prioritization
- Validate usability with user feedback and design reviews
- Partner with Developers and QA/Testing to ensure the proposed experience is feasible and testable

### Goals
- Improve usability, clarity, and customer satisfaction
- Reduce rework caused by unclear requirements or weak user flows
- Align design decisions with measurable product outcomes

### Typical Communication
- Product discovery and design reviews
- User research summaries and prototype walkthroughs
- Collaboration with PM, developers, and QA during iteration

### Interaction with Existing Roles
- Works closely with Product Managers to define customer problems and success criteria
- Supports Developers by clarifying interface expectations and edge cases
- Shares validation evidence with QA/Testing to inform acceptance and regression coverage
- Keeps Project Managers informed of design dependencies and timeline impacts

---

## Engineering Leads / Technical Leads

### Role Summary
Engineering Leads guide technical direction, implementation quality, team coordination, and technical risk management across one or more workstreams.

### Responsibilities
- Define technical approach and architecture trade-offs
- Estimate complexity and feasibility for proposed scope
- Support technical planning, sequencing, and dependency management
- Review design decisions, code quality, and implementation risks
- Help remove technical blockers and coordinate cross-team engineering needs

### Goals
- Deliver robust, maintainable technical solutions
- Balance delivery speed with technical quality and sustainability
- Reduce the likelihood of avoidable integration or rework issues

### Typical Communication
- Architecture reviews and technical planning sessions
- Dependency tracking and implementation status updates
- Escalation of technical risks to PM and Product stakeholders

### Interaction with Existing Roles
- Partners with Project Managers on delivery constraints, staffing needs, and sequencing
- Works with Product Managers on trade-offs between scope, quality, and delivery timing
- Guides Developers in technical standards and implementation decisions
- Shares risk and dependency information that informs stakeholder communication and release readiness

---

## Delivery / Release Managers

### Role Summary
Delivery or Release Managers coordinate the readiness, sequencing, and communication associated with delivering work to customers or production environments.

### Responsibilities
- Manage release schedules, deployment windows, and cross-team dependencies
- Ensure readiness criteria and rollback plans are documented
- Coordinate communication with support, stakeholders, and delivery teams before and after launch
- Track release health and post-deployment verification
- Support escalation when a release creates operational or customer impact

### Goals
- Reduce release risk and disruption
- Improve predictability and confidence in deployment execution
- Keep stakeholders aligned on timing, impact, and follow-up actions

### Typical Communication
- Release readiness check-ins and deployment briefings
- Pre/post-release updates to stakeholders and support teams
- Escalation updates when deployment risk or incident impact increases

### Interaction with Existing Roles
- Works with Project Managers on milestone timing and delivery readiness
- Coordinates with Developers and QA/Testing to confirm evidence of quality and rollout safety
- Partners with Product Managers on launch messaging, customer impact, and operational readiness
- Provides support and operational teams with the information needed for issue handling and customer communication

---

## Security / Privacy Partners

### Role Summary
Security and Privacy Partners review risks related to data handling, trust, compliance, and secure product operations.

### Responsibilities
- Evaluate security and privacy implications of planned features and changes
- Review threat models, access controls, data flows, and compliance needs
- Recommend mitigations and controls for identified risks
- Validate that high-risk changes receive appropriate review before release
- Support incident response coordination when a product issue affects trust or compliance

### Goals
- Protect customer and business data
- Reduce product risk and exposure to security incidents
- Ensure compliance with relevant standards and policies

### Typical Communication
- Security and privacy review checkpoints
- Risk escalation and remediation updates
- Collaboration during incident triage and post-incident follow-up

### Interaction with Existing Roles
- Advises Engineering Leads and Developers on secure design and safe implementation choices
- Provides Product Managers and Project Managers with risk context and escalation paths
- Coordinates with Release Managers to ensure launch readiness includes security and privacy checks
- Informs stakeholders about risk acceptance, mitigation status, and compliance implications

---

## Data / Analytics Partners

### Role Summary
Data and Analytics Partners define measurement strategies, instrumentation, dashboards, and analysis needed to evaluate product performance and business impact.

### Responsibilities
- Define metrics, event tracking, and reporting requirements
- Validate instrumentation quality and data accuracy
- Support experimentation, trend analysis, and KPI reporting
- Partner with Product Managers on success metrics and business outcomes
- Help QA/Testing verify that the product is producing trusted measurement data

### Goals
- Improve decision quality using evidence and measurable outcomes
- Make it easier to understand customer behavior and operational health
- Ensure product value is visible through transparent metrics

### Typical Communication
- KPI definition and dashboard reviews
- Measurement validation and reporting updates
- Collaboration with product, engineering, and stakeholder teams

### Interaction with Existing Roles
- Works with Product Managers to maintain alignment between stated outcomes and measured success
- Supports Developers with instrumentation requirements and debugging telemetry gaps
- Informs Project Managers and stakeholders of trends, delays, or blockers affecting measurable outcomes
- Helps QA/Testing confirm that analytics and reporting remain reliable after changes

---

## Customer Support / Operations Representatives

### Role Summary
Customer Support and Operations representatives provide frontline insight into real-world customer impact, support readiness, and operational constraints.

### Responsibilities
- Share recurring issues, customer friction, and support trends
- Help define operational readiness requirements for releases or product changes
- Contribute to runbooks, knowledge base updates, and escalation paths
- Review communications and training needs before and after rollout
- Participate in incident follow-up and service-impact discussions

### Goals
- Reduce customer confusion and service disruption
- Improve support readiness and operational resilience
- Ensure product changes match real-world usage and support constraints

### Typical Communication
- Support trends and customer feedback loops
- Release readiness and operational impact reviews
- Incident comms, triage, and after-action updates

### Interaction with Existing Roles
- Provides Product Managers and Project Managers with customer-impact context and support demand signals
- Works with Release Managers on launch readiness, communications, and customer-facing guidance
- Helps Developers and QA/Testing identify edge cases and operational risks in real-world scenarios
- Supports stakeholder communication by translating operational impact into clear business context

---

## Subject Matter Experts / Compliance / Legal Partners

### Role Summary
Subject Matter Experts, Compliance, and Legal partners validate domain-specific requirements, regulatory obligations, and policy constraints that affect project decisions.

### Responsibilities
- Review domain rules, policy constraints, and required approvals
- Validate edge cases, risk areas, and regulatory obligations
- Contribute to governance checkpoints and decision documentation
- Support issue escalation when policy or compliance implications are unclear
- Provide input on customer commitments, contracts, disclosures, and risk framing

### Goals
- Reduce avoidable policy, legal, or operational risk
- Ensure projects meet domain-specific requirements and approval standards
- Protect the organization from compliance and contractual issues

### Typical Communication
- Review checkpoints and approval workflows
- Risk and compliance escalation updates
- Participation in milestone decisions with high policy or compliance impact

### Interaction with Existing Roles
- Advises Product Managers and Project Managers on requirements and approval needs early in planning
- Works with Technical Leads and Developers to confirm constraints are reflected in implementation decisions
- Supports Release Managers and stakeholders in ensuring launch readiness includes legal and compliance requirements
- Provides guidance without replacing accountability for delivery ownership held by the product and project leads

---

## Role Interaction and Accountability

The OctoAcme project model remains anchored on clear ownership for delivery and decision-making. In general:
- Product Managers own product direction and outcome definition
- Project Managers own schedule, coordination, and communication
- Developers and Engineering Leads own implementation quality and technical execution
- QA/Testing validates readiness and quality
- Cross-functional partners such as Designers, Security, Data, Support, and Compliance are consulted or informed depending on the stage of the work

This structure helps teams maintain accountability while still enabling the specialized expertise needed for successful delivery. Documenting these additional personas improves clarity about who is responsible, who is consulted, and who needs to be informed at different points in the project lifecycle.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

