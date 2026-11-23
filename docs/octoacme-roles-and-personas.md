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

## Scrum Masters / Delivery Facilitators

### Role Summary
Scrum Masters or Delivery Facilitators help the delivery team work effectively by facilitating agreed team practices, surfacing impediments, and supporting continuous improvement. The role supports delivery and does not own product priorities or project commitments.

### Responsibilities
- Facilitate standups, planning, reviews, and retrospectives as agreed by the team
- Help identify and remove team-level impediments, escalating cross-team blockers when needed
- Encourage clear work items, collaboration, and continuous improvement
- Help the team inspect progress and adapt its ways of working

### Goals
- Improve team flow and collaboration
- Make impediments visible and support timely resolution
- Help the team maintain sustainable, predictable delivery practices

### Typical Communication
- Team ceremonies and day-to-day delivery conversations
- Impediment follow-ups with the Project Manager and relevant teams
- Retrospective action tracking with the delivery team

### Interactions with Existing Roles
- Partners with the Project Manager on delivery coordination and escalates schedule or dependency risks; the Project Manager remains accountable for the project plan and stakeholder status.
- Works with the Product Manager to ensure backlog items are ready for team discussion; the Product Manager retains prioritization and product-outcome decisions.
- Supports Developers and QA/Testing by helping surface impediments and improve team practices, without directing technical decisions or replacing quality ownership.

---

## UX / Design Leads

### Role Summary
UX / Design Leads shape user experiences by researching customer needs, defining design approaches, and validating usability. They collaborate with product and engineering roles to make solutions useful, accessible, and feasible.

### Responsibilities
- Plan or conduct user research and synthesize relevant findings
- Create and maintain user flows, prototypes, and design specifications
- Identify usability and accessibility considerations
- Review implemented experiences and share design feedback

### Goals
- Deliver usable, accessible experiences that address customer needs
- Make design decisions and trade-offs clear to the team
- Reduce rework by validating experience assumptions early

### Typical Communication
- Design reviews and collaborative planning with Product Managers and Developers
- Research summaries and prototypes shared with stakeholders
- Usability feedback during demos and acceptance reviews

### Interactions with Existing Roles
- Works with the Product Manager to connect user needs and research findings to product outcomes and backlog choices; the Product Manager retains product prioritization accountability.
- Collaborates with Developers on technical feasibility and implementation details, and with QA/Testing on experience-related acceptance checks.
- Shares design decisions and risks with the Project Manager when they affect scope, milestones, or dependencies.

---

## DevOps / Platform Engineers

### Role Summary
DevOps / Platform Engineers support reliable software delivery and operation by maintaining delivery automation, environments, platform capabilities, and operational signals.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Support development and test environments
- Improve platform reliability, observability, and operational readiness
- Advise teams on infrastructure and deployment risks
- Support operational troubleshooting and recovery activities within their area

### Goals
- Enable safe, repeatable, and efficient delivery
- Improve system reliability and visibility into service health
- Reduce avoidable deployment and environment-related blockers

### Typical Communication
- Pipeline and deployment updates with Developers
- Operational readiness and release discussions
- Reliability signals, incidents, and risks shared with the delivery team

### Interactions with Existing Roles
- Partners with Developers on build pipelines, environments, observability, and deployment needs; Developers remain responsible for the quality of their code.
- Coordinates with the Project Manager on platform dependencies, delivery risks, and release readiness.
- Works with QA/Testing to provide stable environments and support automated test execution.
- Escalates significant reliability or operational concerns through the agreed incident and risk processes.

---

## Security Leads

### Role Summary
Security Leads help teams identify and address security risks throughout planning, development, testing, and release. They provide security guidance and coordinate with the appropriate security contacts when an issue requires escalation.

### Responsibilities
- Define or advise on security requirements and controls
- Facilitate threat and security risk reviews appropriate to the work
- Review findings from security scans and help coordinate remediation
- Advise on secure design, implementation, and testing practices
- Support security incident coordination through established procedures

### Goals
- Identify security risks early and make ownership clear
- Help teams meet security requirements without delaying necessary decisions
- Ensure security issues are tracked, mitigated, and escalated appropriately

### Typical Communication
- Security reviews during planning and design
- Findings and remediation follow-ups with Developers and QA/Testing
- Escalation to Security on-call or the security incident process when required

### Interactions with Existing Roles
- Advises Developers on secure implementation and remediation; Developers remain responsible for implementing and testing code changes.
- Works with QA/Testing to include relevant security checks and validate fixes.
- Partners with the Project Manager to track security risks and dependencies, while using the established security escalation path for security incidents.
- Consults with the Product Manager when security requirements affect scope or product trade-offs.

---

## Data / Analytics Leads

### Role Summary
Data / Analytics Leads help define how product outcomes will be measured and ensure the data needed for analysis is appropriately instrumented, interpreted, and communicated.

### Responsibilities
- Translate success metrics into measurement and instrumentation needs
- Advise on event definitions, data quality, and reporting
- Analyze relevant usage or outcome data and communicate findings
- Identify limitations, privacy considerations, and risks in measurement

### Goals
- Make product outcomes measurable and interpretable
- Improve confidence in data-informed decisions
- Surface data quality issues and measurement gaps early

### Typical Communication
- Metric and instrumentation discussions with Product Managers and Developers
- Analysis summaries and dashboard reviews
- Findings shared at delivery reviews and stakeholder updates

### Interactions with Existing Roles
- Partners with the Product Manager to define success measures and interpret results; the Product Manager remains accountable for product priorities and outcome decisions.
- Works with Developers on instrumentation and data implementation, and with QA/Testing to validate that measurement behaves as expected.
- Shares data risks, dependencies, and reporting needs with the Project Manager for planning and stakeholder communication.

---

## Release Managers

### Role Summary
Release Managers coordinate release readiness and execution across the teams involved. They help ensure that release criteria, communications, and recovery plans are clear; they do not replace the authority of the designated deployment or incident responders.

### Responsibilities
- Coordinate release scope, schedule, readiness checks, and approvals
- Confirm acceptance criteria, CI, security checks, and smoke-test expectations are addressed
- Ensure release notes, stakeholder communications, and rollback or mitigation plans are prepared
- Coordinate go-live verification and capture release issues for follow-up

### Goals
- Make releases predictable, observable, and well communicated
- Ensure relevant teams understand readiness and recovery plans
- Reduce avoidable release risks and unclear handoffs

### Typical Communication
- Release readiness check-ins with Project Managers, Product Managers, Developers, QA/Testing, and DevOps / Platform Engineers
- Deployment status updates and stakeholder announcements
- Post-release verification and follow-up reviews

### Interactions with Existing Roles
- Coordinates with the Project Manager on milestones, dependencies, and stakeholder updates; the Project Manager remains accountable for overall project coordination.
- Confirms product scope and release communications with the Product Manager, who retains product prioritization and acceptance decisions.
- Works with Developers, QA/Testing, and DevOps / Platform Engineers to confirm technical readiness, test results, deployment plans, and rollback preparation.
- Follows the established incident and escalation process if release verification identifies a critical issue.

---

## Customer / Stakeholder Representatives

### Role Summary
Customer or Stakeholder Representatives provide domain knowledge, operational context, and timely feedback to help the team understand needs and validate proposed outcomes. They inform product decisions but do not replace the Product Manager's prioritization accountability.

### Responsibilities
- Explain relevant customer, business, or operational needs
- Provide timely feedback on proposals, acceptance criteria, and demonstrations
- Identify stakeholder constraints, dependencies, and impacts
- Help communicate project changes or outcomes to represented groups when appropriate

### Goals
- Ensure delivery reflects validated needs and relevant stakeholder context
- Make feedback and decisions available to the team in time to inform planning
- Support shared understanding of changes and expected outcomes

### Typical Communication
- Stakeholder interviews, planning discussions, and milestone updates
- Reviews and demos with the delivery team
- Feedback and decision follow-ups through agreed project channels

### Interactions with Existing Roles
- Provides customer and stakeholder input to the Product Manager, who owns product direction, backlog priority, and product acceptance decisions.
- Works with the Project Manager on stakeholder communication, participation, and timely decisions.
- Shares domain context with Developers and QA/Testing to clarify scenarios and validate that acceptance criteria address user needs.
- Raises new needs or scope changes through the agreed product and project decision process rather than directing unplanned work.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Teams may combine roles or assign responsibilities differently based on project size, while keeping decision ownership and escalation paths explicit.
