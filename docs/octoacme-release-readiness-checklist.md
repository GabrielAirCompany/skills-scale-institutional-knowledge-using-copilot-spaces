# OctoAcme — Release Readiness Checklist

## Purpose
Provide a consistent, cross-functional gate before any release to production. Every sign-off below must be obtained (or explicitly waived with documented rationale) before the **Release Manager** calls go/no-go.

## How to use
1. Open this checklist for each planned release (copy into a new issue, PR, or release doc).
2. Assign each section owner before the release window.
3. Obtain written sign-off (comment, approval, or checkmark) from each owner.
4. The Release Manager reviews completed sign-offs and makes the final go/no-go call.

For release deployment steps, refer to the [Release & Deployment Guide](octoacme-release-and-deployment.md).

---

## Engineering Readiness

**Owner: Engineering Manager / Tech Lead**

- [ ] All acceptance criteria met and linked PRs merged to the release branch
- [ ] Passing CI (build, unit tests, integration tests)
- [ ] No P0/P1 open bugs targeting this release
- [ ] Code freeze window enforced; any post-freeze merges reviewed and approved
- [ ] Rollback plan documented and tested (or documented as untested with risk acknowledged)
- [ ] Feature flags or progressive rollout configured if applicable

---

## Quality Assurance

**Owner: QA / Testing**

- [ ] Regression suite executed and results reviewed
- [ ] End-to-end smoke tests passed for all critical flows
- [ ] Known issues list reviewed; no unacceptable issues remain untracked
- [ ] Accessibility checks completed for UI-impacting changes (coordinate with UX Designer)
- [ ] Test summary shared with Project Manager and Product Manager

---

## Security & Compliance

**Owner: Security / Compliance Partner**

- [ ] Security scan results reviewed; no critical or high vulnerabilities unmitigated
- [ ] Dependency vulnerability scan completed (e.g., Dependabot or equivalent)
- [ ] Data handling and privacy requirements reviewed for new features (if applicable)
- [ ] Penetration test or threat model updated for significant architectural changes
- [ ] Security sign-off recorded (name + date)

---

## Product Sign-off

**Owner: Product Manager**

- [ ] Feature scope confirmed as complete (no missing must-have items)
- [ ] Release notes drafted and reviewed
- [ ] Success metrics and tracking confirmed as instrumented
- [ ] External communications / announcements prepared (if applicable)
- [ ] Product sign-off recorded (name + date)

---

## Customer Support Readiness

**Owner: Customer Support Lead**

- [ ] Support team briefed on new features and known issues
- [ ] Internal FAQs, runbooks, or help articles updated
- [ ] Escalation path for post-release issues confirmed with Engineering and PM
- [ ] Support sign-off recorded (name + date)

---

## Operational / SRE Readiness

**Owner: SRE / Platform Engineer**

- [ ] Deployment runbook reviewed and up to date
- [ ] Monitoring and alerting verified for new or changed services
- [ ] On-call rotation confirmed and briefed for the release window
- [ ] Infrastructure capacity reviewed (scaling, quotas, limits)
- [ ] SRE sign-off recorded (name + date)

---

## Release Manager — Final Go/No-Go

**Owner: Release Manager**

- [ ] All required sign-offs obtained (or waivers documented)
- [ ] Deployment window confirmed and communicated to stakeholders
- [ ] Rollback trigger criteria defined (e.g., error rate threshold, SLO breach)
- [ ] Post-deploy verification steps assigned (owner + expected duration)

**Decision:** ☐ GO &nbsp;&nbsp; ☐ NO-GO

**Release Manager:** _____________________ &nbsp; **Date / Time:** _____________________

**Notes / Waivers:**
_Document any waived items with rationale here._
