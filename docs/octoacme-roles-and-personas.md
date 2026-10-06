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

### Interactions with Other Roles
- Works closely with QA/Testing Lead on test coverage and acceptance criteria
- Collaborates with Technical Lead/Architect on design and system decisions
- Partners with Operations/DevOps Engineer on deployment and observability
- Receives requirements and priority guidance from Product Manager
- Updates Project Manager on progress, blockers, and timeline risks

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

### Interactions with Other Roles
- Aligns with Stakeholder/Sponsor on business objectives and success metrics
- Works with Project Manager on timeline and release planning
- Collaborates with Technical Lead/Architect on feasibility and technical constraints
- Partners with QA/Testing Lead on acceptance criteria and validation approach
- Provides guidance to Developers on feature priorities and requirements

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

### Interactions with Other Roles
- Reports status and escalates blockers to Stakeholder/Sponsor
- Coordinates with all team members on timelines and dependencies
- Works with Scrum Master/Agile Coach on process facilitation
- Tracks and mitigates risks identified by technical and QA teams
- Ensures Business Analyst requirements are integrated into planning

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality strategy and acceptance validation for projects. They collaborate with product and development teams to ensure features meet acceptance criteria and maintain system quality standards.

### Responsibilities
- Define and execute comprehensive test plans aligned with project scope
- Establish acceptance criteria validation processes and QA workflows
- Identify and document quality gaps, regression risks, and edge cases
- Coordinate with developers on test coverage, automation, and testability
- Conduct smoke tests, integration tests, and user acceptance testing (UAT) before release
- Report quality metrics, defect trends, and test coverage status
- Manage test data, test environments, and quality tooling

### Goals
- Ensure zero critical bugs reach production
- Maintain clear visibility into quality status and test coverage
- Enable fast, confident releases through comprehensive validation
- Reduce post-release incidents and support burden

### Typical Communication
- Weekly QA sync with development and product teams
- Test results and defect reports in project board
- Quality metrics included in stakeholder status updates
- Pre-release sign-off on acceptance criteria completion

### Interactions with Other Roles
- Defines acceptance criteria in collaboration with Product Manager
- Works with Developers on testability, test coverage, and automation strategy
- Coordinates with Technical Lead/Architect on test environment setup
- Reports quality status to Project Manager for release planning
- Partners with Operations/DevOps Engineer on production validation and monitoring
- Receives test requirements from Business Analyst

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, strategic direction, and approvals for projects. They own the business case and success metrics, representing the customer or organizational needs.

### Responsibilities
- Define business objectives, success metrics, and desired outcomes
- Provide approvals at key project gates and decision milestones
- Escalate business-critical blockers and risks
- Communicate project outcomes and ROI to leadership and customers
- Advocate for resources, priority alignment, and organizational support
- Validate that delivered solutions meet business requirements

### Goals
- Maximize business value delivery and ROI
- Ensure organizational alignment on priorities and trade-offs
- Reduce business risk and market uncertainty
- Enable stakeholder confidence and buy-in

### Typical Communication
- Monthly stakeholder updates and executive summaries
- Escalation paths for business-blocking issues
- Gate approval at project milestones
- Go/no-go decisions on release readiness

### Interactions with Other Roles
- Aligns with Product Manager on business objectives and priorities
- Escalates risks and blockers from Project Manager
- Provides final approval for major releases and go-live decisions
- Reviews success metrics achievement with QA/Testing Lead
- Advocates for business needs to Technical Lead/Architect

---

## Technical Lead/Architect

### Role Summary
Technical Leads and Architects guide technical decisions, system design, and scalability planning. They ensure solutions are technically sound, maintainable, and aligned with organizational standards.

### Responsibilities
- Provide technical guidance and design review for features and components
- Evaluate technical trade-offs and recommend solutions for complex problems
- Define architecture, design patterns, and coding standards
- Assess technical feasibility and identify scalability concerns
- Plan for system reliability, performance, and security
- Mentor developers on technical best practices and design principles
- Identify technical risks and propose mitigation strategies

### Goals
- Deliver technically sound, scalable, and maintainable solutions
- Reduce technical debt and rework
- Ensure system reliability and performance under load
- Foster a culture of continuous technical improvement

### Typical Communication
- Technical design documents and architecture decision records (ADRs)
- Code review feedback and design guidance
- Technical risk assessments in project risk registers
- Architecture reviews and technical deep-dives with team

### Interactions with Other Roles
- Collaborates with Developers on design decisions and code quality
- Works with QA/Testing Lead on testability and test environment design
- Advises Project Manager on technical risks and timeline impacts
- Partners with Operations/DevOps Engineer on deployment and infrastructure requirements
- Provides feasibility input to Product Manager on scope and requirements
- Advises Business Analyst on technical constraints and implementation options

---

## Operations/DevOps Engineer

### Role Summary
Operations and DevOps Engineers manage deployment pipelines, infrastructure, and production monitoring. They ensure reliable, secure, and efficient delivery of software to production environments.

### Responsibilities
- Design and maintain deployment pipelines and CI/CD infrastructure
- Manage production environments, monitoring, and alerting systems
- Execute deployments and coordinate rollback procedures
- Implement infrastructure-as-code and configuration management
- Monitor system performance, availability, and security posture
- Troubleshoot production issues and collaborate on incident response
- Automate operational tasks and improve deployment reliability

### Goals
- Enable fast, reliable, and repeatable deployments
- Maintain high system availability and performance
- Reduce deployment risk and incident response time
- Optimize infrastructure costs and resource utilization

### Typical Communication
- Deployment coordination meetings and release checklists
- Monitoring dashboards and alerting systems
- Incident response and post-incident retrospectives
- Infrastructure and deployment documentation

### Interactions with Other Roles
- Coordinates with Developers on deployment requirements and CI/CD configuration
- Works with Technical Lead/Architect on infrastructure design and standards
- Partners with QA/Testing Lead on production validation and smoke tests
- Reports infrastructure and deployment status to Project Manager
- Escalates production issues and outages to appropriate teams
- Implements security and compliance requirements from organizational standards

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical solutions. They gather requirements, clarify scope, and ensure alignment between what is built and what is needed.

### Responsibilities
- Conduct stakeholder interviews and gather business requirements
- Document functional and non-functional requirements clearly
- Create user stories, acceptance criteria, and use cases
- Analyze requirements for completeness, clarity, and feasibility
- Identify dependencies and potential scope issues early
- Validate solutions against business requirements
- Support communication between business and technical teams

### Goals
- Ensure built solutions truly solve business problems
- Reduce rework and scope creep through clear requirements
- Enable faster decision-making through thorough analysis
- Improve stakeholder satisfaction and product adoption

### Typical Communication
- Requirement documents and user story specifications
- Backlog refinement meetings and requirement walkthroughs
- Clarification questions and scope discussion forums
- Requirements traceability and change impact analysis

### Interactions with Other Roles
- Collaborates with Stakeholder/Sponsor to understand business context and constraints
- Works with Product Manager on requirements prioritization and backlog refinement
- Partners with Developers to clarify requirements and discuss feasibility
- Coordinates with QA/Testing Lead on acceptance criteria definition
- Supports Project Manager with requirements documentation and scope management
- Consults with Technical Lead/Architect on technical constraints and implementation options

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate team processes, remove blockers, and coach the organization on agile practices. They enable teams to be self-organizing and continuously improve.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove process impediments and blockers that slow team progress
- Coach team members on agile practices and self-organization
- Protect team focus and shield from external disruptions
- Track team health metrics and identify improvement opportunities
- Foster psychological safety and encourage constructive feedback
- Escalate systemic issues and organizational impediments

### Goals
- Enable high-performing, self-organizing teams
- Improve team velocity and delivery predictability
- Foster continuous learning and process improvement
- Reduce process overhead and meeting waste

### Typical Communication
- Facilitation of regular ceremonies (planning, standups, reviews, retros)
- Retrospective action items and tracking
- Coaching feedback and one-on-ones with team members
- Impediment tracking and escalation logs

### Interactions with Other Roles
- Works with Project Manager to align team ceremonies and delivery cadence
- Coaches all team members on collaboration and agile principles
- Partners with Technical Lead/Architect on technical excellence practices
- Supports QA/Testing Lead on quality and test-driven development practices
- Helps Business Analyst on requirements clarification and backlog refinement
- Escalates organizational impediments to Stakeholder/Sponsor and leadership

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the "Interactions with Other Roles" section to understand how personas collaborate and communicate.
- Use these definitions during project kickoffs and onboarding to clarify roles and responsibilities.
