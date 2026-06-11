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

## UX Designer

### Role Summary
UX Designers conduct user research, design user experiences, and validate usability. They collaborate closely with Product Managers and Developers to ensure the product is intuitive, accessible, and meets user needs.

### Responsibilities
- Lead user research and usability testing
- Create wireframes, prototypes, and design specifications
- Validate design decisions with users and stakeholders
- Collaborate with Developers on implementation feasibility
- Maintain design consistency and component libraries
- Advocate for user needs during planning and trade-off discussions

### Goals
- Deliver intuitive, user-centered product experiences
- Reduce support burden through clear design
- Establish design patterns and reusable components
- Continuously improve usability based on user feedback

### Typical Communication
- Sprint planning and refinement meetings (present user research insights)
- Design reviews with Developers and Product Managers
- Usability testing sessions with stakeholders
- Design documentation and component specifications

### Key Interactions
- **With Product Managers**: Align on user personas and success metrics; share research insights to inform prioritization
- **With Developers**: Review implementation against design specs; collaborate on technical feasibility of features
- **With Project Managers**: Contribute to timeline estimates for design work; escalate blockers affecting user experience

---

## Technical Writer

### Role Summary
Technical Writers own documentation strategy and execution. They work with all teams to ensure user-facing and technical documentation is clear, accurate, and accessible to support product adoption and team efficiency.

### Responsibilities
- Maintain user documentation, guides, and tutorials
- Draft and publish release notes and migration guides
- Document technical architecture and APIs
- Collaborate with teams to capture knowledge and processes
- Ensure documentation is up-to-date before releases
- Establish documentation standards and style guides

### Goals
- Reduce support tickets through clear, comprehensive documentation
- Enable self-service onboarding for new users and team members
- Maintain accuracy and consistency across all documentation
- Make knowledge discoverable and searchable

### Typical Communication
- Sprint planning to identify documentation needs
- Feature handoff meetings with Developers and Product
- Release coordination to ensure docs are ready
- Documentation reviews and feedback cycles

### Key Interactions
- **With Developers**: Understand technical details; clarify architecture and implementation for documentation
- **With Product Managers**: Learn about feature intent and user impact for context
- **With Project Managers**: Coordinate documentation delivery as part of release readiness

---

## DevOps Engineer

### Role Summary
DevOps Engineers own the CI/CD infrastructure, deployment automation, and operational reliability. They partner with Developers to build reliable delivery pipelines and support the team in troubleshooting production issues.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage infrastructure as code (IaC) and deployment environments
- Optimize build, test, and deployment processes
- Monitor system health and respond to operational incidents
- Support rollback and disaster recovery procedures
- Collaborate with Developers on reliability and observability improvements

### Goals
- Enable fast, reliable deployments to production
- Minimize deployment failures and mean time to recovery (MTTR)
- Reduce manual, error-prone deployment tasks
- Maintain secure, scalable infrastructure

### Typical Communication
- Sprint planning to understand deployment requirements
- Release coordination and go/no-go decisions
- Post-incident retrospectives and action items
- Infrastructure and automation design reviews

### Key Interactions
- **With Developers**: Support CI/CD troubleshooting; consult on logging, monitoring, and testability
- **With Project Managers**: Provide deployment timelines and risk assessments; escalate infrastructure blockers
- **With the Team**: Drive on-call rotations and incident response procedures

---

## Cross-Functional Collaboration Map

| Role | Reports/Coordinates With | Key Dependencies |
|------|-------------------------|------------------|
| **Developer** | Project Manager, Product Manager, UX Designer, DevOps Engineer | Design specs, release requirements, CI/CD pipeline health |
| **Product Manager** | Project Manager, stakeholders | User research, technical feasibility, market feedback |
| **Project Manager** | Product Manager, sponsor | Roadmap, resource allocation, team capacity |
| **UX Designer** | Product Manager, Developers | User insights, design adoption, technical feedback |
| **Technical Writer** | Product Manager, Developers, Project Manager | Feature details, release timelines, documentation reviews |
| **DevOps Engineer** | Developers, Project Manager | Build/deploy requirements, incident response, infrastructure needs |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the collaboration map when defining workflows and communication patterns across the team.
