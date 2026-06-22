# OctoAcme — Team Onboarding & Role Clarity Guide

## Purpose
Provide clarity on role responsibilities, handoffs, and escalation paths to enable new team members to quickly understand their role and how they fit into the project management process.

## Scope
This guide applies to all team members joining OctoAcme projects, including developers, product managers, project managers, and cross-functional support roles.

---

## Quick Role Reference

### I'm a Developer. What do I need to know?
- **Your core mission:** Build features that meet acceptance criteria and quality standards.
- **Your primary collaborators:** Technical Lead (for design/code review), QA Lead (for testing), Delivery Lead (for sprint planning).
- **Key responsibilities:**
  - Implement features and fixes according to acceptance criteria
  - Write and maintain tests for your code
  - Participate in code reviews
  - Help estimate work and identify technical risks
  - Collaborate with QA on testability
- **Success metrics:** Code quality, test coverage, cycle time, PR review speed
- **Typical handoffs:** Design approval → Implementation → Code review → QA testing → Release

---

### I'm a Product Manager. What do I need to know?
- **Your core mission:** Define what should be built to maximize customer value and business impact.
- **Your primary collaborators:** Project Manager (for planning), Developers (for feasibility), Data Analyst (for metrics).
- **Key responsibilities:**
  - Define problem statements and success metrics
  - Prioritize the roadmap and backlog
  - Write clear acceptance criteria
  - Validate solutions with users and data
  - Make data-driven prioritization decisions
- **Success metrics:** Customer adoption, impact on business metrics, roadmap velocity
- **Typical handoffs:** Problem statement → Backlog → Sprint planning → Feature validation → Impact analysis

---

### I'm a Project Manager. What do I need to know?
- **Your core mission:** Ensure projects deliver on time, on scope, and with clear communication.
- **Your primary collaborators:** Delivery Lead (for execution), all roles (for status/escalation).
- **Key responsibilities:**
  - Create and maintain project timelines and plans
  - Manage risks and escalate blockers
  - Facilitate planning and retrospective meetings
  - Report status to stakeholders
  - Coordinate cross-team dependencies
- **Success metrics:** On-time delivery, budget adherence, stakeholder satisfaction, risk identification
- **Typical handoffs:** Project charter → Plan → Weekly status → Risk escalation → Retrospective

---

### I'm a Delivery Lead. What do I need to know?
- **Your core mission:** Keep the team aligned on day-to-day execution and maintain momentum toward milestones.
- **Your primary collaborators:** Project Manager (for planning), Developers (for sprint delivery), QA Lead (for quality).
- **Key responsibilities:**
  - Run daily standups and coordinate sprint planning
  - Track sprint progress and update the project board
  - Identify and escalate blockers and dependencies
  - Maintain the release/milestone timeline
  - Facilitate handoffs between teams
- **Success metrics:** Sprint velocity, on-time sprint completion, blocker resolution time, team communication flow
- **Typical handoffs:** Sprint planning → Daily standups → Sprint review → Risk escalation → Sprint retrospective

---

### I'm a Technical Lead. What do I need to know?
- **Your core mission:** Guide technical decisions and ensure the system remains scalable, secure, and maintainable.
- **Your primary collaborators:** Developers (for implementation), DevOps (for infrastructure), Release Manager (for deployment).
- **Key responsibilities:**
  - Review and approve architectural designs
  - Set code quality and testing standards
  - Identify and propose mitigations for technical risks
  - Mentor developers on best practices
  - Validate technology and tool selections
- **Success metrics:** System reliability, code quality, technical debt reduction, team capability growth
- **Typical handoffs:** Architecture review → Code review → Technical risk assessment → Deployment validation

---

### I'm a Release Manager. What do I need to know?
- **Your core mission:** Deliver releases predictably, safely, and with minimal risk or disruption.
- **Your primary collaborators:** DevOps (for deployment), QA Lead (for validation), Developers (for hotfixes).
- **Key responsibilities:**
  - Create release schedules and coordinate timing
  - Validate pre-release checklists (CI, security, tests, docs)
  - Make go/no-go decisions
  - Coordinate deployment execution
  - Own rollback decisions and incident response
- **Success metrics:** Release frequency, deployment success rate, time to rollback, post-release issues
- **Typical handoffs:** Release planning → Pre-release validation → Deployment → Post-release verification

---

### I'm a Security Liaison. What do I need to know?
- **Your core mission:** Prevent security vulnerabilities and ensure compliance with company policies.
- **Your primary collaborators:** Technical Lead (for architecture), DevOps (for infrastructure), Developers (for code).
- **Key responsibilities:**
  - Define security requirements early in projects
  - Coordinate security reviews and scanning
  - Triage and prioritize security findings
  - Approve security mitigations before release
  - Participate in incident response for security issues
- **Success metrics:** Security findings remediation rate, compliance violations, incident prevention
- **Typical handoffs:** Security requirements → Code review → Security scan → Release sign-off

---

### I'm a DevOps / Platform Engineer. What do I need to know?
- **Your core mission:** Enable fast, reliable, repeatable deployments and maintain platform stability.
- **Your primary collaborators:** Technical Lead (for architecture), Release Manager (for deployments), Developers (for CI/CD).
- **Key responsibilities:**
  - Design and maintain CI/CD pipelines
  - Manage infrastructure-as-code and deployments
  - Monitor platform health and performance
  - Support incident response
  - Maintain runbooks and deployment procedures
- **Success metrics:** Deployment success rate, MTTR, platform uptime, CI/CD efficiency
- **Typical handoffs:** CI/CD setup → Pipeline configuration → Pre-deployment validation → Deployment execution

---

### I'm a QA Lead / Test Owner. What do I need to know?
- **Your core mission:** Ensure features meet quality and acceptance standards before release.
- **Your primary collaborators:** Developers (for testability), Product Manager (for acceptance criteria), Release Manager (for sign-off).
- **Key responsibilities:**
  - Define test strategy and approach
  - Create and maintain test plans
  - Validate acceptance criteria and Definition of Done
  - Own QA sign-off before release
  - Identify and triage quality issues
- **Success metrics:** Test coverage, bug escape rate, acceptance criteria sign-off rate, QA efficiency
- **Typical handoffs:** Requirements review → Test planning → Development testing → Release validation

---

### I'm a Data Analyst. What do I need to know?
- **Your core mission:** Enable data-driven decision making and measure the impact of features and releases.
- **Your primary collaborators:** Product Manager (for metrics), Developers (for instrumentation), DevOps (for monitoring).
- **Key responsibilities:**
  - Define success metrics aligned with business goals
  - Design instrumentation and telemetry collection
  - Build dashboards for monitoring and reporting
  - Analyze feature and release impact
  - Provide insights for iteration and improvement
- **Success metrics:** Metric definition clarity, dashboard coverage, analysis turnaround time, data-informed decisions
- **Typical handoffs:** Metrics definition → Instrumentation setup → Monitoring → Impact analysis

---

## Common Handoff Scenarios

### Scenario 1: Starting a New Feature
1. **Product Manager** defines the problem, success metrics, and acceptance criteria
2. **Product Manager** → **Project Manager** hands off requirements for planning
3. **Project Manager** → **Delivery Lead** schedules in sprint
4. **Technical Lead** reviews design feasibility during sprint planning
5. **Developers** implement with support from **QA Lead** on testability
6. **QA Lead** validates acceptance criteria during development
7. **Data Analyst** sets up metrics tracking before launch

---

### Scenario 2: Deploying a Release
1. **Release Manager** creates release checklist and schedule
2. **QA Lead** completes testing and signs off on quality
3. **Security Liaison** reviews findings and approves release
4. **Technical Lead** validates technical readiness
5. **DevOps** prepares infrastructure and deployment procedures
6. **Release Manager** executes deployment and monitors
7. **Data Analyst** tracks post-release metrics and impact

---

### Scenario 3: Identifying a Technical Risk
1. **Developer** or **Technical Lead** identifies a technical risk
2. **Technical Lead** proposes mitigation strategy
3. **Delivery Lead** escalates if it impacts timeline/schedule
4. **Project Manager** communicates impact to stakeholders
5. **Product Manager** may adjust priorities if needed
6. **Release Manager** updates release plans if needed

---

### Scenario 4: Responding to a Blocker
1. **Developer** surfaces blocker in daily standup
2. **Delivery Lead** triages and escalates to **Project Manager**
3. **Project Manager** identifies root cause and coordinates resolution
4. **Technical Lead** may help if it's a technical blocker
5. **DevOps** may help if it's an infrastructure blocker
6. **Delivery Lead** tracks resolution and updates team

---

## Escalation Paths

### For Timeline/Schedule Issues
```
Developer/Team → Delivery Lead → Project Manager → Product Lead → Sponsor
```

### For Technical Issues
```
Developer → Technical Lead → Delivery Lead → Project Manager (if blocking schedule)
```

### For Quality/QA Issues
```
QA Lead → Delivery Lead → Project Manager (if blocking release)
```

### For Security Issues
```
Security Liaison → Technical Lead → Project Manager (if blocking release)
```

### For Infrastructure/Deployment Issues
```
DevOps → Release Manager → Project Manager (if blocking release)
```

---

## Weekly Communication Cadence

| Meeting | Attendees | Purpose | Frequency |
|---------|-----------|---------|-----------|
| Daily Standup | Developers, Delivery Lead, QA Lead | Progress, blockers, dependencies | Daily (15 min) |
| Sprint Planning | PM, PdM, Developers, Tech Lead, Delivery Lead | Plan sprint work and commitments | Start of sprint |
| Delivery Sync | Project Manager, Delivery Lead, Tech Lead, QA Lead | Track progress, risks, blockers | 2x per week (30 min) |
| PM/PdM Sync | Project Manager, Product Manager | Scope, priorities, metrics, stakeholder updates | Weekly (30 min) |
| Release Planning | Release Manager, QA Lead, DevOps, Tech Lead | Plan release schedule and validation | As needed (1–2 weeks before release) |
| Retrospective | All project team members | Review learnings, action items | End of sprint/release |

---

## Definition of Done

A task, user story, or feature is "done" when:
- [ ] Acceptance criteria are met and signed off by Product Manager / QA Lead
- [ ] Code is reviewed and approved by at least one peer or Technical Lead
- [ ] Unit tests are written and passing
- [ ] Integration tests (if applicable) are written and passing
- [ ] Code follows team quality standards and is documented
- [ ] QA has validated the feature against acceptance criteria
- [ ] Security Liaison has reviewed (if security-related)
- [ ] Release notes are drafted
- [ ] Product Manager and QA Lead have signed off
- [ ] Work is merged to main branch and ready for release

---

## Decision-Making Framework

### Who decides what?

| Decision | Owner | Consulted | Informed |
|----------|-------|-----------|----------|
| **Feature Priority / Roadmap** | Product Manager | Project Manager, Developers | All team members |
| **Technical Architecture / Design** | Technical Lead | Developers, DevOps | QA, Security |
| **Definition of Done / Quality Standards** | QA Lead | Technical Lead, Developers | All team members |
| **Release Go/No-Go** | Release Manager | QA Lead, Technical Lead, Security Liaison | Project Manager, Developers |
| **Timeline / Schedule** | Project Manager | Delivery Lead, Developers | Product Manager, Stakeholders |
| **Security Requirements** | Security Liaison | Technical Lead, DevOps | Developers, Product Manager |
| **Infrastructure / Platform Changes** | DevOps | Technical Lead, Release Manager | Project Manager, Developers |
| **Test Strategy / Approach** | QA Lead | Developers, Product Manager | Technical Lead, Release Manager |
| **Success Metrics / KPIs** | Product Manager / Data Analyst | Developers, DevOps | Project Manager, QA Lead |

---

## Tips for New Team Members

- **Attend your first daily standup and sprint planning** — ask questions about roles and responsibilities
- **Read the role description for your role AND one adjacent role** — understanding your neighbors helps with collaboration
- **Bookmark the Handoff Scenarios section** — reference it when you're unsure who to hand off work to
- **Schedule a 1:1 with someone in your role** — learn how they approach the role and what to expect
- **Review the Decision-Making Framework** — know who makes final calls before you're surprised
- **Ask for clarity early** — if you're unsure about a handoff or responsibility, ask your Project Manager or Delivery Lead

---

## How to Use This Guide

- **Onboarding:** New team members should read their role section + the Quick Role Reference
- **Planning:** Review the Handoff Scenarios and Communication Cadence before sprint planning
- **Escalation:** Check the Escalation Paths when you need to surface a blocker or risk
- **Decision-making:** Reference the Decision-Making Framework when you're unsure who owns a call
- **Retrospectives:** Use this guide to assess communication and collaboration effectiveness
