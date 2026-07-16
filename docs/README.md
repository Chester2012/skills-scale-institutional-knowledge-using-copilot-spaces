# OctoAcme — Project Management Overview

This repository houses OctoAcme's program management process artifacts. The files in docs/ define how we initiate, plan, execute, deliver, and improve projects. Use these documents as the single source of truth for roles, workflows, checklists, and templates.

## Key Processes (high-level)

- Purpose: Deliver customer value iteratively, with clear ownership and measurable outcomes.
- Initiation: Capture a Project One-pager (problem, goal, success metrics), stakeholder alignment, and a go/no-go decision.
- Planning: Prioritize a backlog, estimate scope, define Definition of Done, map releases and dependencies.
- Execution & Tracking: Use a project board (Backlog → Ready → In Progress → In Review → QA → Done), small PRs, CI checks, daily standups, and weekly delivery syncs.
- Release & Deployment: Follow pre-release checks, automated pipelines where possible, smoke tests, and a rollback plan.
- Retrospectives & Continuous Improvement: Run timeboxed retros, capture 2–3 action items, and add improvements to the backlog.
- Risk & Communication: Maintain a Risk Register, provide regular stakeholder updates, and follow escalation paths for blockers or incidents.

## Team Rhythm & Roles

- Daily standups (15 min) for progress, blockers, and dependencies.
- Weekly delivery sync for progress, risks, and cross-team coordination.
- Sprint demos / reviews at the end of each sprint or milestone.

Core roles: Project Manager (PM), Product Manager (PdM), Developers, QA/Testing, Stakeholders.

## Quality and Release Expectations

- Unit and integration tests for new logic; smoke tests for critical flows.
- Security scanning in CI and manual QA when required.
- Release notes, rollback plans, and post-deploy verifications.

## Where to find more detail

This overview is a summary of more detailed process docs in this folder:

- octoacme-project-initiation.md
- octoacme-project-planning.md
- octoacme-execution-and-tracking.md
- octoacme-release-and-deployment.md
- octoacme-retrospective-and-continuous-improvement.md
- octoacme-risks-and-communication.md
- octoacme-roles-and-personas.md

Please keep these docs updated as processes evolve. For changes, use the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/ to request edits.
