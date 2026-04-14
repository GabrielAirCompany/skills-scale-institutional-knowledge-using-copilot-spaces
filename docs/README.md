# OctoAcme Project Management Docs

This README provides an overview of the project management practices used at OctoAcme and serves as a reference index to all process documentation. It is designed to help team members quickly understand OctoAcme's delivery approach and navigate to the right document for any stage of a project.

## Summary of Project Management Processes

OctoAcme's project management approach follows a lightweight, repeatable lifecycle that moves work from **initiation → planning → execution → release → retrospective/continuous improvement**. Projects begin once a clear business need and measurable outcome are defined, stakeholders are identified, and a "go/no-go" decision is made to proceed into planning. Core artifacts — such as a project charter, a high-level milestone timeline, an initial risk list, and a communication plan — serve as the baseline source of truth and reduce ambiguity as the team transitions into delivery.

In planning, OctoAcme focuses on turning approved work into an actionable backlog of **shippable increments** with explicit **acceptance criteria**. The team defines a shared Definition of Done, estimates work (e.g., T-shirt sizing or story points), identifies dependencies and integration points, and maps milestones into a release plan. During execution, work is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and managed through a pull-request workflow that emphasises small, reviewable changes linked to issues and acceptance criteria.

Roles and ownership are intentionally explicit. A **Project Manager (PM)** coordinates delivery, scheduling, risks, and communications; a **Product Manager / Product Lead** defines outcomes, prioritises the backlog, and measures success; **Developers** design and implement solutions with testability and maintainability in mind; **QA/Testing** validates quality and acceptance criteria; and **Stakeholders** provide inputs and approvals at key gates. This clarity of responsibilities helps decisions get made quickly and keeps accountability for both delivery and outcomes visible throughout the project.

Communication and quality assurance are treated as continuous practices rather than one-time phase gates. Teams maintain a **risk register** (impact/likelihood/owner/mitigation/status) and review it regularly, escalating blockers from team triage to PM/Product Lead and, when needed, to sponsor-level visibility. The operating rhythm typically includes daily standups, weekly delivery syncs, and demos per sprint or milestone. On quality, OctoAcme expects unit and integration testing where applicable, end-to-end smoke testing for critical flows before release, security scanning in CI, and manual QA when needed — paired with release checklists (CI passing, release notes, rollback plans, staged deploys, and post-deploy verification) and a retrospective loop to convert learnings into tracked action items.

## Process Docs Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level overview of the OctoAcme PM lifecycle and guiding principles |
| [Project Initiation Guide](octoacme-project-initiation.md) | How to define scope, stakeholders, and secure project approval |
| [Project Planning](octoacme-project-planning.md) | Backlog creation, estimation, Definition of Done, and milestone mapping |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Board workflow, PR process, and daily/weekly delivery rhythms |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, and communication plan templates |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Release checklists, staged deploys, rollback plans, and post-deploy verification |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective formats, action-item tracking, and process improvement loops |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed descriptions of every role involved in OctoAcme projects |
| [Ownership Matrix Template](octoacme-ownership-matrix-template.md) | RACI-style ownership matrix template for assigning roles across project activities |
| [Release Readiness Checklist](octoacme-release-readiness-checklist.md) | Cross-functional sign-off checklist (Engineering, QA, Security, Product, Support, SRE) for go/no-go decisions |

Each linked document provides detailed descriptions, templates, and checklists for the OctoAcme way of managing projects.
