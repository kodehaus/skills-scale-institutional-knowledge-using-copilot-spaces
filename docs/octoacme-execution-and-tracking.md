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
  - Run automated tests and linting in CI before requesting review (DevOps pipelines)
  - Require at least one approval before merging (or team-defined policy)
  - QA Lead reviews for quality-critical changes
  - UX Designer reviews for UI/UX changes
- Quality Gate: PRs move to QA column for QA Lead validation before Done

## Quality & Testing
- Unit tests for new logic (Developer responsibility)
- Integration tests where applicable (Developer + QA Lead)
- End-to-end smoke tests for critical flows before release (QA Lead)
- Security scanning in CI (DevOps Engineer maintains tooling)
- Automated testing in CI/CD pipeline (DevOps + QA collaboration)
- Manual QA for feature acceptance when needed (QA Lead)
- Usability testing for new user-facing features (UX Designer + QA Lead)

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues
- Quality blockers: QA Lead → PM → Product Lead
- Infrastructure/deployment blockers: DevOps Engineer → PM → Infrastructure Lead
- Design blockers: UX Designer → Product Manager → Design Lead

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint (DevOps Engineer)
- [ ] Automated quality gates established (QA Lead + DevOps)
- [ ] Regular demos scheduled with stakeholder participation
- [ ] Risk register updated weekly
- [ ] Design review process established (UX Designer + Product Manager)
- [ ] Release coordination process in place (Release Manager)
