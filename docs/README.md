# OctoAcme Project Management Docs

This README indexes the OctoAcme project management process documents and provides a concise summary of the project's approach to initiating, planning, executing, releasing, and continuously improving work.

Summary

OctoAcme follows a lightweight, repeatable project management workflow that emphasizes clear outcomes, iterative delivery, and shared ownership. Work begins with a short Project One‑pager to capture problem statements, success metrics, stakeholders, and a go/no‑go decision. Approved initiatives move into planning where scope is decomposed into shippable backlog items with acceptance criteria, estimates, and a Definition of Done.

During execution, the team uses a project board (Backlog → Ready → In Progress → In Review → QA → Done), small pull requests with linked issues and acceptance criteria, and CI checks (unit/integration tests, linting, security scans) before requesting review. Regular rhythms — daily standups, a weekly delivery sync, and demo/review at the end of each milestone — keep stakeholders aligned and surface blockers for escalation.

Releases are governed by type (patch, minor, major) and a pre‑release checklist including staging smoke tests, automated pipelines where possible, and a rollback plan. After release, retrospectives capture learnings and convert them into prioritized action items tracked in the backlog, and a simple risk register is maintained and reviewed regularly.

Docs index

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risks & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

How to propose changes

To suggest an update to these docs, use the "Add Content to Project Management Process Docs" issue template available at `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`. Fill out the form with which document to update, a summary of the change, rationale, and any suggested content. This helps keep changes reviewable and discoverable.

Acceptance criteria

- The README lists and links to every file in this docs/ directory.
- The summary aligns with the individual process documents in this folder.
- The README points contributors to the issue template for proposing changes.

Maintainers: @ctn4kn59mh
