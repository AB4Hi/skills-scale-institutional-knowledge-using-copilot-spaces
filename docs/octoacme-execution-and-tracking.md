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
  - When docs-only changes are made, mark PR with "docs" label and reference the relevant ISSUE_TEMPLATE entry.

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Documentation Maintenance (new)
Purpose: ensure process documents are accurate, discoverable, and easy to change.

- Where to add changes:
  - All program process documents live under docs/
  - Use `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to propose new content or updates.
- Doc PR expectations:
  - Provide a brief summary and rationale in the PR description.
  - Link to the issue created by the ISSUE_TEMPLATE (or create one if special-case).
  - Add at least one team reviewer (owner or domain expert).
  - Use "docs" label and, if applicable, the relevant functional label (e.g., "process improvement").
  - Small doc changes may be fast-tracked by the PM if non-controversial, but major changes should wait for at least one cross-functional review.
- Publishing:
  - After merge, update any relevant project boards and announce to stakeholders (weekly status or release notes as appropriate).
  - Keep a short ChangeLog entry in the doc header or a central CHANGELOG for process docs when changes materially affect workflows.

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
