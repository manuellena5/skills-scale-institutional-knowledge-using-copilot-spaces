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
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, Sponsor, UX team, Data team)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- Ensure Sponsor receives executive summaries at key milestones
- Share Data Analyst insights with relevant stakeholders
- Communicate design decisions and user feedback from UX Designer

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary (with System Administrator for infrastructure incidents)
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled (facilitated by Scrum Master)
- Impact analysis provided by Data Analyst when applicable

## Escalation Paths
- Team-level -> Scrum Master/Project Manager -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call and System Administrator
- For infrastructure issues: System Administrator -> Infrastructure Lead
- For design/UX conflicts: UX Designer -> Design Lead -> Product Manager
- For data/metrics concerns: Data Analyst -> Analytics Lead -> Product Manager
