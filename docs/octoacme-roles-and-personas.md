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

## QA / Testing Engineer

> **Note:** This role is referenced throughout OctoAcme process documentation but is formally defined here.

### Role Summary
QA/Testing Engineers validate quality, test coverage, and acceptance criteria across all deliverables.

### Responsibilities
- Define and execute test plans (unit, integration, E2E, smoke, security)
- Validate acceptance criteria against delivered features
- Own manual QA for feature acceptance
- Report and track defects through resolution
- Collaborate with developers on testability and test design

### Goals
- Ensure every release meets the Definition of Done
- Minimize defect escape rate to production
- Maintain high test coverage and observability

### Typical Communication
- Attends sprint planning and sprint demos
- Participates in PR reviews to assess testability
- Provides QA sign-off before each release

### Interactions
- **Developers:** Collaborates on test coverage, test design, and bug fixes
- **Project Manager:** Reports QA status, defect counts, and release readiness
- **Product Manager:** Validates acceptance criteria are met
- **DevOps Engineer:** Collaborates on CI test automation integration and test environment provisioning
- **Stakeholders:** Communicates quality metrics and release readiness signals

---

## Scrum Master

### Role Summary
Facilitates agile ceremonies, removes blockers, and coaches the team on agile best practices.

### Responsibilities
- Facilitate standups, sprint planning, sprint reviews, and retrospectives
- Identify and remove impediments blocking team progress
- Coach team members on agile principles and practices
- Shield the team from unplanned interruptions
- Track and report on team health and process metrics

### Goals
- Maximize team velocity and well-being
- Ensure the process is followed and continuously improved
- Reduce waste and eliminate bottlenecks

### Typical Communication
- Runs all agile ceremonies
- Escalates blockers to Project Manager when team cannot resolve them
- Maintains retrospective notes and tracks action items to completion

### Interactions
- **Project Manager:** Partners on delivery logistics, risk, and impediment escalation
- **Product Manager:** Collaborates on backlog health and sprint readiness
- **Developers:** Removes barriers and advocates for team capacity and process needs
- **QA / Testing Engineer:** Aligns on sprint readiness and acceptance criteria timing

---

## UX Designer

### Role Summary
Conducts user research, creates wireframes and mockups, defines user flows, and ensures usability across all deliverables.

### Responsibilities
- Conduct user interviews and usability testing sessions
- Create wireframes, prototypes, and detailed design specifications
- Define user flows and interaction patterns
- Participate in backlog refinement to clarify UX requirements
- Review implemented features for design fidelity before release

### Goals
- Deliver intuitive, accessible, and customer-validated experiences
- Reduce rework caused by poor or undefined UX
- Translate user needs into actionable, testable requirements

### Typical Communication
- Collaborates in backlog refinement sessions with Product Manager
- Shares design specs and interactive prototypes with Developers
- Participates in QA reviews for usability acceptance sign-off

### Interactions
- **Product Manager:** Partners on requirements definition and user research synthesis
- **Developers:** Provides design specifications and clarifies interaction intent during implementation
- **QA / Testing Engineer:** Collaborates on usability testing criteria and acceptance
- **Stakeholders:** Presents research findings, design proposals, and usability testing results
- **Customer Success Manager:** Coordinates on customer research sessions and feedback synthesis

---

## DevOps Engineer

### Role Summary
Manages CI/CD pipelines, infrastructure as code, monitoring, deployment automation, and production support.

### Responsibilities
- Design, build, and maintain CI/CD pipelines
- Manage cloud infrastructure and environment configuration
- Automate deployment, rollback, and scaling processes
- Configure monitoring, alerting, and observability tooling
- Support incident response and on-call rotations

### Goals
- Ensure fast, reliable, and repeatable deployments
- Minimize MTTR (mean time to recovery) for production incidents
- Enable developer self-service for deployments and environment provisioning

### Typical Communication
- Coordinates with Project Manager on release windows and deployment scheduling
- Collaborates with Developers on build requirements and environment issues
- Supports QA on test environment provisioning and configuration

### Interactions
- **Developers:** Collaborates on pipeline integration, environment configuration, and deployment troubleshooting
- **QA / Testing Engineer:** Integrates test automation into CI pipelines and provisions test environments
- **Project Manager:** Advises on deployment risk, release readiness, and production incident status
- **Security Lead:** Follows guidance on infrastructure security controls and compliance requirements

---

## Data Analyst

### Role Summary
Designs and maintains data collection and metrics pipelines, analyzes usage data, and prepares insights reports for stakeholders.

### Responsibilities
- Define and implement success metrics and data collection strategies
- Build dashboards and reports for key signals (errors, latency, usage, feature adoption)
- Analyze data to surface trends and inform product decisions
- Support post-release validation by measuring metric changes against baselines

### Goals
- Ensure project success metrics are measurable and consistently tracked
- Enable data-informed prioritization for the product team
- Reduce time-to-insight for product and business stakeholders

### Typical Communication
- Shares dashboards and metric reports in weekly stakeholder updates
- Collaborates in backlog refinement to define instrumentation requirements
- Presents insights and trend analysis to Product Manager and Stakeholders

### Interactions
- **Product Manager:** Supports measurement of success metrics and outcome validation
- **Developers:** Collaborates on instrumentation, event tracking, and data pipeline implementation
- **Stakeholders:** Provides regular insights reports and dashboards
- **DevOps Engineer:** Collaborates on data pipeline infrastructure and observability tooling

---

## Customer Success Manager

### Role Summary
Acts as the end-user advocate, channels customer feedback into requirements, and supports post-release onboarding and education.

### Responsibilities
- Gather, document, and prioritize customer feedback
- Serve as escalation point for customer-reported issues
- Coordinate post-release onboarding, training, and change management
- Communicate product changes to customers
- Represent the customer voice in backlog prioritization discussions

### Goals
- Maximize customer adoption and satisfaction with delivered features
- Reduce time-to-value for customers adopting new functionality
- Minimize churn caused by usability or communication gaps

### Typical Communication
- Shares customer feedback summaries in the weekly PM/PdM sync
- Escalates critical customer issues to Project Manager and Product Manager
- Coordinates release announcements and customer communications

### Interactions
- **Product Manager:** Communicates user issues and feedback for prioritization
- **Project Manager:** Escalates urgent customer issues that require delivery intervention
- **QA / Testing Engineer:** Interfaces on bug validation and reproduction steps
- **UX Designer:** Coordinates on customer research sessions and design feedback

---

## Security Lead

### Role Summary
Designs security controls and policies, reviews code and architecture for vulnerabilities, and coordinates incident response.

### Responsibilities
- Define and enforce security standards and policies across the project
- Conduct threat modeling and security architecture reviews
- Review PRs and infrastructure changes for security issues
- Lead security incident response and post-incident reviews
- Coordinate security scanning requirements in CI pipelines
- Train team members on secure development practices

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure compliance with relevant security standards and policies
- Minimize blast radius and MTTR for security incidents

### Typical Communication
- Reviews high-risk PRs and architecture proposals
- Participates in release readiness reviews
- Leads security incident communications
- Advises Product Manager and Project Manager on security risk trade-offs

### Interactions
- **Developers:** Works to identify and remediate security findings in code and dependencies
- **Project Manager:** Advises on security risk and release readiness
- **Product Manager:** Advises on security risk trade-offs during prioritization
- **QA / Testing Engineer:** Collaborates on security test cases and vulnerability validation
- **DevOps Engineer:** Advises on infrastructure security controls, secrets management, and compliance
- **Stakeholders:** Escalates incidents and communicates security posture per the escalation path

---

## How these personas interact

The table below summarizes the key collaboration touchpoints between all roles.

| | Developer | Product Manager | Project Manager | QA / Testing | Scrum Master | UX Designer | DevOps Engineer | Data Analyst | Customer Success | Security Lead |
|---|---|---|---|---|---|---|---|---|---|---|
| **Developer** | — | Requirements, specs | Status, blockers | Test coverage, bug fixes | Process support | Design specs | Pipeline, infra | Instrumentation | — | Security fixes |
| **Product Manager** | Feature specs | — | Planning, alignment | Acceptance criteria | Backlog health | User research | Release coordination | Success metrics | Customer feedback | Security trade-offs |
| **Project Manager** | Status, delivery | Planning, alignment | — | QA status, release | Delivery logistics | — | Deployment windows | — | Issue escalation | Risk, readiness |
| **QA / Testing** | Test coverage, bugs | Acceptance criteria | QA status | — | Sprint readiness | Usability testing | Test environments | — | Bug validation | Security test cases |
| **Scrum Master** | Barrier removal | Backlog health | Delivery logistics | Sprint readiness | — | — | — | — | — | — |
| **UX Designer** | Design specs | Requirements | — | Usability testing | — | — | — | — | Customer research | — |
| **DevOps Engineer** | Pipeline, infra | Release coordination | Deployment windows | Test environments | — | — | — | Data pipelines | — | Infra security |
| **Data Analyst** | Instrumentation | Success metrics | — | — | — | — | Data pipelines | — | — | — |
| **Customer Success** | — | Feedback, priorities | Issue escalation | Bug validation | — | Customer research | — | — | — | — |
| **Security Lead** | Security fixes | Security trade-offs | Risk, readiness | Security test cases | — | — | Infra security | — | — | — |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

