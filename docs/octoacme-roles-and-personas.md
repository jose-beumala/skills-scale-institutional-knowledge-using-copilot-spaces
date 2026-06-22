# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Cross-Functional Roles

### Delivery Lead

#### Role Summary
Delivery Leads coordinate day-to-day delivery activities across teams, own the release and milestone plan, track risks and dependencies, and ensure the team stays aligned on execution priorities.

#### Responsibilities
- Maintain and communicate the release/milestone timeline
- Coordinate daily standups and cross-team delivery syncs
- Track project board status and update sprint/iteration progress
- Identify and escalate cross-team dependencies and blockers
- Own risk and issue tracking between PM and delivery team
- Facilitate handoffs between product, engineering, and QA

#### Goals
- Keep projects on track and predictable
- Minimize cross-team friction and rework
- Enable rapid issue escalation and resolution

#### Typical Communication
- Daily standups and sprint planning
- Weekly delivery status reports
- Risk and dependency updates

#### When to Involve
- At project kickoff and sprint planning
- When managing cross-team dependencies
- For weekly delivery syncs and risk reviews
- During escalations or schedule changes

#### Interactions with Other Roles
- **Project Manager** (primary): reports status, escalates risks and dependencies
- **Product Manager** (secondary): discusses scope trade-offs and priority conflicts
- **Developers & QA** (primary): coordinates delivery commitments and sprint planning
- **Technical Lead** (secondary): validates technical feasibility and design decisions
- **Stakeholders** (secondary): provides delivery and status updates

---

### Technical Lead

#### Role Summary
Technical Leads provide technical direction, make architectural decisions, ensure code quality standards, and help the team navigate technical trade-offs and risks.

#### Responsibilities
- Define or validate system architecture and design
- Approve technical changes that impact system design or scale
- Set and enforce code quality standards
- Mentor developers on technical best practices
- Identify and propose mitigations for technical risks
- Guide technology and tool selections

#### Goals
- Maintain a scalable, maintainable, secure system
- Reduce technical debt and rework
- Enable team learning and growth

#### Typical Communication
- Technical design reviews and architecture discussions
- Code review comments and pull request feedback
- Technical risk identification and mitigation planning

#### When to Involve
- During planning when assessing technical feasibility
- For design reviews before implementation
- When making significant technology or architecture choices
- For technical risk assessment and mitigation

#### Interactions with Other Roles
- **Developers** (primary): guides implementation, reviews code and design
- **Release Manager** (secondary): validates deployment readiness and technical prerequisites
- **QA Lead** (secondary): ensures testability and quality standards
- **DevOps/Platform Engineer** (primary): aligns on infrastructure and deployment requirements
- **Project Manager** (secondary): escalates if technical risks impact schedule

---

### Release Manager

#### Role Summary
Release Managers own the release planning process, coordinate deployment windows, validate pre-release checklists, and lead go/no-go decisions and rollback actions if needed.

#### Responsibilities
- Create and maintain release schedules and deployment calendars
- Validate pre-release checklists (CI passes, security scans, smoke tests, documentation)
- Coordinate deployment timing and sequence across services/teams
- Lead release communication and stakeholder notifications
- Make and document go/no-go decisions
- Own incident response and rollback decisions if needed

#### Goals
- Deliver releases with predictability and low risk
- Minimize post-release issues and rollbacks
- Maintain clear communication with stakeholders during releases

#### Typical Communication
- Release planning meetings and coordination calls
- Pre-release validation checklists and sign-offs
- Release notes and stakeholder communications
- Post-release retrospectives

#### When to Involve
- During release planning phase
- For pre-release validation and sign-off
- During deployment windows
- For post-release retrospectives

#### Interactions with Other Roles
- **DevOps/Platform Engineer** (primary): coordinates deployment execution and infrastructure prep
- **QA Lead** (primary): validates QA completion and sign-off
- **Developers** (secondary): coordinates final code changes and hotfix prioritization
- **Technical Lead** (secondary): validates technical readiness and known limitations
- **Project Manager** (secondary): reports release status and communicates any delays
- **Stakeholders** (secondary): provides release announcements and status

---

### Security Liaison

#### Role Summary
Security Liaisons surface security requirements early in projects, coordinate security reviews and scanning, and approve security-related mitigations before release.

#### Responsibilities
- Define security requirements and threat models for projects
- Run or coordinate security code reviews and scanning
- Triage and prioritize security findings
- Approve or reject proposed security mitigations
- Ensure compliance with company security policies
- Participate in incident response for security issues

#### Goals
- Prevent security vulnerabilities in production
- Align the team on security best practices
- Maintain compliance and reduce risk exposure

#### Typical Communication
- Security requirement documentation and threat models
- Security review findings and remediation tracking
- Security sign-off for releases
- Incident response coordination

#### When to Involve
- Early in project planning to identify security requirements
- During code reviews for security validation
- Before releases for security sign-off
- For any security-related escalations or incidents

#### Interactions with Other Roles
- **Technical Lead** (primary): discusses secure design and architecture decisions
- **DevOps/Platform Engineer** (primary): ensures infrastructure security and compliance
- **Developers** (secondary): coordinates remediation of security findings
- **Release Manager** (secondary): provides security sign-off gate for releases
- **Project Manager** (secondary): escalates security risks that impact timeline

---

### DevOps / Platform Engineer

#### Role Summary
DevOps and Platform Engineers maintain CI/CD pipelines, manage infrastructure-as-code, support deployments, and monitor platform health and performance.

#### Responsibilities
- Design, build, and maintain CI/CD pipelines and automation
- Manage infrastructure-as-code and deployments
- Monitor platform health, performance, and cost
- Support incident response and troubleshooting
- Create and maintain runbooks and deployment procedures
- Ensure environment parity (dev, staging, production)

#### Goals
- Enable fast, reliable, repeatable deployments
- Maintain platform stability and performance
- Reduce deployment risk and toil

#### Typical Communication
- Infrastructure and CI/CD documentation
- Deployment procedure updates and runbooks
- Incident response and post-mortems
- Platform health and performance metrics

#### When to Involve
- During planning to estimate infrastructure needs
- For CI/CD setup and pipeline configuration
- Before deployments to validate readiness
- For performance or infrastructure incidents

#### Interactions with Other Roles
- **Technical Lead** (primary): aligns on architecture and infrastructure decisions
- **Release Manager** (primary): executes deployment procedures and coordination
- **Developers** (secondary): supports CI/CD troubleshooting and environment setup
- **Security Liaison** (secondary): implements security controls and compliance measures
- **Data Analyst** (secondary): sets up monitoring and telemetry infrastructure

---

### QA Lead / Test Owner

#### Role Summary
QA Leads define test strategies, own automated and manual test plans for releases, and sign off on acceptance criteria and QA completion.

#### Responsibilities
- Define test strategy and approach (unit, integration, end-to-end, manual)
- Create and maintain test plans and test cases
- Own automated and manual QA execution
- Validate acceptance criteria and Definition of Done
- Identify and triage quality issues
- Sign off on QA completion before release

#### Goals
- Ensure features meet quality and acceptance standards
- Reduce production defects and customer-impacting issues
- Enable fast feedback loops for quality validation

#### Typical Communication
- Test plans and quality metrics
- Acceptance criteria validation
- Bug reports and quality issues
- QA sign-off for releases

#### When to Involve
- During planning to define test approach
- For acceptance criteria review and validation
- During development for test design and early validation
- Before release for final QA sign-off

#### Interactions with Other Roles
- **Developers** (primary): collaborates on testability and test automation
- **Product Manager** (primary): aligns on acceptance criteria and requirements
- **Release Manager** (primary): provides QA sign-off for releases
- **Technical Lead** (secondary): discusses testability of architecture and design
- **Data Analyst** (secondary): coordinates test data and telemetry validation

---

### Data Analyst (if applicable)

#### Role Summary
Data Analysts define success metrics, set up instrumentation and dashboards, and analyze experiment and release impact to drive data-informed decisions.

#### Responsibilities
- Define success metrics aligned with business and product goals
- Design instrumentation and telemetry collection
- Build and maintain dashboards for monitoring and reporting
- Analyze experiment and release impact
- Provide actionable insights for iteration and improvement
- Validate data quality and correctness

#### Goals
- Enable data-driven decision making
- Provide rapid feedback on feature and release impact
- Identify optimization opportunities and trends

#### Typical Communication
- Metrics definitions and success criteria
- Dashboard and reporting updates
- Analysis of experiment and release impact
- Insights and recommendations

#### When to Involve
- During project planning to define success metrics
- During execution to set up monitoring and dashboards
- After releases to analyze impact
- For ongoing optimization based on data

#### Interactions with Other Roles
- **Product Manager** (primary): aligns on success metrics and business goals
- **Developers & DevOps** (secondary): coordinates instrumentation and telemetry
- **Project Manager** (secondary): provides metrics and impact reporting
- **QA Lead** (secondary): validates test data and coverage

---

## Cross-Functional Interaction Matrix

| Role | Primary Interactions | Secondary Interactions | Key Handoffs |
|------|----------------------|------------------------|--------------|
| **Developers** | QA Lead, Technical Lead, DevOps | Product Manager, Delivery Lead | Code reviews, PR approval, QA sign-off |
| **Product Manager** | Project Manager, Delivery Lead | Developers, QA Lead, Data Analyst | Requirements, acceptance criteria, priorities |
| **Project Manager** | Delivery Lead, Stakeholders | All roles | Status, risks, escalations, timeline updates |
| **Delivery Lead** | Project Manager, Developers, QA Lead | Technical Lead, Release Manager | Sprint planning, sprint reviews, risk tracking |
| **Technical Lead** | Developers, DevOps | Release Manager, Security Liaison | Design approval, code review, architecture decisions |
| **Release Manager** | DevOps, QA Lead | Technical Lead, Developers, Security Liaison | Pre-release validation, deployment execution, go/no-go |
| **Security Liaison** | Technical Lead, DevOps | Developers, Release Manager | Security requirements, findings remediation, sign-off |
| **DevOps / Platform** | Technical Lead, Release Manager | Developers, Security Liaison | Infrastructure prep, deployment procedures, monitoring |
| **QA Lead** | Developers, Product Manager, Release Manager | Technical Lead, Delivery Lead | Test coverage, acceptance sign-off, quality metrics |
| **Data Analyst** | Product Manager, Developers, DevOps | QA Lead, Project Manager | Metrics definition, instrumentation, impact analysis |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the Interaction Matrix when planning project kickoffs to identify required participants and handoff points.
- Use the "When to Involve" section to determine the right time to engage each role in the project lifecycle.
