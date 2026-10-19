# OctoAcme Project Management Docs

OctoAcme runs projects iteratively with a clear lifecycle: initiation, planning, execution, release, and retrospective. Initiation focuses on validating the business need and defining measurable outcomes using a lightweight one-pager. Planning breaks approved initiatives into prioritized, estimated backlog items, defines a Definition of Done, and captures dependencies and risks to create a release plan and milestone map. Execution emphasizes small, shippable increments and clear acceptance criteria so the team can iterate quickly and safely.

During execution, the team uses a project board (Backlog → Ready → In Progress → In Review → QA → Done), daily standups, and weekly delivery syncs to keep work visible and unblock progress. Pull requests should be small, include links to the related issue and acceptance criteria, and run CI checks (unit/integration tests, linting, security scanning) before requesting reviews. Releases follow defined pre-release checks (passing CI, release notes, rollback plans) and post-deploy verifications with an incident/rollback playbook for failures.

Roles and responsibilities are explicit: Product Managers define outcomes and success metrics; Project Managers coordinate delivery, schedule, and stakeholder communication; Developers implement and maintain tests and docs; QA validates acceptance and runs manual verification when needed. Communication cadence includes daily standups, weekly PM–PdM syncs, sprint demos, and monthly stakeholder updates, with an escalation path from team → PM → Product Lead → Sponsor for business-impacting blockers.

Continuous improvement is formalized through timeboxed retrospectives and a tracked action-item process: capture what went well, what could improve, prioritize 2–3 action items, and add them to the backlog with owners and due dates. The docs in this directory provide templates, checklists, and more detail for each stage of the lifecycle.

## Docs index

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risks & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

## How to use

Keep the Project Charter updated in the project repo and propose updates using the "Add Content to Project Management Process Docs" issue template. Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
