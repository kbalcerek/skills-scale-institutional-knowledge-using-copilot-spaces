# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Functional Risk Ownership Guide
- UX Designer: usability/accessibility risks, adoption friction, and user journey gaps.
- Business Analyst: requirement ambiguity, policy/compliance interpretation, and process misalignment.
- DevOps/SRE: environment reliability, deployment safety, scalability, and observability gaps.
- Customer Support/Success: customer impact trends, support readiness, and incident communication quality.
- Project Manager: overall risk register completeness, mitigation tracking, and escalation timing.

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call

## Handoff Expectations
- Every high-impact risk has a named functional owner and a PM-tracked mitigation due date.
- Risks that affect release readiness must be reviewed in go/no-go with DevOps/SRE and Support/Success.
- Newly identified customer-impacting risks are communicated to Support/Success within one business day.
