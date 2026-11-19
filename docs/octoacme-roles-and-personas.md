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

## UX / Design

### Role Summary
UX and design practitioners turn customer and user needs into clear, accessible, and usable experiences. Depending on the team, this work may be performed by a dedicated designer or shared across roles.

### Responsibilities
- Research user needs and map workflows or journey pain points
- Create and validate interaction designs, prototypes, and design specifications
- Apply accessibility and usability guidance
- Share design decisions, constraints, and open questions with the delivery team

### Goals
- Make product experiences useful, understandable, and inclusive
- Validate design assumptions before costly implementation

### Typical Communication
- Design reviews and prototype walkthroughs
- User research findings and usability feedback
- Collaboration in backlog refinement and acceptance-criteria discussions

### Interactions with Existing Roles
- Partners with Product Managers to connect user needs, product outcomes, and priorities
- Works with Developers and the Engineering Lead to assess feasibility and clarify design intent
- Coordinates with QA/Testing to include usability and accessibility in validation
- Shares research insights with Project Managers to inform sequencing, dependencies, and risks

---

## Engineering Lead / Technical Lead

### Role Summary
The Engineering or Technical Lead guides technical direction and helps the team make sound implementation decisions while keeping delivery risks visible.

### Responsibilities
- Facilitate architecture and technical design decisions
- Identify technical dependencies, estimates, and delivery or operational risks
- Support code quality through technical guidance and reviews
- Help Developers break down work and resolve technical blockers

### Goals
- Deliver secure, reliable, maintainable systems
- Keep technical decisions aligned with product needs and delivery constraints

### Typical Communication
- Technical design discussions and decision records
- Planning and dependency reviews with the delivery team
- Escalation of technical risks and trade-offs

### Interactions with Existing Roles
- Works with Developers on implementation choices, reviews, and technical growth
- Partners with Product Managers to explain feasibility and trade-offs without owning product priority
- Coordinates with Project Managers on estimates, sequencing, dependencies, and risk escalation
- Collaborates with QA/Testing and Release/DevOps on testability, reliability, and release readiness

---

## Release / DevOps Owner

### Role Summary
The Release or DevOps Owner coordinates the technical and operational practices that make software deployable, observable, and recoverable. This responsibility may be shared or assigned to an established engineering role.

### Responsibilities
- Coordinate deployment pipelines, environments, and release readiness checks
- Confirm rollback or mitigation plans and operational monitoring are prepared
- Support deployment execution and post-deployment verification
- Surface infrastructure, reliability, and release risks

### Goals
- Make releases repeatable, observable, and low risk
- Reduce deployment-related disruption and recovery time

### Typical Communication
- Release planning and go/no-go readiness checks
- Deployment status and post-deploy verification updates
- Incident and reliability follow-up

### Interactions with Existing Roles
- Coordinates with Developers and the Engineering Lead on build, infrastructure, and operational requirements
- Partners with QA/Testing on staging validation and smoke tests
- Updates Project Managers on release dependencies, readiness, and risks
- Works with Product Managers and stakeholders on release timing and communicates operational constraints

---

## QA / Quality Lead

### Role Summary
The QA or Quality Lead coordinates the team's approach to verifying that deliverables meet acceptance criteria and expected quality standards. Testing may be performed by a dedicated QA specialist or shared by the team.

### Responsibilities
- Plan appropriate unit, integration, end-to-end, and exploratory testing
- Clarify acceptance criteria and maintain traceability of test evidence
- Identify quality risks, defects, and gaps before release
- Promote testability and continuous quality practices throughout delivery

### Goals
- Provide timely, credible evidence that work meets its requirements
- Find important defects early and protect customer experience

### Typical Communication
- Test plans, quality reports, and defect triage
- Acceptance-criteria reviews with Product Managers
- Release readiness discussions with Developers and the delivery team

### Interactions with Existing Roles
- Works with Developers to design testable changes and resolve defects
- Partners with Product Managers to clarify expected behavior and acceptance criteria
- Coordinates with Project Managers on test dependencies, status, and quality risks
- Works with Release/DevOps Owners on smoke tests and deployment verification

---

## Security / Compliance Representative

### Role Summary
The Security or Compliance Representative helps teams understand and address applicable security, privacy, and regulatory requirements. The role may be a specialist or a designated contact from a security or compliance function.

### Responsibilities
- Identify applicable security, privacy, and compliance requirements
- Advise on risk assessment, threat modeling, and appropriate controls
- Review significant risks and help track remediation or approved exceptions
- Provide guidance on security validation and incident escalation paths

### Goals
- Address security and compliance risks early and proportionately
- Make control ownership and unresolved risks visible before release

### Typical Communication
- Security and compliance reviews during planning and design
- Risk register updates and remediation tracking
- Consultation with the security team and incident response contacts

### Interactions with Existing Roles
- Advises Product Managers on user, data, and regulatory requirements that affect scope
- Works with Developers and the Engineering Lead to identify controls and resolve technical findings
- Coordinates with Project Managers to record risk owners, mitigations, and escalation needs
- Partners with Release/DevOps and QA/Testing on security checks and release readiness; follows the security incident runbook for incidents

---

## Data / Analytics Lead

### Role Summary
The Data or Analytics Lead helps teams instrument product experiences and evaluate outcomes using reliable, appropriately governed data.

### Responsibilities
- Translate success metrics into measurement plans and instrumentation needs
- Define data-quality checks and coordinate dashboards or analysis
- Explain trends, limitations, and findings to the delivery team
- Raise privacy, data access, or interpretation concerns

### Goals
- Make project outcomes measurable and decision-useful
- Support evidence-based iteration while respecting data governance

### Typical Communication
- Metric definitions and instrumentation reviews
- Dashboard and analysis readouts at delivery or stakeholder reviews
- Data-quality and privacy discussions with relevant owners

### Interactions with Existing Roles
- Works with Product Managers to define success measures and interpret product outcomes
- Partners with Developers and the Engineering Lead on event instrumentation and data quality
- Coordinates with Project Managers on reporting cadence and milestone evidence
- Consults Security/Compliance Representatives when measurement involves sensitive or regulated data

---

## Support / Operations Representative

### Role Summary
The Support or Operations Representative brings customer-support and service-operation needs into planning, release, and post-release learning.

### Responsibilities
- Identify support workflows, operational constraints, and recurring customer pain points
- Prepare or review troubleshooting guidance, known issues, and escalation routes
- Validate support readiness before a release when needed
- Share service and customer feedback with the delivery team

### Goals
- Help customers and support teams respond effectively to changes and incidents
- Feed operational learning into product and process improvements

### Typical Communication
- Release readiness and support handoff reviews
- Incident triage and escalation updates
- Feedback summaries in product planning and retrospectives

### Interactions with Existing Roles
- Shares customer issues and support needs with Product Managers to inform priorities
- Works with Developers and the Engineering Lead to provide reproducible reports and operational context
- Coordinates with Project Managers on readiness, dependencies, and stakeholder communications
- Partners with Release/DevOps Owners on deployment notices, known issues, and incident response; works with QA/Testing to ensure critical support scenarios are covered

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
