# OctoAcme Project Management Docs

This folder collects OctoAcme's program process documents — a single, discoverable entry point that helps team members and new contributors learn how we initiate, plan, deliver, and improve cross-functional projects. These docs are intentionally lightweight, actionable, and tied to living artifacts (project one‑pagers, boards, risk registers, and retrospectives) so processes remain practical and easy to follow.

OctoAcme runs projects through a lightweight, outcome-driven lifecycle that moves from initiation (problem statement and one‑pager) to planning, execution, release, and retrospective. Initiation requires a Project One‑pager that captures the problem, SMART objectives, success metrics, stakeholders, timeline, risks and proposed team—projects only move to planning once success metrics, stakeholder buy‑in, and team availability are confirmed. Planning breaks approved work into shippable increments with a prioritized backlog, clear acceptance criteria, estimates, a documented Definition of Done, and a release plan that maps milestones and dependencies. Key artifacts that live with the project include the Project Charter/One‑pager, roadmap/release plan, sprint backlog, acceptance criteria, risk register, and retrospective notes with action items.

Roles and personas are clearly defined and separated to enforce ownership and reduce ambiguity. Product Managers own what gets built: problem definition, prioritization and success metrics, and stakeholder alignment. Project Managers coordinate delivery: schedules, risk and dependency management, meeting facilitation, and status reporting. Developers implement features, write and maintain tests and docs, participate in design and code reviews, and help estimate work. QA/testing validates acceptance criteria and supports both automated and manual verification where needed; stakeholders are engaged for inputs and approvals.

Communication is structured around a predictable cadence and escalation path to keep alignment and surface blockers early. Teams run daily 15‑minute standups for progress, blockers and dependencies; a weekly delivery sync shows progress and flagged risks; PM+PdM hold weekly alignment; monthly stakeholder updates are used for broader reporting. Escalation is tiered: team triage at standups (Level 1), PM escalation to Product Lead and dependent teams (Level 2), and sponsor‑level escalation for business‑impacting issues (Level 3). Risk and dependency management are explicit—items are tracked in a risk register (ID, impact, probability, owner, mitigation) and cross‑team dependencies are marked on project boards and raised during weekly syncs.

Quality assurance and execution practices emphasize small, testable increments, automation, and gated reviews. The team uses a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a pull‑request workflow that favors small PRs (<= 400 lines), includes issue links and acceptance criteria, runs CI (tests, linting, security scans) before review, and requires at least one approval per team policy. Testing expectations include unit tests for new logic, integration tests where relevant, end‑to‑end smoke tests for critical flows, security scanning in CI, and manual QA for acceptance when necessary. Progress and quality are monitored via velocity/burndown metrics, dashboards for errors/latency/usage, and demos at the end of each sprint or milestone, with retrospectives feeding continuous improvement back into process and documentation.

This README is the canonical onboarding/discoverability entry point for OctoAcme process docs stored in this docs/ folder. To make these docs usable by Copilot Spaces, add process-specific files into `.copilot/` in project repos when you want Copilot to consume them as context.

## Links to process docs
- Project Management Overview — docs/octoacme-project-management-overview.md
- Project Initiation — docs/octoacme-project-initiation.md
- Project Planning — docs/octoacme-project-planning.md
- Execution & Tracking — docs/octoacme-execution-and-tracking.md
- Risks & Communication — docs/octoacme-risks-and-communication.md
- Release & Deployment — docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement — docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas — docs/octoacme-roles-and-personas.md

## Acceptance checklist (for maintainers)
- [ ] Content aligns with existing process docs
- [ ] README improves discoverability and onboarding
- [ ] Stakeholders/reviewers invited to confirm wording if needed
