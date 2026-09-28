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
QA/Testing Leads own the quality assurance strategy and ensure all deliverables meet acceptance criteria and quality standards. They collaborate with developers and product to define testability requirements and manage test execution.

### Responsibilities
- Create and execute test plans aligned with acceptance criteria
- Define and maintain test automation strategy
- Manage regression testing and quality gates
- Report on test coverage, defect metrics, and quality trends
- Participate in Definition of Done and acceptance criteria refinement
- Escalate quality risks and blockers

### Goals
- Ensure shipped features meet quality and acceptance standards
- Reduce defect escape rate and post-release issues
- Enable fast, confident deployments through automated testing

### Typical Communication
- Sprint planning and backlog refinement
- Test plan and execution status in standups
- Defect triage and quality metrics reports
- Acceptance criteria validation and sign-off

### Interaction with Existing Roles
- **Developers:** Collaborate on testability requirements and review test coverage; provide feedback on Definition of Done
- **Product Managers:** Validate acceptance criteria and define quality expectations; report on feature readiness
- **Project Managers:** Track quality metrics and escalate blockers; coordinate testing timelines in project schedules

---

## Technical Lead / Architect

### Role Summary
Technical Leads and Architects provide technical direction and design guidance for projects. They review technical proposals, identify risks, and mentor developers in best practices to ensure scalable, maintainable solutions.

### Responsibilities
- Provide technical direction and design guidance
- Review technical proposals and architecture decisions
- Identify technical risks and scalability concerns
- Mentor developers and drive technical best practices
- Participate in planning to estimate complexity and feasibility

### Goals
- Ensure technical solutions are scalable, maintainable, and aligned with standards
- Reduce technical debt and rework
- Foster a culture of technical excellence

### Typical Communication
- Design review meetings and technical discussions
- Architecture documentation and decision logs
- Code review feedback and mentoring sessions

### Interaction with Existing Roles
- **Developers:** Provide technical guidance, review designs, and mentor on best practices; collaborate on complexity estimation
- **Project Managers:** Advise on technical feasibility and timeline impacts; escalate technical risks
- **Product Managers:** Discuss trade-offs between features and technical implementation; inform roadmap decisions with technical constraints

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, priorities, and strategic alignment for projects. They approve scope and timelines, escalate business-level issues, and ensure projects deliver value aligned with organizational goals.

### Responsibilities
- Provide business context, priorities, and strategic alignment
- Approve scope, timeline, and resource allocation
- Escalate business-level risks and dependencies
- Review progress at key milestones and decision gates
- Communicate project status to executive leadership

### Goals
- Ensure projects deliver maximum business value and ROI
- Maintain alignment with organizational strategy
- Support team success through clear decision-making

### Typical Communication
- Kickoff meetings and decision gate reviews
- Monthly stakeholder updates and executive briefings
- Ad-hoc escalation and priority alignment

### Interaction with Existing Roles
- **Project Managers:** Collaborate on timeline and scope decisions; escalate blockers requiring business decisions
- **Product Managers:** Align on business goals and success metrics; prioritize roadmap based on business value
- **Developers & Technical Leads:** Provide context on why work is important; understand constraints and trade-offs

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers ensure projects meet security and regulatory requirements. They review designs for vulnerabilities, manage security scanning in CI/CD pipelines, and participate in incident response.

### Responsibilities
- Ensure security and regulatory compliance requirements are met
- Review design and implementation for security risks
- Manage security scanning in CI/CD pipeline
- Participate in incident response and post-incident reviews
- Advise on secure practices and standards

### Goals
- Protect systems and data from security threats
- Meet regulatory and compliance obligations
- Build a culture of security awareness

### Typical Communication
- Design and security review meetings
- Security vulnerability reports and remediation plans
- Incident response coordination and post-mortems

### Interaction with Existing Roles
- **Developers:** Review code and architecture for security risks; provide guidance on secure coding practices
- **Project Managers:** Escalate security risks and compliance requirements; track security action items
- **Technical Leads:** Collaborate on security architecture and threat modeling; advise on security patterns

---

## Operations / DevOps Engineer

### Role Summary
Operations and DevOps Engineers manage infrastructure, CI/CD pipelines, and deployment automation. They ensure environments are stable and monitored, coordinate releases, and manage incident response and rollback procedures.

### Responsibilities
- Manage infrastructure, CI/CD pipelines, and deployment automation
- Ensure environments (staging, production) are stable and monitored
- Participate in release planning and deployment execution
- Manage rollback procedures and incident response
- Monitor and optimize system performance and reliability

### Goals
- Enable fast, reliable, and safe deployments
- Maintain high system availability and performance
- Reduce time to resolution for production issues

### Typical Communication
- Release planning and deployment coordination
- Infrastructure status and monitoring dashboards
- Incident response and post-incident reviews

### Interaction with Existing Roles
- **Developers:** Manage CI/CD pipelines and deployment infrastructure; provide monitoring and performance insights
- **Project Managers:** Coordinate deployment windows and release timelines; report on deployment readiness
- **QA/Testing Leads:** Manage staging environments; coordinate smoke tests before production deployment
- **Security Officers:** Implement security scanning in pipelines; manage security patches and incident response

---

## Design / UX Lead

### Role Summary
Design and UX Leads define user experience and design specifications for features. They collaborate with product and engineering on usability, validate solutions meet user needs and accessibility standards, and ensure delightful, intuitive interactions.

### Responsibilities
- Define user experience and design specifications
- Collaborate with product and engineering on usability
- Validate solutions meet user needs and accessibility standards
- Participate in design reviews and acceptance criteria definition
- Contribute to process docs related to feature acceptance

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce user friction and support burden
- Ensure consistent design patterns and brand alignment

### Typical Communication
- Design review meetings and feedback sessions
- Wireframes, prototypes, and design specifications
- Usability testing results and iteration feedback

### Interaction with Existing Roles
- **Product Managers:** Collaborate on user needs and feature specifications; validate designs against business goals
- **Developers:** Provide design specifications and accessibility guidance; review implementation for design fidelity
- **QA/Testing Leads:** Define acceptance criteria for user experience; validate accessibility compliance
- **Stakeholders:** Present design direction and validate alignment with brand and strategy

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-functional interactions between personas highlight dependencies and communication patterns used in OctoAcme projects.
