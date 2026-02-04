# OctoAcme Project Management Docs

Welcome — this README is the entry point for OctoAcme’s project management process documentation. These docs capture how we evaluate, plan, deliver, and learn from projects so teams and stakeholders have a single, discoverable source of truth.

OctoAcme runs projects through an iterative lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Initiation is lightweight and centers on a Project One-pager that describes the problem, objectives, measurable success criteria, stakeholders, and a high-level timeline; the Decision Gate to move into planning requires clear success metrics, stakeholder alignment, and team availability. Planning breaks approved initiatives into shippable increments with a prioritized backlog, estimates, a Definition of Done, and a release/milestone map; dependencies and risks are recorded in a Risk Register with owners and mitigation plans.

Day-to-day execution is guided by a team rhythm and a structured workflow. We use a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a Pull Request workflow that favors small changes, links issues and acceptance criteria, and runs automated CI checks before review. Quality assurance is layered: unit and integration tests, end-to-end smoke tests for critical flows, CI security scans, and manual QA when needed. Releases require passing CI/security scans, drafted release notes, smoke tests, and rollback plans.

Roles and responsibilities are explicit — each project names a Project Manager (PM) and a Product Lead/Manager (PdM). PMs coordinate delivery, schedules, risk and communication; PdMs define outcomes and prioritize the backlog; Developers implement changes and tests; QA validates acceptance criteria. Communication cadence and escalation are formalized: daily standups, weekly delivery syncs, PM–PdM alignment, and monthly stakeholder updates. Retrospectives capture learnings and convert them into prioritized action items.

Process documents (click to open)
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

How to use and contribute
- Keep the Project One-pager and project README updated in each project repo.
- Use the issue template .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml to propose changes to these process docs.
- When updating process docs, reference related issues and propose concrete action items for alignment in weekly PM syncs.

Acknowledgements
These docs are maintained to centralize and preserve program-level knowledge, improve onboarding, and reduce single-person dependencies. If something is missing or unclear, please open an issue with the “documentation” label.