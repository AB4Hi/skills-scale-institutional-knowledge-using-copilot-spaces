# Process Docs — PR & Publishing Checklist

Purpose: a short, repeatable checklist contributors and reviewers can follow for updating/adding process documentation.

When to use
- Any time you add or modify documents in docs/ (process, playbooks, checklists, templates).

Checklist for contributors (to include in PR description)
- [ ] I used the `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` template to capture the request and rationale (or linked the issue that explains the change).
- [ ] The doc is placed under docs/ and follows existing naming conventions.
- [ ] I added a short summary / TL;DR in the top of the file (one or two lines).
- [ ] I included acceptance criteria or examples where applicable.
- [ ] I ran a quick spell-check and ensured formatting is consistent with other process docs.
- [ ] I added or updated the Risk/Impact note if this change affects multiple teams or workflows.

Reviewer guidance
- Confirm the change addresses the stated rationale in the issue.
- Ensure the doc is actionable: steps, owners, and outputs are clear.
- Suggest a small set of edits instead of blocking on stylistic preferences.
- Approve when the doc meets the bar for clarity and does not introduce operational risk.

Post-merge steps (owner/PM)
- [ ] Add a short ChangeLog entry (either at top of file or in a central docs CHANGELOG).
- [ ] Move or update related project board cards (if applicable).
- [ ] Announce the change in the next weekly status update or via the established stakeholder channel.
- [ ] Add follow-up action items to backlog if needed (e.g., training, sample templates).

Templates / Examples (paste into PR if helpful)
- Summary (1–2 lines): "Clarify doc-update process and add checklist so contributors know acceptance criteria."
- Rationale: "Team members have been unsure how to propose doc changes; this reduces friction and ensures reviews are targeted."
