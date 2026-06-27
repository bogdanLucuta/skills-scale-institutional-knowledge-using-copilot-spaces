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

## QA / Testing Lead

### Role Summary
QA/Testing Leads define and execute test strategies, ensure quality gates are met, and validate that features meet acceptance criteria before release.

### Responsibilities
- Create and maintain test plans aligned with feature acceptance criteria
- Lead manual and automated testing efforts
- Define quality standards and acceptance criteria thresholds
- Identify and document defects with reproducible steps
- Coordinate with developers on test coverage and CI/CD integration
- Conduct UAT (User Acceptance Testing) sessions with stakeholders
- Establish metrics for test coverage and defect resolution

### Interactions
- **With Developers**: Collaborate on test design, CI/CD automation, and bug resolution
- **With Product Managers**: Clarify acceptance criteria and validate feature completeness
- **With Project Managers**: Report quality status and escalate release blockers
- **With Release Engineers**: Coordinate pre-release smoke testing and production validation

### Goals
- Ship features with high confidence and minimal production defects
- Maintain rapid feedback loops without compromising quality
- Build test automation that enables fast iteration

### Typical Communication
- Weekly QA status in delivery syncs
- Daily standup updates on test execution progress
- Defect reports and quality dashboards

---

## Technical Lead / Architect

### Role Summary
Technical Leads guide architectural decisions, perform code reviews, mentor developers, and identify technical risks that could impact delivery.

### Responsibilities
- Lead technical design reviews and architecture decisions
- Mentor and unblock developers on technical challenges
- Perform code reviews focusing on design patterns, maintainability, and performance
- Identify and propose mitigations for technical risks
- Ensure consistency with platform standards and best practices
- Define technical acceptance criteria (performance, scalability, security)
- Document technical decisions and design patterns

### Interactions
- **With Developers**: Review code, unblock technical decisions, provide mentorship
- **With Product Managers**: Translate requirements into technical constraints and feasibility
- **With Project Managers**: Flag technical risks and help estimate impact on timeline
- **With Security Engineers**: Collaborate on security design and threat modeling

### Goals
- Deliver maintainable, performant, and secure code
- Reduce technical debt and rework
- Build team capability and knowledge sharing

### Typical Communication
- Design review sessions during planning
- Code review comments and pull request feedback
- Technical risk updates in weekly syncs

---

## Security Engineer

### Role Summary
Security Engineers embed security into the development lifecycle, conduct threat assessments, and ensure compliance with security standards.

### Responsibilities
- Review designs and code for security vulnerabilities
- Define security requirements and acceptance criteria
- Conduct threat modeling for new features
- Manage security scanning tools and interpret results
- Lead incident response for security issues
- Support compliance audits and regulatory reviews
- Train and advise teams on secure coding practices

### Interactions
- **With Developers**: Code review, secure coding guidance, vulnerability remediation
- **With Technical Leads**: Threat modeling and security architecture decisions
- **With Project Managers**: Escalate security blockers and coordinate remediation timelines
- **With DevOps/Release Engineers**: Integrate security scanning into CI/CD pipeline

### Goals
- Reduce security vulnerabilities and breach risk
- Embed security early in the development lifecycle
- Maintain compliance with regulatory and internal standards

### Typical Communication
- Security reviews during design phase
- Vulnerability reports and remediation guidance
- Security incidents and escalations as needed

---

## DevOps / Release Engineer

### Role Summary
DevOps and Release Engineers own deployment infrastructure, CI/CD pipelines, and the technical execution of releases to production.

### Responsibilities
- Maintain and improve CI/CD pipeline reliability and speed
- Manage staging and production environments
- Coordinate and execute release deployments
- Create and test rollback procedures
- Monitor deployment health and post-deploy verification
- Document deployment procedures and runbooks
- Integrate security and testing automation into the pipeline

### Interactions
- **With Developers**: Support environment setup, debug CI/CD failures, enable fast iteration
- **With QA/Testing Leads**: Integrate automated testing into CI/CD, support smoke tests
- **With Project Managers**: Coordinate release windows and manage deployment schedules
- **With Security Engineers**: Integrate security scanning and compliance checks

### Goals
- Enable fast, safe, and reliable releases to production
- Minimize downtime and improve mean-time-to-recovery (MTTR)
- Provide visibility into system health and performance

### Typical Communication
- Pre-release readiness reviews
- Deployment status and incident reports
- CI/CD metrics and improvement initiatives

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business alignment, funding decisions, and executive oversight for projects. They represent customer, business, or organizational interests.

### Responsibilities
- Define business requirements and constraints
- Approve project scope, budget, and timeline
- Provide executive sponsorship and remove organizational blockers
- Validate alignment with business strategy
- Participate in key decision gates and approvals
- Support stakeholder communication and change management

### Interactions
- **With Project Managers**: Receive status updates and escalations
- **With Product Managers**: Validate business requirements and success metrics
- **With Technical Leads**: Understand technical feasibility and trade-offs
- **With Development Team**: Participate in demos and user acceptance testing

### Goals
- Ensure projects deliver measurable business value
- Maintain strategic alignment and risk mitigation
- Support organizational change and adoption

### Typical Communication
- Monthly or milestone-based stakeholder briefings
- Decision gate approvals and sign-offs
- Executive dashboards and risk escalations

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate the team's agile processes, remove impediments, and foster a culture of continuous improvement and psychological safety.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Track team velocity and impediment removal
- Coach the team on agile practices and principles
- Identify and help resolve process bottlenecks
- Foster psychological safety and encourage feedback
- Track and report on team health and engagement metrics
- Guide continuous improvement initiatives

### Interactions
- **With Project Managers**: Align on sprint schedules and delivery metrics
- **With Development Team**: Support retrospectives and process improvements
- **With Leadership**: Report on team health and recommended process changes
- **With All Roles**: Facilitate communication and resolve interpersonal conflicts

### Goals
- Maximize team velocity and flow
- Build a high-performing, self-organizing team
- Continuously improve processes and eliminate waste

### Typical Communication
- Facilitation of daily standups and sprint ceremonies
- Weekly velocity and impediment reports
- Retrospective action items and improvement tracking

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference specific role responsibilities and interactions when defining workflows and decision points in process documentation.
- See [Role Interactions and Dependencies](./octoacme-role-interactions-and-dependencies.md) for detailed cross-functional workflows and handoff points.
