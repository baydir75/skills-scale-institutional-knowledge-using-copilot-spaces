# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

Role assignment may vary by project size, complexity, and risk. Smaller efforts may combine multiple responsibilities into one role, while larger or higher-risk efforts may assign dedicated owners for product, delivery, design, architecture, release, security, and support concerns.

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

## Executive Sponsor

### Role Summary
The Executive Sponsor provides strategic backing, confirms priority and funding, and helps resolve business-critical escalations that the delivery team cannot unblock on its own.

### Responsibilities
- Confirm the project aligns to business goals and expected outcomes
- Approve major scope, funding, or timeline changes
- Remove organizational blockers and support cross-functional alignment
- Participate in major decision gates during initiation, planning, and release readiness

### Goals
- Ensure the initiative delivers measurable business value
- Maintain executive alignment on priority and trade-offs
- Reduce delays caused by unresolved organizational decisions

### Typical Communication
- Sponsor reviews and milestone decision meetings
- Escalation discussions with Project Managers and Product Managers
- Stakeholder briefings on progress, risks, and decisions needed

### Decision Rights / Accountability Boundaries
- Accountable for strategic sponsorship, business priority, and escalation support
- Approves major investment, scope, or timeline changes when team-level trade-offs are insufficient
- Does not manage day-to-day backlog, implementation, or test execution

### Lifecycle Touchpoints
- Initiation: validates business need and approves moving into planning
- Planning: confirms priority, funding, and major milestones
- Execution: resolves business-impacting escalations
- Release: reviews readiness for high-visibility launches when needed
- Retrospective: reviews major lessons learned and follow-up actions for future investment decisions

### Key Interactions & Handoffs
- Receives project status, risks, and escalation requests from Project Managers
- Aligns with Product Managers on desired outcomes, priority, and business trade-offs
- Supports Stakeholders when decisions require executive sponsorship or cross-org coordination

---

## Business Analyst

### Role Summary
The Business Analyst translates business needs into detailed requirements, process flows, and acceptance criteria that the delivery team can plan, build, and test effectively.

### Responsibilities
- Document business workflows, requirements, assumptions, and dependencies
- Refine scope details and support backlog readiness
- Clarify acceptance criteria with Product Managers, Developers, and QA/Testing
- Identify process impacts, edge cases, and cross-team dependencies

### Goals
- Reduce ambiguity in requirements and handoffs
- Improve backlog quality and shared understanding
- Help the team deliver behavior that matches real business processes

### Typical Communication
- Backlog refinement and planning sessions
- Requirements reviews, process walkthroughs, and decision logs
- Clarification threads with Product Managers, Developers, QA/Testing, and Stakeholders

### Decision Rights / Accountability Boundaries
- Accountable for requirement clarity, traceability, and process detail
- Recommends workflow and acceptance updates based on business analysis
- Does not own final product priority, delivery scheduling, or technical design decisions

### Lifecycle Touchpoints
- Initiation: helps define current-state problems and business context
- Planning: refines requirements, process details, and acceptance criteria
- Execution: answers implementation and testing questions as details emerge
- Release: confirms process impacts and readiness for affected teams
- Retrospective: identifies requirement gaps and process improvements

### Key Interactions & Handoffs
- Works with Product Managers to turn goals into actionable backlog items
- Hands clarified requirements and edge cases to Developers and QA/Testing
- Gives Project Managers dependency and scope detail needed for planning
- Confirms business-process impacts and open questions with Stakeholders

---

## UX/UI Designer or User Researcher

### Role Summary
The UX/UI Designer or User Researcher represents user needs, validates workflows and usability, and helps the team make evidence-based experience decisions.

### Responsibilities
- Create or validate user flows, wireframes, prototypes, or research findings
- Identify usability risks, accessibility concerns, and experience gaps
- Support acceptance criteria with user-centered scenarios
- Provide design guidance during implementation and release readiness

### Goals
- Improve usability, accessibility, and customer confidence
- Ensure solutions solve the right user problem with minimal friction
- Provide evidence for product and delivery trade-offs

### Typical Communication
- Discovery sessions, design reviews, and usability readouts
- Collaboration with Product Managers on priorities and outcomes
- Implementation reviews with Developers and acceptance reviews with QA/Testing

### Decision Rights / Accountability Boundaries
- Accountable for user-experience guidance, research insight, and design intent
- Recommends workflow, interaction, and usability changes based on evidence
- Does not own delivery scheduling or final business-priority decisions

### Lifecycle Touchpoints
- Initiation: contributes user problem framing and early discovery insight
- Planning: shapes workflows, scenarios, and usability-focused acceptance criteria
- Execution: reviews implementation against design intent and accessibility needs
- Release: helps validate release notes, support content, and critical user flows
- Retrospective: shares user feedback and experience learnings

### Key Interactions & Handoffs
- Partners with Product Managers on problem definition, solution options, and success signals
- Provides Developers with design intent, workflows, and clarifications during build
- Works with QA/Testing to define usability, accessibility, and journey-based checks
- Shares Stakeholder-ready prototypes, findings, or experience trade-offs where needed

---

## Technical Lead or Architect

### Role Summary
The Technical Lead or Architect guides technical direction, design decisions, non-functional requirements, and technical risk management across the project lifecycle.

### Responsibilities
- Define or review solution architecture and key technical decisions
- Identify technical risks, dependencies, and non-functional requirements
- Support estimation, sequencing, and implementation trade-offs
- Align security, reliability, scalability, and maintainability expectations

### Goals
- Deliver a sound technical approach that supports product and operational needs
- Reduce rework caused by unclear architecture or missing constraints
- Balance delivery speed with reliability, security, and long-term maintainability

### Typical Communication
- Architecture reviews, design docs, and technical decision logs
- Planning and estimation sessions with Developers and Project Managers
- Trade-off discussions with Product Managers and Security or Privacy Leads

### Decision Rights / Accountability Boundaries
- Accountable for technical direction, design coherence, and key engineering trade-offs
- Approves or recommends major architecture decisions and non-functional standards
- Does not own product priority, stakeholder approval, or final release scheduling

### Lifecycle Touchpoints
- Initiation: assesses feasibility, constraints, and major dependencies
- Planning: shapes architecture, estimates, and implementation sequencing
- Execution: guides implementation decisions and risk mitigation
- Release: validates production readiness, observability, and rollback considerations
- Retrospective: identifies technical improvement actions and architecture follow-ups

### Key Interactions & Handoffs
- Works with Developers on design, implementation patterns, and technical decisions
- Gives Product Managers feasibility input and trade-off analysis
- Shares delivery risks, dependencies, and sequencing guidance with Project Managers
- Partners with QA/Testing on test strategy for critical technical flows
- Aligns with Security or Privacy Leads on required controls and reviews

---

## Release Manager or DevOps/SRE

### Role Summary
The Release Manager or DevOps/SRE coordinates deployment readiness, operational safeguards, observability, and incident preparedness so releases can be executed safely.

### Responsibilities
- Prepare release plans, deployment windows, rollback steps, and operational checklists
- Confirm CI, deployment automation, monitoring, and smoke-test readiness
- Coordinate production readiness across engineering, QA/Testing, and support teams
- Support incident response, rollback decisions, and post-release stabilization

### Goals
- Reduce release risk and recovery time
- Improve deployment consistency, observability, and operational readiness
- Ensure customer-facing teams are ready for launch and support impacts

### Typical Communication
- Release readiness reviews and deployment checklists
- Incident channels, on-call coordination, and post-release updates
- Collaboration with Developers, QA/Testing, Project Managers, and support teams

### Decision Rights / Accountability Boundaries
- Accountable for operational readiness, deployment coordination, and rollback planning
- Can pause or recommend pausing a release when readiness checks fail
- Does not own feature priority or acceptance of business scope

### Lifecycle Touchpoints
- Initiation: identifies platform or operational constraints for new work
- Planning: helps define release approach, environments, and automation needs
- Execution: prepares pipelines, observability, and readiness evidence
- Release: coordinates deployment, validation, and rollback if needed
- Retrospective: contributes incident, release, and reliability learnings

### Key Interactions & Handoffs
- Receives deployment-ready changes and runbook details from Developers
- Coordinates QA/Testing evidence and smoke-test readiness before release
- Aligns with Project Managers on release timing, risks, and stakeholder communications
- Hands release status and incident-ready context to Customer/Support Representatives and Stakeholders

---

## Security or Privacy Lead

### Role Summary
The Security or Privacy Lead identifies security, privacy, and compliance obligations and helps the team build and validate the right controls before release.

### Responsibilities
- Identify security, privacy, data-handling, and compliance requirements
- Review risks, threat scenarios, and required mitigations
- Advise on secure design, testing scope, and release readiness
- Support incident escalation and follow-up when security or privacy concerns arise

### Goals
- Reduce security and privacy risk introduced by delivery work
- Ensure required controls are defined early and validated before release
- Improve team awareness of security and privacy responsibilities

### Typical Communication
- Risk reviews, architecture discussions, and security sign-off checkpoints
- Coordination with Technical Leads, Developers, QA/Testing, and Project Managers
- Escalation updates for incidents or unresolved control gaps

### Decision Rights / Accountability Boundaries
- Accountable for advising on security/privacy requirements and validating high-risk controls
- Can recommend blocking release when material security or privacy gaps remain
- Does not manage day-to-day implementation or business-priority decisions

### Lifecycle Touchpoints
- Initiation: identifies high-level risk, compliance, or data-classification concerns
- Planning: defines control requirements and review needs
- Execution: reviews implementation approach and validation coverage
- Release: confirms critical security/privacy checks are complete for higher-risk changes
- Retrospective: contributes lessons from incidents, findings, and control gaps

### Key Interactions & Handoffs
- Works with Technical Leads on secure architecture and control expectations
- Gives Developers clear security/privacy requirements and review feedback
- Partners with QA/Testing on validation coverage for critical controls
- Updates Project Managers on unresolved risks, needed approvals, or escalation paths
- Coordinates with Stakeholders and Executive Sponsors when risk acceptance or compliance decisions are needed

---

## Customer/Support Representative

### Role Summary
The Customer/Support Representative brings customer-impact insight into planning and release readiness and ensures support teams can respond effectively after launch.

### Responsibilities
- Share common customer pain points, support trends, and operational feedback
- Review release notes, support readiness, and customer communication needs
- Help identify likely failure modes or high-impact user scenarios
- Feed post-release issues and customer feedback into prioritization and improvement work

### Goals
- Reduce customer confusion and support disruption during change
- Improve readiness for launches, incidents, and follow-up communication
- Ensure real customer feedback informs product and process decisions

### Typical Communication
- Readiness reviews, release communication planning, and incident updates
- Feedback loops with Product Managers, Project Managers, and support teams
- Post-release summaries on customer questions, issues, and trends

### Decision Rights / Accountability Boundaries
- Accountable for support-readiness input and customer-impact communication
- Recommends support content, escalation preparation, and post-release follow-up priorities
- Does not own delivery schedules, product roadmap priority, or technical implementation decisions

### Lifecycle Touchpoints
- Initiation: shares customer pain points and recurring support themes
- Planning: reviews customer-impact assumptions and support dependencies
- Execution: prepares support content and escalation readiness
- Release: monitors customer response, incoming issues, and communication needs
- Retrospective: contributes post-release trends and improvement recommendations

### Key Interactions & Handoffs
- Gives Product Managers customer-impact insight and post-release feedback
- Coordinates with Project Managers on stakeholder communications and readiness timing
- Receives release notes, known issues, and operational guidance from Release Manager or DevOps/SRE and Developers
- Shares high-priority customer issues with QA/Testing and Developers for triage and follow-up

---

## Responsibility & Handoff Snapshot

| Role | Primary accountability | Main lifecycle touchpoints | Key handoffs / interactions |
| --- | --- | --- | --- |
| Executive Sponsor | Strategic priority, funding, escalation support | Initiation, planning, major release gates | Receives escalations from Project Managers; aligns with Product Managers and Stakeholders |
| Product Managers | Outcomes, roadmap, backlog priority | Initiation through retrospective | Hand off prioritized work to Developers, QA/Testing, and Project Managers |
| Project Managers | Plan, schedule, risks, communications | Planning through retrospective | Coordinate Stakeholders, escalate to Sponsors, align delivery teams |
| Business Analyst | Requirements detail, workflow clarity | Initiation, planning, execution | Hands clarified requirements to Developers and QA/Testing; supports Product Managers and Project Managers |
| UX/UI Designer or User Researcher | User workflows, usability, research evidence | Initiation, planning, execution, release | Gives design intent to Developers; aligns acceptance checks with QA/Testing and Product Managers |
| Technical Lead or Architect | Technical direction, non-functional requirements | Initiation through retrospective | Guides Developers; shares feasibility and risk with Product Managers, Project Managers, and Security |
| Developers | Implementation, technical quality, documentation | Planning, execution, release | Hand off build artifacts and readiness evidence to QA/Testing and Release roles |
| QA/Testing | Quality validation and acceptance confidence | Planning, execution, release | Validates work from Developers; reports readiness and defects to Product and Project Managers |
| Release Manager or DevOps/SRE | Deployment readiness, observability, rollback | Planning, execution, release, retrospective | Coordinates release evidence from Developers and QA/Testing; updates Support and Stakeholders |
| Security or Privacy Lead | Security, privacy, compliance guidance | Initiation, planning, execution, release | Defines controls with Technical Leads; shares risks with Project Managers and Sponsors when needed |
| Customer/Support Representative | Support readiness, customer-impact feedback | Planning, release, retrospective | Receives release context from Release/Development; returns feedback to Product, QA/Testing, and Project Managers |
| Stakeholders | Business input, approvals, adoption support | Initiation, planning, release | Provide inputs and approvals; receive updates from Product and Project Managers |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
