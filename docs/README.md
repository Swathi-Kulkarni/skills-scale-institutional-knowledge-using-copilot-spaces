# OctoAcme Project Management Documentation

Welcome to OctoAcme's project management process documentation. This folder contains comprehensive guides for managing projects across all phases of the project lifecycle—from initiation through retrospectives and continuous improvement.

## Quick Links to Process Documents

Below are links to each OctoAcme project management document with a brief summary:

- **[octoacme-project-management-overview.md](./octoacme-project-management-overview.md)** — Introduction to OctoAcme's approach, core principles, roles, key artifacts, and high-level lifecycle
- **[octoacme-project-initiation.md](./octoacme-project-initiation.md)** — Guidance and templates for initiating new projects, including the Project One-pager and decision gates
- **[octoacme-project-planning.md](./octoacme-project-planning.md)** — Planning activities, backlog templates, estimation, Definition of Done, and release planning
- **[octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md)** — Team rhythm, workflows, PR conventions, quality standards, and tracking practices
- **[octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md)** — Release types, pre-release requirements, deployment checklists, and rollback procedures
- **[octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md)** — Retrospective structure, running effective retros, and tracking improvements
- **[octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md)** — Risk register guidance, communication templates, and escalation paths
- **[octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)** — Role descriptions and responsibilities for Project Managers, Product Managers, and Developers

---

## OctoAcme Project Management Overview

### Project Lifecycle & Workflow

OctoAcme follows a structured five-phase project lifecycle: **Initiation → Planning → Execution → Release → Close & Retrospective**. During initiation, teams validate business need, align stakeholders, and create a lightweight Project One-pager defining the problem, goals, success metrics, and initial timeline. Once approved, the planning phase breaks work into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done. Execution emphasizes iterative delivery with small pull requests (≤400 lines), automated testing, and continuous integration before review. The release phase ensures all acceptance criteria are met, security scans pass, and rollback plans are documented. Finally, retrospectives capture learnings and convert them into actionable improvements tracked in the backlog.

### Roles, Communication, and Governance

OctoAcme operates with clearly defined roles: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define what to build and prioritize the backlog; **Developers** implement features and collaborate on design; and **QA/Testing** validates acceptance criteria. Communication follows a structured cadence including daily standups (15 min focus on progress and blockers), weekly delivery syncs showing progress and risks, and monthly stakeholder updates. Risk management is central to the process—teams maintain a Risk Register tracking ID, description, impact, likelihood, owner, and mitigation plan, with escalation paths from team-level triage → PM → Product Lead → Sponsor for blocking issues.

### Quality & Delivery Standards

Quality is embedded throughout OctoAcme's execution model through unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI. The team tracks velocity, burndown, and success metrics on project dashboards, with manual QA for feature acceptance when needed. Pull Request workflows require at least one approval before merging, automated test and linting in CI, and clear issue links with acceptance criteria in PR descriptions. Release management is formalized with pre-release checklists, smoke tests on staging, and documented rollback procedures to minimize production risk.

### Key Artifacts & Continuous Improvement

The process is anchored in five core artifacts: the Project Charter/One-pager, Roadmap and Release Plan, Sprint/Iteration Backlog, Acceptance Criteria & Definition of Done, and Risk Register. Team members maintain these living documents in the project repository—with process-specific docs stored in `docs/` for shared reference and in `.copilot/` for Copilot Spaces context. The retrospective practice ensures continuous improvement: teams timebox 45–75 minute sessions after each sprint or milestone to discuss what went well, what could improve, and assign 2–3 prioritized action items with clear owners and due dates, measured for impact over time.

---

## How to Use These Docs

- **New to OctoAcme?** Start with [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) to understand the big picture.
- **Starting a new project?** Use [octoacme-project-initiation.md](./octoacme-project-initiation.md) and the Project One-pager template.
- **In execution mode?** Reference [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) for team rhythm and PR workflows.
- **Need to escalate a risk?** Check [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) for escalation paths and templates.
- **Preparing a release?** Use [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) for checklists and procedures.
- **Running a retrospective?** See [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) for structure and templates.

Keep these documents updated as processes evolve. Use the [Add/Update Content issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose improvements or new content.
