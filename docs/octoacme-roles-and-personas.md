# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## UX Designer

### Role Summary
UX Designers translate user needs and product requirements into intuitive, accessible interfaces and interaction patterns. They bridge product intent and engineering implementation through design artefacts and validation.

### Responsibilities
- Conduct user research and usability testing to inform design decisions
- Produce wireframes, prototypes, and design specifications
- Participate in backlog refinement to clarify acceptance criteria around UX
- Review implemented features against design specifications
- Maintain a shared design system and component library

### Goals
- Ensure delivered features are usable, accessible, and aligned with user expectations
- Reduce rework caused by late-stage UX feedback
- Advocate for user needs throughout the project lifecycle

### Typical Communication
- Design reviews with Product Managers and Developers at sprint or feature level
- Usability test reports shared with Product and Project Managers
- Annotated prototypes and specs in the shared design tool

### Interactions with Existing Roles
- **Product Managers**: Receive problem statements and success metrics; provide design solutions and usability findings that inform prioritisation decisions.
- **Developers**: Hand off detailed specs and assets; collaborate during implementation to resolve design ambiguities; conduct acceptance reviews.
- **Project Managers**: Flag design-dependent blockers or scope changes; align on timelines for design deliverables relative to sprint milestones.

---

## Data Analyst

### Role Summary
Data Analysts partner with Product and Project Managers to define, track, and interpret success metrics. They surface data-driven insights that guide feature prioritisation, release decisions, and retrospective learnings.

### Responsibilities
- Define and instrument key metrics in collaboration with Product Managers
- Build and maintain dashboards for tracking project and product health
- Analyse post-release data to validate outcomes against success criteria
- Surface insights and anomalies during retrospectives and planning sessions
- Support A/B test design, analysis, and result communication

### Goals
- Ensure all projects have measurable outcomes tracked throughout delivery
- Reduce reliance on intuition for prioritisation and go/no-go decisions
- Provide fast, trustworthy data access to the delivery team

### Typical Communication
- Metric review in weekly PM + PdM syncs
- Dashboard links and summary reports in project status updates
- Ad-hoc analysis shared via the team's collaboration channel

### Interactions with Existing Roles
- **Product Managers**: Co-define success metrics during initiation; deliver post-launch analysis to support backlog prioritisation.
- **Project Managers**: Provide data signals for risk and progress tracking; flag metric deviations that may require escalation.
- **Developers**: Collaborate on instrumentation requirements (logging, events, feature flags) to ensure data collection is complete and accurate.

---

## Release Manager

### Role Summary
Release Managers coordinate release planning, change control, and cross-functional readiness to ensure deployments happen safely and predictably. They own the release process from final code freeze to post-deploy confirmation.

### Responsibilities
- Define and communicate release schedules and code-freeze windows
- Coordinate cross-functional sign-off (QA, Security, Support, Product) before each release
- Maintain deployment playbooks and ensure rollback plans are documented
- Run or delegate the go/no-go call at each release gate
- Communicate release status and post-deploy outcomes to stakeholders
- Own the [Release Readiness Checklist](octoacme-release-readiness-checklist.md)

### Goals
- Reduce deployment risk through consistent process and explicit sign-off gates
- Ensure every stakeholder is informed and prepared for each release
- Maintain a reliable, repeatable release cadence

### Typical Communication
- Release schedule and change-freeze announcements
- Pre-release status updates summarising readiness gate outcomes
- Post-release announcements and incident/rollback notifications

### Interactions with Existing Roles
- **Developers**: Receive build artefacts, release notes, and readiness confirmations; coordinate code freeze and hotfix policies.
- **Product Managers**: Confirm scope finality and business sign-off before go-live; align on release notes and external communications.
- **Project Managers**: Synchronise release milestones with the project timeline; escalate release blockers that affect delivery commitments.

---

## Customer Support Lead

### Role Summary
Customer Support Leads represent the voice of end-users and internal support staff. They ensure the delivery team understands support impact before releases and that user-facing issues are closed-loop efficiently.

### Responsibilities
- Collect, triage, and escalate customer feedback and incident reports to the product and engineering teams
- Review upcoming releases for support readiness (docs, FAQs, runbooks)
- Participate in release readiness reviews to confirm support is prepared
- Provide input to retrospectives based on support trends and recurring issues
- Liaise with Product Managers on bugs and improvements surfaced through support channels

### Goals
- Reduce the volume and severity of post-release support incidents
- Ensure support teams are informed and equipped before any release
- Close the feedback loop between end-users and the delivery team

### Typical Communication
- Support readiness confirmation in the [Release Readiness Checklist](octoacme-release-readiness-checklist.md)
- Recurring issue summaries shared with Product and Project Managers (at least monthly)
- Incident escalations and status updates via the shared incident channel

### Interactions with Existing Roles
- **Product Managers**: Provide customer feedback and incident trends as inputs for backlog prioritisation.
- **Developers**: Escalate reproducible bugs with context; participate in post-incident reviews.
- **Project Managers**: Flag support-impacting risks before releases; confirm support readiness as part of go/no-go gates.

---

## Engineering Manager / Tech Lead

### Role Summary
Engineering Managers and Tech Leads provide technical oversight and people leadership for the development team. They bridge delivery commitments and engineering capacity, guard technical quality, and unblock the team.

### Responsibilities
- Own technical architecture decisions and design reviews
- Manage team capacity and skill-set gaps in coordination with Project Managers
- Set and enforce coding standards, review processes, and security practices
- Identify technical risks and propose mitigations during planning
- Provide input on feasibility and estimates for new features

### Goals
- Maintain a healthy, productive engineering team
- Ensure technical quality and sustainable delivery pace
- Reduce technical debt and architectural risk

### Typical Communication
- Technical design reviews with Developers and cross-functional partners
- Capacity and risk inputs to weekly PM syncs
- Engineering updates in stakeholder status reports as needed

### Interactions with Existing Roles
- **Project Managers**: Provide engineering capacity and risk inputs; escalate technical blockers; align on realistic timelines.
- **Product Managers**: Assess feasibility and trade-offs for roadmap items; surface technical constraints that affect scope or prioritisation.
- **Developers**: Provide mentorship, code review, and architectural direction; shield team from unplanned scope changes.

---

## Security / Compliance Partner

### Role Summary
Security and Compliance Partners ensure that project deliverables meet organisational security policies, regulatory requirements, and risk thresholds. They are a required sign-off in release and planning gates.

### Responsibilities
- Review designs and technical implementations for security vulnerabilities and compliance requirements
- Define and validate security acceptance criteria for features
- Approve or flag releases via the [Release Readiness Checklist](octoacme-release-readiness-checklist.md)
- Own the security incident runbook and on-call rotation
- Conduct or coordinate periodic security reviews and penetration tests

### Goals
- Ensure no critical security vulnerabilities reach production
- Maintain compliance with applicable standards (e.g., SOC 2, GDPR, HIPAA as relevant)
- Build a security-aware culture within delivery teams

### Typical Communication
- Security review findings shared with Engineering Manager and Project Manager
- Security sign-off in release gates (pre-deploy)
- Incident notifications and post-incident reports for security events

### Interactions with Existing Roles
- **Developers**: Provide secure coding guidelines; review PRs flagged for security impact; respond to security scan findings.
- **Project Managers**: Communicate security-related risks and timelines; participate in risk register reviews.
- **Release Managers**: Provide explicit security sign-off before each release; define security-related release blockers.

---

## SRE / Operations / Platform Engineer

### Role Summary
SRE and Platform Engineers own the reliability, observability, and operability of production systems. They partner with delivery teams to ensure services can be deployed, monitored, and recovered safely.

### Responsibilities
- Define and maintain SLOs, SLIs, and alerting for services in scope
- Review release plans for operational readiness (runbooks, monitoring, rollback)
- Participate in incident response and lead post-incident reviews
- Provide infrastructure and platform capabilities that enable CI/CD pipelines
- Approve or flag operational readiness in the [Release Readiness Checklist](octoacme-release-readiness-checklist.md)

### Goals
- Maintain agreed availability and reliability targets
- Reduce mean time to detect and resolve incidents
- Enable teams to deploy confidently and frequently

### Typical Communication
- Operational readiness review before each release
- On-call handoff notes and incident reports
- Infrastructure change requests and platform updates communicated via standard channels

### Interactions with Existing Roles
- **Developers**: Collaborate on observability requirements (logging, tracing, alerting); assist with environment and deployment issues.
- **Project Managers**: Flag infrastructure risks or capacity constraints that affect delivery milestones.
- **Release Managers**: Provide operational sign-off in release gates; own rollback execution if a deployment triggers reliability thresholds.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For assigning ownership across these roles in a specific project, refer to the [Ownership Matrix Template](octoacme-ownership-matrix-template.md).

