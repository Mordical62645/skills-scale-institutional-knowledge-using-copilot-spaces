# OctoAcme Personas & Roles

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
- Participate in daily standups and sprint planning

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
- Partner with Project Manager on planning and execution
- Review and sign off on release readiness

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs
- Monthly stakeholder updates

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
- Escalate blockers and dependencies
- Track progress against milestones and metrics

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Testing Specialists

### Role Summary
QA/Testing specialists validate software quality and ensure all deliverables meet acceptance criteria before release. They collaborate with developers, product managers, and operations teams.

### Responsibilities
- Develop and maintain test plans aligned with acceptance criteria
- Execute manual and automated testing across all environments
- Manage test data and environments
- Identify, document, and verify resolution of defects
- Participate in definition of acceptance criteria during planning
- Validate pre-release requirements and smoke tests
- Provide feedback on testability and quality standards
- Support post-deployment verification

### Goals
- Ensure all releases meet quality and acceptance standards
- Reduce production defects and regressions
- Build confidence in deployment safety

### Typical Communication
- Participation in planning and definition of done workshops
- Test result summaries and defect reports
- Daily standup updates on QA blockers
- Sign-off on release readiness

---

## Tech Leads / Engineering Leads

### Role Summary
Tech Leads provide technical direction and leadership on complex initiatives. They collaborate with product and project management while maintaining code quality and architectural integrity.

### Responsibilities
- Provide technical guidance on design, architecture, and trade-offs
- Identify and advocate for addressing technical debt
- Mentor developers and review code quality
- Assess technical feasibility and risks
- Collaborate on estimation and capacity planning
- Lead design reviews and technical discussions
- Support incident response and root-cause analysis

### Goals
- Maintain technical excellence and system health
- Reduce technical risk and complexity
- Ensure scalable, maintainable solutions

### Typical Communication
- Technical design discussions and architecture reviews
- Code review and mentoring
- Risk register input on technical issues
- Participation in sprint planning and retrospectives

---

## Stakeholders & Sponsors

### Role Summary
Stakeholders and Sponsors provide business context, approval, and oversight. They ensure projects align with organizational priorities and receive timely updates on progress and risks.

### Responsibilities
- Define business goals and success criteria in collaboration with Product Manager
- Provide business and domain expertise during planning
- Approve go/no-go decisions at initiation and milestone gates
- Review and approve project charter and resource allocation
- Receive regular status updates and escalations
- Make trade-off decisions on scope, timeline, and resources
- Participate in retrospectives and lessons learned

### Goals
- Ensure projects deliver business value and ROI
- Maintain visibility and control over project direction
- Support team success through timely decision-making

### Typical Communication
- Kickoff and checkpoint meetings
- Monthly stakeholder updates
- Escalation of business-critical blockers
- Retrospective participation

---

## Security Lead / Security Officer

### Role Summary
Security Leads ensure that projects incorporate security best practices and maintain compliance. They are involved in planning, review, incident response, and release verification.

### Responsibilities
- Conduct or review security assessments for new features
- Define security requirements and acceptance criteria
- Monitor and oversee security scanning in CI/CD pipelines
- Review pre-release security checklist
- Lead security incident response and triage
- Provide security training and guidance to team
- Maintain security documentation and runbooks

### Goals
- Prevent security vulnerabilities and breaches
- Ensure compliance with security standards and policies
- Enable rapid incident response and recovery

### Typical Communication
- Security requirement input during planning
- Security scanning results and remediation tracking
- Incident response coordination
- Post-incident blameless retrospectives

---

## Support / Operations Lead

### Role Summary
Support and Operations Leads manage production systems, customer communication, and incident response. They are critical partners during planning and release activities.

### Responsibilities
- Define operational requirements (logging, monitoring, runbooks)
- Participate in release planning and pre-deployment coordination
- Execute deployment activities (or coordinate with DevOps/SRE)
- Manage post-deployment verification and monitoring
- Lead incident triage and response coordination
- Provide customer-facing incident communication
- Capture operational metrics and post-incident action items

### Goals
- Maintain system reliability and uptime
- Rapidly triage and resolve production incidents
- Minimize customer impact during incidents

### Typical Communication
- Operational requirements input during planning
- Deployment coordination and release notes
- Incident response and escalation
- Post-incident retrospectives

---

## Cross-Functional Collaboration Matrix

| Activity | PM | PdM | Developers | QA | Tech Lead | Stakeholder | Security | Support |
|----------|----|----|-----------|-----|-----------|-------------|----------|---------|
| Project Initiation | Lead | Collaborate | — | — | — | Approve | Consult | Consult |
| Planning & Kickoff | Lead | Lead | Participate | Participate | Participate | Approve | Consult | Consult |
| Design Review | Facilitate | Input | Lead | Input | Participate | — | Consult | — |
| Execution | Track | Monitor | Execute | Execute | Guide | — | Monitor | — |
| Testing & QA | Track | Input | Collaborate | Lead | Consult | — | Consult | — |
| Security Review | Coordinate | Input | Consult | Consult | Participate | — | Lead | — |
| Release Planning | Lead | Lead | Input | Input | Input | Approve | Lead | Lead |
| Deployment | Coordinate | Sign-off | Support | Verify | Support | Notify | Monitor | Execute |
| Incident Response | Coordinate | Notify | Support | Verify | Lead | Escalate | Lead | Lead |
| Retrospective | Facilitate | Participate | Participate | Participate | Participate | Participate | Participate | Participate |

---

## How These Personas Are Used

- Use these persona definitions to frame scenarios and sample interactions in exercises
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance
- Reference this document when defining responsibilities in project charters and team structures
- Use the collaboration matrix to clarify handoffs and decision points

---

## Related Documentation
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)