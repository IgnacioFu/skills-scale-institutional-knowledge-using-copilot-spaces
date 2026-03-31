# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles

### Primary Delivery Roles
- **Project Manager (PM)**: coordinates delivery, schedules, risks, communications.
- **Product Manager (PdM)**: defines outcomes, prioritizes backlog, and measures success.
- **Developers**: implement features, collaborate on design and testability.
- **QA/Testing Lead**: plan and execute quality assurance; validate acceptance criteria.

### Supporting Roles
- **Business Analyst**: gathers and translates business requirements into actionable specifications.
- **Scrum Master / Process Facilitator**: removes impediments and facilitates agile ceremonies.
- **Security Officer**: defines security requirements and reviews security-sensitive changes.
- **Release Manager**: coordinates planning and execution of production releases.
- **Sponsor / Executive Stakeholder**: provides business context and makes go/no-go decisions.

For detailed role descriptions, responsibilities, and cross-functional interactions, see [`docs/octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md).

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items
- Release notes and deployment documentation

## Lifecycle (high-level)
1. **Initiation**: problem statement, stakeholders, high-level timeline.
   - Key roles: Sponsor, Product Manager, Project Manager, Business Analyst
2. **Planning**: scope, resources, milestones, dependencies.
   - Key roles: Project Manager, Product Manager, Developers, QA/Testing Lead
3. **Execution**: build, test, review, iterate.
   - Key roles: Developers, QA/Testing Lead, Scrum Master, Project Manager
4. **Release**: deploy, verify, announce.
   - Key roles: Release Manager, QA/Testing Lead, Security Officer, Developers
5. **Close & Retrospective**: capture learnings and next steps.
   - Key roles: Project Manager, Product Manager, Team, Sponsor

## Communication Cadence
- **Daily**: Standups with delivery team (led by Scrum Master or Project Manager)
- **Weekly**: PM + PdM alignment and risk review
- **Weekly**: Stakeholder status updates
- **Biweekly**: Sprint planning and retrospectives
- **Monthly**: Executive stakeholder updates
- **Ad-hoc**: Escalations and decision-making ceremonies

## Decision-Making Framework

Decisions are made using the RACI model (Responsible, Accountable, Consulted, Informed). See the Role Interaction Matrix in [`docs/octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) for decision authority by activity.

### Escalation Path
- Level 1: Team-level triage in daily standup (Scrum Master / Project Manager)
- Level 2: Project Manager escalates to Product Manager and stakeholders
- Level 3: Executive Sponsor for business-impacting decisions
- Security: Follow security incident runbook for security-related escalations

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Reference [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) when onboarding new team members.
- Use [`octoacme-role-onboarding-checklist.md`](octoacme-role-onboarding-checklist.md) to ensure clarity of responsibilities.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
