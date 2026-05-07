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

## QA/Testing Lead

### Role Summary
QA/Testing Leads ensure software quality through comprehensive testing strategies, validation of acceptance criteria, and coordination of quality assurance activities across the project lifecycle.

### Responsibilities
- Define and execute test plans aligned with acceptance criteria
- Coordinate manual and automated testing efforts
- Identify and triage defects with reproducible steps
- Validate quality gates before release
- Advocate for quality standards and testing best practices

### Goals
- Ensure all acceptance criteria are validated before release
- Reduce defects reaching production
- Build confidence in release readiness

### Typical Communication
- Quality status reports in weekly syncs
- Test plan documentation and defect logs
- Participation in sprint planning and release preparation

### Interaction with Existing Roles
- **Developers:** Collaborates on test coverage strategy and testable design patterns; reviews automated test execution
- **Product Managers:** Validates acceptance criteria clarity and completeness; reports on quality metrics that impact release decisions
- **Project Managers:** Provides quality status for release gates and risk escalations; participates in deployment checklists

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers embed security practices and compliance requirements throughout the project lifecycle, protecting the organization and customers from security and regulatory risks.

### Responsibilities
- Define security requirements and acceptance criteria
- Review designs and code for security vulnerabilities
- Manage compliance and regulatory obligations (GDPR, SOC 2, etc.)
- Coordinate security scanning and threat assessments
- Ensure incident response and breach notification protocols

### Goals
- Prevent security breaches and data exposure
- Maintain compliance with applicable regulations
- Build secure-by-design practices into project culture

### Typical Communication
- Security requirements in project initiation
- Code review comments and security test reports
- Risk register entries and incident escalations
- Quarterly compliance audit reports

### Interaction with Existing Roles
- **Product Managers:** Advises on security-related user needs and regulatory constraints that impact feature prioritization
- **Developers:** Provides security guidance during code review; conducts threat modeling and design reviews
- **Project Managers:** Escalates critical security risks; participates in incident response and post-mortems
- **QA/Testing Leads:** Collaborates on security test cases and vulnerability scanning integration
- **DevOps Engineers:** Validates infrastructure security controls and deployment pipeline security

---

## DevOps/Infrastructure Engineer

### Role Summary
DevOps/Infrastructure Engineers build, maintain, and optimize the infrastructure and deployment pipelines that enable teams to deliver software reliably and frequently.

### Responsibilities
- Design and manage CI/CD pipelines and deployment automation
- Maintain infrastructure and cloud resources (scaling, monitoring)
- Coordinate staging and production deployments
- Monitor system performance, reliability, and observability
- Participate in incident response and rollback procedures

### Goals
- Enable fast, reliable, repeatable deployments
- Minimize deployment-related incidents and downtime
- Improve system observability and incident response time

### Typical Communication
- Infrastructure requirements in sprint planning
- Deployment checklists and runbooks
- Infrastructure and performance metrics in dashboards
- On-call escalations and incident postmortems

### Interaction with Existing Roles
- **Developers:** Integrates code changes into CI/CD pipelines; provides feedback on deployability and performance implications
- **Project Managers:** Advises on deployment windows, rollback readiness, and infrastructure capacity for timeline planning
- **QA/Testing Leads:** Validates pre-release deployment checklist; supports staging environment setup for testing
- **Security/Compliance Officers:** Implements infrastructure security controls and access management
- **Scrum Masters:** Raises infrastructure-related impediments and coordinates deployment ceremony participation

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters/Agile Coaches facilitate agile processes, remove team impediments, and coach teams and stakeholders on agile principles to maximize delivery efficiency.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Coach the team on agile principles and practices
- Identify and escalate team impediments and blockers
- Maintain sprint board and backlog hygiene
- Mentor Project Managers and Product Managers on agile practices

### Goals
- Enable consistent, sustainable team velocity
- Build a culture of continuous improvement
- Maximize team autonomy and self-organization

### Typical Communication
- Facilitation of all team ceremonies
- Impediment logs and escalation summaries
- Retrospective action item tracking
- Coaching notes and process improvement proposals

### Interaction with Existing Roles
- **Project Managers:** Partners on planning discipline and team capacity; escalates systemic blockers
- **Product Managers:** Coaches on backlog refinement, user story writing, and stakeholder management
- **Developers:** Supports sustainable workloads and velocity consistency; facilitates technical problem-solving
- **QA/Testing Leads:** Ensures quality considerations are part of sprint planning and Definition of Done
- **Executive Sponsor:** Provides visibility to leadership on team health, velocity trends, and impediments impacting delivery

---

## Executive Sponsor

### Role Summary
Executive Sponsors provide executive-level oversight, decision authority, resource allocation, and alignment with organizational strategy for major projects.

### Responsibilities
- Approve project charter and funding
- Make executive-level trade-off decisions (scope, timeline, budget)
- Remove organizational and political blockers
- Communicate project value to board and leadership team
- Approve major scope changes and milestone decisions

### Goals
- Ensure project aligns with strategic business objectives
- Secure resources and organizational support
- Maximize business value delivery and ROI

### Typical Communication
- Monthly executive status briefings
- Approval on charter, major scope changes, and milestone decisions
- Escalation resolution for cross-organizational dependencies
- Board and stakeholder communications

### Interaction with Existing Roles
- **Project Managers:** Receives project status and escalations; provides decision authority for Level 3 blockers
- **Product Managers:** Offers strategic context to guide prioritization; approves major scope/timeline trade-offs
- **Developers:** Advocates for team resources and removes organizational impediments that affect delivery
- **All roles:** Final escalation point for project-threatening issues; provides executive air cover and resource support

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the [Team Composition Guide](./octoacme-team-composition-guide.md) for guidance on assembling teams for different project types and sizes.
- Consult the [Role Interaction Matrix](./octoacme-role-interaction-matrix.md) to understand how roles collaborate across project phases.