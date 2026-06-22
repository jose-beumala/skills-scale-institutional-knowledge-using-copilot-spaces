# OctoAcme Project Management Processes

This README is an index of OctoAcme project management process documents and includes a brief summary of the core processes. Place this file at docs/README.md so teammates can quickly find and navigate process guidance.

Overview

OctoAcme follows a lightweight, iterative, customer-first project management approach that guides work from idea through delivery and continuous improvement. Key stages are initiation (validate and authorize work with a one-pager and stakeholder alignment), planning (break initiatives into a prioritized backlog, estimate effort, and identify dependencies and risks), execution & tracking (deliver in small increments using a project board, PR conventions, and CI), release & deployment (pre-release checks, staging smoke tests, automated deploys where possible, and rollback plans), and retrospectives (capture learnings and convert them into tracked improvements).

Core workflows

- Initiation: Use the Project One-pager to state the problem, objectives, success metrics, stakeholders, and a go/no‑go decision for planning.
- Planning: Create a prioritized backlog with acceptance criteria and estimates, define the Definition of Done (DoD), and maintain a release plan and risk register.
- Execution & Tracking: Operate with a team rhythm (daily standups, weekly syncs, demos), manage work on a project board (Backlog → Ready → In Progress → In Review → QA → Done), and follow PR practices (small PRs, link issues and acceptance criteria, CI checks before review, required approvals).
- Release & Deployment: Categorize releases (patch, minor, major), ensure pre-release requirements (passing CI, release notes, rollback plan), run staging smoke tests, and verify production post-deploy.
- Retrospective & Continuous Improvement: Run retros after sprints/releases/incidents, prioritize 2–3 action items, and track them in the backlog with owners and due dates.
- Risk Management & Communication: Keep a simple risk register (ID, impact, likelihood, owner, mitigation), follow the escalation path (team → PM → Product Lead → Sponsor), and use weekly or milestone-based stakeholder updates.

Docs (links)

- [Project Management Overview](./octoacme-project-management-overview.md) — concise intro to OctoAcme approach, roles, and artifacts.
- [Project Initiation Guide](./octoacme-project-initiation.md) — one-pager template, initiation checklist, decision gate.
- [Project Planning](./octoacme-project-planning.md) — backlog templates, planning activities, risk management during planning.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — team rhythms, PR workflow, QA, reporting.
- [Release & Deployment](./octoacme-release-and-deployment.md) — release types, deployment checklist, rollback playbook.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — running retrospectives, tracking action items.
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — risk register structure, communication templates, escalation paths.
- [Roles & Personas](./octoacme-roles-and-personas.md) — role summaries used across the docs.

How to use

- Add or update process docs using the .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml issue template so changes are reviewed and tracked.
- Keep this README short and link to canonical documents for details.
- Place this file at docs/README.md and keep links relative so they work on any branch.
