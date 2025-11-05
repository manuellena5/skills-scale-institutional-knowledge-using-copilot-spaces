# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies (facilitated by Scrum Master)
- Weekly delivery sync — show progress, updates, and flagged risks (led by Project Manager)
- Demo/Review at the end of each sprint or milestone (includes Product Manager, UX Designer, and key stakeholders)

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
- Manual QA for feature acceptance when needed (coordinated by QA team)
- UX Designer validates design implementation and usability
- System Administrator reviews infrastructure and security implications

## Reporting & Metrics
- Track velocity and burndown (monitored by Scrum Master)
- Monitor success metrics identified in the Project One-pager (tracked by Data Analyst)
- Use dashboards for key signals (errors, latency, usage) — Data Analyst builds and maintains
- UX metrics and user feedback tracked and reviewed regularly

## Blocker Escalation
- Level 1: Team-level triage in daily standup (Scrum Master facilitates)
- Level 2: Project Manager escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues
- For infrastructure/security issues: System Administrator involved at appropriate level
- For design/UX blockers: UX Designer consulted and may escalate to design leadership

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled with stakeholders
- [ ] Risk register updated weekly by Project Manager
- [ ] QA sign-off process defined and followed
- [ ] Data tracking and dashboards operational
- [ ] Infrastructure and deployment runbooks maintained by System Administrator
