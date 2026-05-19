# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone
- Cross-functional triage touchpoint (as needed) — UX, BA, DevOps/SRE, and Support/Success for blockers and handoffs

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

## Cross-Functional Execution Handoffs
- UX Designer: reviews implemented experience against intended flows and accessibility expectations.
- Business Analyst: validates requirement intent and updates traceability when scope decisions change.
- DevOps/SRE: tracks operational readiness, deployment health, and reliability risks.
- Customer Support/Success: validates support readiness artifacts and monitors emerging customer issues.

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] UX/design acceptance checks completed for scoped flows
- [ ] BA requirement changes reflected in backlog and decision log
- [ ] DevOps/SRE operational checks reviewed (alerts, dashboards, rollback)
- [ ] Support/Success prepared with customer-facing guidance for upcoming release
