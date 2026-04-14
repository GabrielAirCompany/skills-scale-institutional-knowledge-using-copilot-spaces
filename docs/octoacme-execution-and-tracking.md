# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Cross-functional Handoffs
Clear handoffs between roles reduce dropped context and last-minute surprises. At key execution milestones:
- **UX Designer → Developer**: Handoff annotated specs and design assets at the start of each feature; Designer is available for clarification questions during implementation and signs off on the implemented UI before marking the story Done.
- **Data Analyst → Product Manager**: Share metric dashboards and anomaly alerts within one business day of a release; flag unexpected trends in the next weekly sync.
- **Developer → QA**: Provide a test summary (coverage, known edge cases) alongside each PR; flag any untested paths that require manual QA attention.
- **QA → Release Manager**: Confirm QA sign-off in the [Release Readiness Checklist](octoacme-release-readiness-checklist.md) before the deployment window opens.
- **Customer Support Lead → Product Manager**: Escalate recurring customer issues with a concise summary (frequency, severity, user impact) at least once per sprint.

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
