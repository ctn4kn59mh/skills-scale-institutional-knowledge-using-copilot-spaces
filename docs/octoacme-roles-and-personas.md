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

## Extended Personas (new)

This section lists additional cross-functional roles commonly involved in delivery but not covered in the core personas above. For each persona we include: Responsibilities, Interactions (who they work with), When to involve, and Key deliverables.

### Engineering Manager
- Responsibilities:
  - Prioritize technical debt and longer-term engineering health.
  - Coordinate cross-team engineering efforts and staffing.
  - Support career growth, performance, and hiring decisions.
  - Mediate high-level design trade-offs and resourcing conflicts.
- Interactions:
  - Works with Product Manager and Project Manager on resourcing and timelines.
  - Supports Developers during planning and execution.
  - Escalates resourcing or technical impediments to Product Lead.
- When to involve:
  - During planning for large technical efforts, architecture changes, or cross-team dependencies.
- Key deliverables:
  - Team capacity guidance, technical risk assessments, staffing proposals.

### UX Researcher / Designer
- Responsibilities:
  - Lead user research and synthesize insights.
  - Define user journeys, wireframes, and high-fidelity designs.
  - Ensure accessibility and usability standards are met.
  - Validate solutions against user needs and acceptance criteria.
- Interactions:
  - Partners with Product Manager on success criteria and feature scope.
  - Hands off prototypes and specs to Developers.
  - Collaborates with QA on usability and accessibility testing.
- When to involve:
  - Early in discovery and before finalizing acceptance criteria for UX-sensitive features.
- Key deliverables:
  - Research reports, design artifacts, usability test plans/results.

### Security Engineer
- Responsibilities:
  - Perform threat modeling and security reviews for designs and releases.
  - Ensure compliance with security standards and best practices.
  - Triage and coordinate vulnerability response.
  - Review and validate CI/CD security checks.
- Interactions:
  - Consulted during planning for security-sensitive changes.
  - Collaborates with Developers and Release Engineer on remediations and scans.
- When to involve:
  - For changes that touch sensitive data, auth, networking, or infrastructure.
- Key deliverables:
  - Threat models, security review notes, remediation plans, approval/sign-off.

### Release Engineer / DevOps
- Responsibilities:
  - Own CI/CD pipelines, deployment automation, and rollback processes.
  - Maintain production runbooks and deployment playbooks.
  - Manage build/release tooling and environment configurations.
- Interactions:
  - Works with Developers to automate releases.
  - Coordinates deployments with Project Manager and notifies Support/On-call for production events.
- When to involve:
  - When planning releases, migrations, or changes to deployment topology.
- Key deliverables:
  - Deployment checklists, pipeline changes, rollback procedures, runbooks.

### Data Analyst / Data Engineer
- Responsibilities:
  - Define measurement plans and instrumentation requirements.
  - Implement or validate telemetry and data models.
  - Analyze feature impact and prepare dashboards for success metrics.
- Interactions:
  - Partners with Product Manager on success metrics and experiment design.
  - Provides analysis and dashboards to stakeholders and PMs.
- When to involve:
  - During planning for features that require quantitative validation or instrumentation.
- Key deliverables:
  - Measurement plan, dashboard artifacts, analysis reports.

### Customer Success / Support Liaison
- Responsibilities:
  - Surface customer feedback and common support issues.
  - Escalate production issues and assist with customer communications.
  - Help prepare release notes targeted at customers or support teams.
- Interactions:
  - Works with PM and Product Manager for prioritization of customer-impacting issues.
  - Communicates status and mitigations to customers and stakeholders.
- When to involve:
  - Prior to releases with customer-impacting changes or when recurring customer issues surface.
- Key deliverables:
  - Customer impact assessments, support runbooks, post-release feedback summaries.

### Technical Writer / Documentation Owner
- Responsibilities:
  - Maintain internal and public documentation, runbooks, and onboarding guides.
  - Draft release notes, API docs, and user-facing documentation.
  - Ensure docs reflect the current system state and feature usage.
- Interactions:
  - Collaborates with Developers and PMs to collect implementation details and acceptance criteria.
  - Coordinates publication with Release Engineer and Product Manager.
- When to involve:
  - Early enough for accurate docs to be available at release time.
- Key deliverables:
  - Release notes, user guides, runbooks, quickstart/onboarding docs.

### Observability / Monitoring Lead
- Responsibilities:
  - Define alerting, dashboard standards, and SLI/SLO definitions for critical flows.
  - Ensure critical features have appropriate telemetry coverage and post-deploy validation.
  - Lead monitoring improvements and incident signal definitions.
- Interactions:
  - Partners with DevOps and Developers to instrument systems and validate monitoring.
  - Supports incident response and postmortem analysis.
- When to involve:
  - During planning for changes that affect user-visible behavior or system health.
- Key deliverables:
  - Dashboard templates, alerting rules, post-deploy observability checklist.

### Compliance / Legal Liaison (if applicable)
- Responsibilities:
  - Review changes for regulatory and contractual impact.
  - Coordinate legal approvals and data handling requirements.
  - Advise on privacy, data residency, and compliance implications.
- Interactions:
  - Engaged early for compliance-sensitive work and signs off with Product Lead/Sponsor.
- When to involve:
  - For work touching regulated data, integrations subject to contracts, or legal obligations.
- Key deliverables:
  - Compliance checklists, approval records, data handling guidance.

---

### How to use the Extended Personas
- Add a short "When to involve" and "Key deliverables" subsection for each persona to make handoffs actionable.
- Link relevant extended personas from the Developer/PM/Project Manager sections where responsibilities overlap.
- Keep the core persona descriptions unchanged; the Extended Personas section augments them with operational clarity.
