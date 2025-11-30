# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies (facilitated by Communication Lead or PM)
- Weekly delivery sync — show progress, updates, and flagged risks (Communication Lead ensures stakeholder updates)
- Demo/Review at the end of each sprint or milestone (Stakeholders participate to provide feedback)

For detailed role responsibilities in execution activities, see the [Responsibility Matrix](octoacme-responsibility-matrix.md).

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

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

The Risk Manager tracks blockers as risks in the risk register and the Communication Lead ensures appropriate stakeholder notification during escalations.

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly (maintained by Risk Manager)
- [ ] Communication plan active (managed by Communication Lead)
- [ ] Stakeholder engagement confirmed (Stakeholders receiving regular updates)
