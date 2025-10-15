# OctoAcme Project Management Processes

Welcome to OctoAcme's project management documentation. This README provides a quick overview of how we approach project delivery, helping new and existing contributors understand our workflows, roles, and practices.

## Overview

OctoAcme follows a structured yet iterative approach to project management, emphasizing customer value, clear ownership, and continuous improvement. Our processes apply to all cross-functional projects delivering product features, services, or integrations.

### Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

OctoAcme projects follow a five-phase lifecycle:

### 1. Initiation
- Define problem statement and business need
- Identify stakeholders and champions
- Create Project One-pager with success metrics
- Establish high-level timeline and key milestones
- Conduct go/no-go decision with stakeholders

**Key Deliverable**: Project One-pager with problem, goal, success metrics, and stakeholder list

### 2. Planning
- Break work into shippable increments
- Create prioritized backlog with acceptance criteria
- Estimate scope using T-shirt sizing or story points
- Define Definition of Done (DoD)
- Identify dependencies, risks, and integration points
- Create release plan and milestone map

**Key Deliverable**: Actionable backlog with release timeline

### 3. Execution
- Daily standups (15 min) focusing on progress, blockers, dependencies
- Weekly delivery sync for progress updates and risk flagging
- Build, test, review, and iterate on features
- Track progress using project boards (Backlog → Ready → In Progress → In Review → QA → Done)
- Maintain small PRs (≤400 lines) with clear acceptance criteria
- Run automated tests and security scanning in CI

**Key Activities**: Build features, manage risks, track metrics, resolve blockers

### 4. Release & Deployment
- Verify all acceptance criteria are met
- Ensure passing CI and security scans
- Draft release notes and rollback plan
- Deploy to staging and run smoke tests
- Deploy to production (automated pipeline preferred)
- Run post-deploy verifications
- Announce release to stakeholders and support

**Key Deliverable**: Production deployment with release notes

### 5. Continuous Improvement
- Conduct retrospectives after sprints, releases, or milestones
- Capture what went well and what could be improved
- Define 2-3 prioritized action items with owners
- Track improvements in project backlog
- Measure impact and celebrate progress

**Key Deliverable**: Action items for process improvement

## Core Personas & Roles

### Project Manager (PM)
**Responsibilities**:
- Coordinate delivery activities and manage schedules
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Maintain project documentation and status reporting
- Coordinate cross-team and stakeholder communication

**Goals**: Deliver on time and within scope, minimize unplanned work, maintain transparency

### Product Manager (PdM)
**Responsibilities**:
- Define what should be built to deliver customer value
- Own product vision and prioritize backlog
- Define problem statements and success metrics
- Collaborate with stakeholders on trade-offs
- Validate solutions through user research and metrics

**Goals**: Maximize customer value and impact, ensure product-market fit

### Developers
**Responsibilities**:
- Implement features to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Identify technical risks and propose mitigations

**Goals**: Deliver reliable, maintainable code with high test coverage

### QA/Testing
**Responsibilities**:
- Validate quality and acceptance criteria
- Execute unit, integration, and end-to-end tests
- Perform manual QA for feature acceptance when needed
- Ensure security scanning is integrated in CI

**Goals**: Ensure product quality and reliability before release

### Stakeholders
**Responsibilities**:
- Provide inputs, requirements, and approvals
- Review progress and provide feedback
- Make prioritization decisions with PM and PdM

**Goals**: Ensure project aligns with business objectives

## Communication Strategies

### Regular Cadences

- **Daily standups**: 15-minute team sync on progress and blockers (twice weekly or as agreed)
- **Weekly PM + PdM sync**: Alignment on priorities and risks
- **Weekly delivery sync**: Progress updates and flagged risks
- **Monthly stakeholder updates**: High-level status and milestone progress
- **Sprint/milestone demos**: Show progress to stakeholders
- **Ad-hoc escalations**: As needed for urgent issues

### Communication Templates

**Weekly Status Update**:
- Progress this week
- Next steps
- Risks & blockers
- Asks / decisions needed

**Incident Communication**:
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident retrospective scheduled

### Escalation Paths

- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues
- **Security incidents**: Follow security incident runbook, notify Security on-call

**Standard escalation chain**: Team → PM → Product Lead → Sponsor

## Quality Assurance Practices

### Testing Strategy
- **Unit tests**: For new logic and components
- **Integration tests**: Where applicable
- **End-to-end smoke tests**: For critical flows before release
- **Security scanning**: Automated in CI pipeline
- **Manual QA**: For feature acceptance when needed

### Quality Gates
- All acceptance criteria met
- Code reviews with at least one approval
- Passing CI builds and tests
- Security scans completed without critical issues
- Definition of Done validated

### Metrics & Monitoring
- Track velocity and burndown
- Monitor success metrics from Project One-pager
- Use dashboards for key signals (errors, latency, usage)
- Review metrics in weekly syncs

## Release Management

### Release Types
- **Patch**: Hotfixes for critical production issues
- **Minor**: Incremental features and improvements
- **Major**: Significant functionality or breaking changes

### Pre-release Requirements
- All PRs merged and acceptance criteria met
- Passing CI and security scans
- Release notes drafted
- Rollback/mitigation plan documented
- Smoke tests prepared

### Deployment Process
1. Schedule deployment window (if needed)
2. Deploy to staging and verify
3. Run smoke tests
4. Deploy to production via automated pipeline
5. Execute post-deploy verifications
6. Announce release to stakeholders and support

### Rollback & Incident Response
- Trigger incident response if deployment fails
- Rollback to last known-good release if necessary
- Conduct blameless post-incident retrospective
- Document lessons learned and action items

## Key Artifacts

- **Project Charter / One-pager**: Problem, goal, success metrics
- **Roadmap and Release Plan**: High-level timeline and milestones
- **Sprint/Iteration Backlog**: Prioritized work items with acceptance criteria
- **Risk Register**: Identified risks with mitigation plans
- **Definition of Done**: Quality standards for completed work
- **Retrospective Notes**: Learnings and action items

## How to Use This Documentation

1. **Starting a new project?** Begin with [Project Initiation](octoacme-project-initiation.md)
2. **Planning phase?** See [Project Planning](octoacme-project-planning.md)
3. **During execution?** Refer to [Execution & Tracking](octoacme-execution-and-tracking.md)
4. **Managing risks?** Check [Risk Management & Communication](octoacme-risks-and-communication.md)
5. **Preparing a release?** Review [Release & Deployment Guide](octoacme-release-and-deployment.md)
6. **After a sprint?** Use [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
7. **Understanding roles?** See [Roles and Personas](octoacme-roles-and-personas.md)
8. **High-level overview?** Start with [Project Management Overview](octoacme-project-management-overview.md)

## Additional Resources

- Keep the Project Charter updated in the project repo
- Add process-specific docs to `.copilot/` for Copilot Spaces context
- Use project boards (e.g., GitHub Projects) to track work
- Maintain single source of truth for project status

---

**Questions or feedback?** Contact your Project Manager or Product Lead, or contribute improvements to these docs.
