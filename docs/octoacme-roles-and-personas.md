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

## Business Analysts

### Role Summary
Business Analysts bridge the gap between stakeholders and the delivery team. They gather requirements, analyze business processes, and ensure solutions align with business needs and user expectations.

### Responsibilities
- Elicit and document business requirements from stakeholders
- Translate business needs into clear, actionable user stories and acceptance criteria
- Conduct feasibility analysis and cost-benefit assessments
- Create process flow diagrams and data models
- Facilitate requirements workshops and stakeholder interviews
- Validate that delivered solutions meet business requirements
- Collaborate with Product Managers on backlog refinement

### Goals
- Ensure accurate understanding of business needs
- Bridge communication gaps between business and technical teams
- Maximize business value through clear requirements
- Reduce rework by catching requirement issues early

### Typical Communication
- Requirements documentation and user stories
- Stakeholder interview summaries and workshop facilitation
- Regular sync with Product Managers and Project Managers
- Business process diagrams and use case specifications

### Interactions with Other Roles
- Works closely with **Product Managers** to refine product vision into detailed requirements
- Partners with **Project Managers** to ensure requirements align with project scope and timelines
- Collaborates with **Developers** to clarify requirements and validate technical feasibility
- Coordinates with **QA Lead** to ensure test cases cover all business requirements

---

## QA Lead / Test Coordinator

### Role Summary
QA Leads oversee the quality assurance strategy and testing activities. They ensure comprehensive test coverage, coordinate testing efforts across the team, and maintain quality standards throughout the development lifecycle.

### Responsibilities
- Define and maintain the overall test strategy and approach
- Coordinate test planning, execution, and reporting activities
- Design test cases, test plans, and test data requirements
- Lead exploratory testing sessions and regression testing
- Ensure integration of automated tests in CI/CD pipelines
- Track defects and quality metrics (test coverage, defect density, escaped defects)
- Facilitate go/no-go decisions based on quality gates
- Mentor team members on testing best practices

### Goals
- Ensure product quality meets defined standards before release
- Minimize production defects and customer-impacting issues
- Optimize test automation coverage and efficiency
- Foster a culture of quality across the entire team

### Typical Communication
- Test plans, test reports, and quality dashboards
- Daily standup updates on testing progress and blockers
- Defect triage meetings and severity assessments
- Quality metrics reporting in weekly syncs

### Interactions with Other Roles
- Partners with **Developers** to implement and maintain automated tests
- Works with **Business Analysts** to understand requirements and create comprehensive test scenarios
- Collaborates with **Release Manager** on release readiness and quality gates
- Reports quality status to **Project Managers** and flags risks to timelines
- Coordinates with **Operations Coordinator** on production monitoring and incident analysis

---

## Release Manager

### Role Summary
Release Managers orchestrate the end-to-end release process, ensuring smooth deployments to production. They coordinate across teams, manage release schedules, and own the deployment pipeline from staging through production.

### Responsibilities
- Plan and schedule releases across environments
- Coordinate release activities with all stakeholders
- Maintain release calendar and communicate deployment windows
- Oversee deployment checklist execution and sign-offs
- Manage rollback procedures and incident response during releases
- Ensure release notes and documentation are complete
- Monitor post-deployment health and coordinate smoke tests
- Track release metrics (deployment frequency, lead time, change failure rate)

### Goals
- Achieve zero-downtime deployments where possible
- Minimize release-related incidents and rollbacks
- Increase deployment frequency while maintaining stability
- Maintain clear communication and transparency during releases

### Typical Communication
- Release schedules and deployment notifications
- Go/no-go decision meetings before production deployments
- Post-deployment status reports and incident communications
- Release retrospectives and continuous improvement discussions

### Interactions with Other Roles
- Coordinates with **Project Managers** on release timelines and milestones
- Works with **QA Lead** to verify quality gates before release approval
- Partners with **Developers** to understand technical dependencies and risks
- Collaborates with **Operations Coordinator** on infrastructure readiness and monitoring
- Communicates with **Product Managers** on feature readiness and rollout strategies

---

## UX Designer

### Role Summary
UX Designers advocate for users by creating intuitive, accessible, and delightful product experiences. They conduct user research, design interfaces, and validate solutions through usability testing and user feedback.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, mockups, and interactive prototypes
- Design user flows, information architecture, and navigation patterns
- Maintain design systems and component libraries for consistency
- Ensure accessibility standards (WCAG) are met in all designs
- Collaborate on feature design from concept through implementation
- Validate designs with real users and iterate based on feedback
- Provide design specifications and assets to developers

### Goals
- Deliver user-centered designs that solve real user problems
- Ensure consistent and accessible user experiences
- Reduce friction and improve user satisfaction
- Balance user needs with technical and business constraints

### Typical Communication
- Design presentations and critique sessions
- User research findings and usability test reports
- Design specifications and style guides
- Regular collaboration sessions with Product and Engineering

### Interactions with Other Roles
- Collaborates closely with **Product Managers** to align design with product vision
- Works with **Business Analysts** to understand user needs and requirements
- Partners with **Developers** on design implementation and technical feasibility
- Provides input to **QA Lead** on user acceptance criteria and usability testing
- Engages with **Stakeholders** to gather feedback and validate design directions

---

## Operations Coordinator

### Role Summary
Operations Coordinators ensure the reliability, performance, and scalability of production systems. They manage infrastructure, monitor system health, coordinate incident response, and implement operational best practices.

### Responsibilities
- Monitor production systems and application performance
- Manage cloud infrastructure, capacity planning, and cost optimization
- Implement and maintain observability tools (logging, metrics, tracing)
- Coordinate incident response and on-call rotations
- Automate operational tasks and improve deployment processes
- Ensure security patches and system updates are applied
- Conduct post-incident reviews and implement improvements
- Document runbooks and operational procedures

### Goals
- Maximize system uptime and reliability
- Detect and resolve issues before they impact users
- Optimize infrastructure costs and resource utilization
- Build robust, self-healing systems

### Typical Communication
- System health dashboards and availability reports
- Incident notifications and post-mortems
- Infrastructure change requests and maintenance windows
- On-call handoff notes and escalation procedures

### Interactions with Other Roles
- Partners with **Developers** on operational requirements and production troubleshooting
- Coordinates with **Release Manager** on deployment readiness and rollback procedures
- Works with **QA Lead** on production testing and smoke test execution
- Provides infrastructure insights to **Project Managers** for capacity planning
- Collaborates with **Security team** on compliance and vulnerability management

---

## Role-Specific Templates and Checklists

### Business Analyst: Requirements Review Checklist
- [ ] Business need and objectives clearly defined
- [ ] Stakeholders identified and consulted
- [ ] User stories include clear acceptance criteria
- [ ] Edge cases and error scenarios documented
- [ ] Dependencies and integration points identified
- [ ] Requirements validated with Product Manager
- [ ] Feasibility confirmed with development team

### QA Lead: Test Readiness Checklist
- [ ] Test strategy documented and reviewed
- [ ] Test cases cover all acceptance criteria
- [ ] Test data prepared and validated
- [ ] Test environment configured and accessible
- [ ] Automated tests integrated in CI/CD pipeline
- [ ] Manual test scenarios documented
- [ ] Quality metrics baseline established
- [ ] Defect tracking and triage process in place

### Release Manager: Pre-deployment Checklist
- [ ] Release notes complete and reviewed
- [ ] All PRs merged and quality gates passed
- [ ] Deployment window scheduled and communicated
- [ ] Rollback procedure documented and tested
- [ ] Smoke test plan prepared
- [ ] Stakeholder notifications sent
- [ ] On-call team briefed
- [ ] Post-deployment verification steps defined

### UX Designer: Design Handoff Template
- **Feature/Component Name:**
- **User Problem Being Solved:**
- **Key User Flows:**
- **Design Files/Prototypes:**
- **Accessibility Requirements:**
- **Responsive Behavior:**
- **Design System Components Used:**
- **Open Questions/Decisions Needed:**
- **Success Metrics:**

### Operations Coordinator: Incident Response Template
- **Incident ID:**
- **Severity:** (Critical / High / Medium / Low)
- **Start Time:**
- **Detection Method:** (Alert / User Report / Monitoring)
- **Impact:** (Users affected, services impacted)
- **Root Cause Summary:**
- **Immediate Actions Taken:**
- **Resolution Time:**
- **Follow-up Actions:**
- **Post-Mortem Scheduled:** (Date/Time)

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

