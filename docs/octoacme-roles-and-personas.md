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

### Cross-functional Interactions
- **With QA/Testing**: Discuss acceptance criteria, review test plans, fix defects identified during testing
- **With Release Manager**: Provide status on deployment-ready features, participate in release planning
- **With Product Manager**: Clarify requirements, negotiate scope
- **With Project Manager**: Provide estimates and status updates

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

### Cross-functional Interactions
- **With Project Manager**: Align on timelines, dependencies, and resource constraints
- **With Developers**: Define acceptance criteria, provide clarification on requirements
- **With QA/Testing**: Validate testing strategies align with success metrics
- **With Stakeholders**: Present roadmap and outcomes, gather feedback
- **With Business Analyst**: Refine business requirements into product specifications

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

### Cross-functional Interactions
- **With Product Manager**: Align backlog, timeline, and prioritization
- **With Developers**: Track progress, remove blockers, manage dependencies
- **With Release Manager**: Plan deployment windows, coordinate release readiness
- **With Sponsor/Executive**: Escalate decisions, provide status updates
- **With Security Officer**: Incorporate security requirements and timelines

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and the delivery team. They translate business needs into clear, actionable requirements and validate that solutions meet business objectives.

### Responsibilities
- Gather and document business requirements from stakeholders
- Translate business needs into functional specifications
- Create user stories and acceptance criteria
- Validate that implemented solutions meet business objectives
- Identify business impacts and change management needs
- Facilitate workshops and requirements review sessions

### Goals
- Ensure alignment between business needs and delivery outcomes
- Reduce rework due to unclear or missed requirements
- Enable rapid feedback loops with stakeholders
- Document institutional knowledge for future reference

### Typical Communication
- Requirements workshops and discovery sessions
- Functional specification documents and user story templates
- Regular stakeholder reviews and walkthroughs
- Change impact assessments

### Cross-functional Interactions
- **With Product Manager**: Refine product vision into detailed requirements
- **With Developers**: Clarify acceptance criteria, answer implementation questions
- **With QA/Testing**: Define test scenarios based on business rules
- **With Stakeholders**: Elicit requirements, validate solutions
- **With Project Manager**: Provide timeline estimates for requirements gathering

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads plan and execute quality assurance activities to ensure features meet acceptance criteria and quality standards. They collaborate closely with developers and product teams to define and validate quality metrics.

### Responsibilities
- Plan testing strategy and create test cases based on acceptance criteria
- Design and execute functional, integration, and regression tests
- Perform manual and automated testing as appropriate
- Identify and document defects with clear reproduction steps
- Collaborate with developers on quality metrics and improvement areas
- Participate in release readiness reviews and sign-off
- Validate that post-deployment verifications are completed

### Goals
- Ensure product quality meets stakeholder expectations
- Identify issues early in the development cycle
- Reduce production defects and customer-impacting bugs
- Build confidence in release readiness

### Typical Communication
- Test plans and test case documentation
- Defect logs and quality reports
- Code review participation (from QA perspective)
- Daily standups and sprint reviews

### Cross-functional Interactions
- **With Developers**: Discuss acceptance criteria, review code for testability, triage defects
- **With Product Manager**: Validate that testing approach covers critical user paths
- **With Release Manager**: Confirm release readiness criteria have been met
- **With Project Manager**: Provide testing timeline and resource estimates
- **With Security Officer**: Coordinate security and compliance testing

---

## Scrum Master / Process Facilitator

### Role Summary
Scrum Masters (or Process Facilitators) enable team delivery by removing impediments, facilitating agile ceremonies, and fostering a culture of continuous improvement. They serve the team and the broader organization.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Identify and escalate team impediments and blockers
- Coach team members on agile practices and principles
- Maintain project board and sprint health metrics
- Facilitate difficult conversations and conflict resolution
- Track team velocity and identify process improvement opportunities
- Mentor junior team members on agile workflows

### Goals
- Enable team autonomy and self-organization
- Remove friction and waste from the delivery process
- Build a high-performing, collaborative team culture
- Foster continuous learning and improvement

### Typical Communication
- Facilitation of agile ceremonies (standups, planning, retros)
- Impediment tracking and removal updates
- Team health metrics and retrospective action items
- One-on-one coaching and mentorship

### Cross-functional Interactions
- **With Team Members**: Remove blockers, provide coaching on agile practices
- **With Project Manager**: Communicate team capacity and timeline concerns
- **With Product Manager**: Facilitate backlog prioritization and refinement
- **With Sponsor/Executive**: Escalate process improvements and resource needs

---

## Security Officer

### Role Summary
Security Officers ensure that projects incorporate appropriate security controls, comply with organizational and regulatory requirements, and can respond effectively to security incidents. They are strategic partners in risk mitigation.

### Responsibilities
- Define security requirements and compliance standards for projects
- Review architectural and design decisions from a security perspective
- Assess and approve security changes and dependencies
- Conduct security reviews and threat assessments
- Manage security testing and vulnerability scanning
- Coordinate incident response and post-incident reviews
- Provide security guidance and best practices to teams

### Goals
- Prevent security breaches and protect organizational data
- Ensure compliance with regulatory and organizational standards
- Enable secure delivery without slowing innovation
- Build security awareness across the organization

### Typical Communication
- Security requirements and compliance checklists
- Threat assessment documents and risk registers
- Code review comments on security-sensitive changes
- Incident response coordination and blameless retrospectives

### Cross-functional Interactions
- **With Developers**: Review code for security issues, provide secure coding guidance
- **With Project Manager**: Include security assessment timeline in project planning
- **With Release Manager**: Approve security-related changes before deployment
- **With QA/Testing**: Define security test cases and penetration testing scope
- **With Sponsor/Executive**: Communicate security risks and compliance status

---

## Release Manager

### Role Summary
Release Managers coordinate the planning, preparation, and deployment of software releases to production. They ensure releases are well-coordinated, documented, and recoverable in case of issues.

### Responsibilities
- Plan release schedules and coordinate cross-team readiness
- Prepare release notes and deployment documentation
- Manage deployment checklists and pre-flight verifications
- Coordinate deployment execution with infrastructure and support teams
- Monitor post-deployment stability and performance
- Execute rollback procedures if necessary
- Conduct post-release retrospectives to capture learnings

### Goals
- Reduce release risk and deployment failures
- Ensure clear communication of changes to stakeholders
- Enable rapid recovery from deployment issues
- Improve deployment frequency without sacrificing stability

### Typical Communication
- Release plans and deployment windows
- Release notes and migration documentation
- Pre-deployment and post-deployment checklists
- Incident and rollback communication

### Cross-functional Interactions
- **With Developers**: Confirm deployment readiness, gather release notes
- **With QA/Testing**: Verify smoke tests and release sign-off criteria
- **With Project Manager**: Communicate release timeline and dependencies
- **With Sponsor/Executive**: Announce releases and major changes to stakeholders
- **With Security Officer**: Include security approvals in release checklist
- **With Infrastructure/Operations**: Coordinate deployment execution and monitoring

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors and Executive Stakeholders provide business context, prioritization, and decision-making authority. They ensure projects align with strategic goals and have adequate resources.

### Responsibilities
- Define business objectives and success criteria
- Prioritize projects and allocate resources
- Make go/no-go decisions at project gates
- Escalate and resolve high-level business issues
- Communicate project status to senior leadership
- Ensure stakeholder alignment and buy-in
- Approve major scope or timeline changes

### Goals
- Ensure projects deliver strategic business value
- Reduce misalignment and rework due to unclear business drivers
- Make timely decisions to keep projects moving
- Maximize ROI on project investments

### Typical Communication
- Project one-pagers and business cases
- Monthly executive status reports
- Decision gate reviews (initiation, planning, release)
- Escalation communications for business-impacting issues

### Cross-functional Interactions
- **With Project Manager**: Receive status updates, make decisions on escalations
- **With Product Manager**: Align on strategic priorities and roadmap
- **With Team**: Attend key milestone reviews and retrospectives
- **With Other Sponsors**: Coordinate cross-project dependencies and resources

---

## Role Interaction Matrix (RACI)

The following matrix shows accountability and involvement for key project activities:

| Activity | PM | PdM | Developer | QA | BA | Scrum Master | Security | Release Mgr | Sponsor |
|----------|----|----|-----------|-----|-------|-------------|----------|------------|---------|
| **Initiation & Planning** |
| Define business objectives | C | R/A | I | I | R | I | C | I | A |
| Create requirements | C | R | I | I | R/A | I | C | I | I |
| Define acceptance criteria | C | R | R | R | A | I | C | I | I |
| **Execution** |
| Implement features | I | C | R/A | I | C | C | C | I | I |
| Execute testing | I | C | I | R/A | I | I | I | I | I |
| Code review | I | I | R/A | I | I | I | C | I | I |
| **Release & Deployment** |
| Prepare release | C | A | R | R | I | I | R | R/A | C |
| Approve deployment | I | I | I | C | I | I | R | R/A | A |
| Deploy to production | I | I | I | I | I | I | I | R/A | I |
| **Post-Release** |
| Monitor stability | C | C | C | C | I | I | I | R/A | I |
| Incident response | R | C | R | R | I | I | R | R | A |
| Retrospective | A | C | R | R | C | R/A | C | C | I |

**Legend**: R = Responsible | A = Accountable | C = Consulted | I = Informed

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the Role Interaction Matrix when planning communication flows and decision-making in project activities.
