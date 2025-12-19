# OctoAcme — Process Templates & Checklists

This file centralizes lightweight templates and checklists to reduce friction and ensure consistent quality across projects.

## PR Checklist
Use this checklist in every PR description or as a PR template.
- [ ] PR links to an issue or project card
- [ ] Short summary of change and why
- [ ] Acceptance criteria included (copy from issue)
- [ ] Tests added / updated for new behavior
- [ ] CI passes (unit, integration, linting)
- [ ] Security scans pass (or exceptions documented)
- [ ] No secrets or sensitive data included
- [ ] Size is reasonable (split if large) and change is reversible
- [ ] At least one approver assigned (per team policy)

## QA Checklist (for feature validation)
- [ ] Acceptance criteria satisfied
- [ ] Unit tests added/updated
- [ ] Integration tests added/updated (if applicable)
- [ ] End-to-end smoke tests for critical flows (pass)
- [ ] Manual exploratory checks (if needed) documented
- [ ] Performance/security considerations reviewed
- [ ] QA sign-off recorded in PR or linked issue

## Release Checklist (pre-deploy)
- [ ] All PRs merged for release candidate
- [ ] CI and security scans green
- [ ] Release notes drafted and reviewed
- [ ] Rollback / mitigation plan recorded
- [ ] Smoke tests prepared and owners assigned
- [ ] Deployment window confirmed (if required)
- [ ] Post-deploy verification plan (who, when) ready
- [ ] Stakeholder announcement draft prepared

## Risk Register Template
Maintain a simple table in the repo or a spreadsheet; add entries as issues if actions are needed.

| ID | Description | Impact (H/M/L) | Likelihood (H/M/L) | Owner | Mitigation | Status |
|----|-------------|----------------|---------------------|-------|------------|--------|
| R-001 | Example dependency delay | High | Medium | @owner | Identify fallback vendor | Open |

## How to use
- Reference these checklists in PR descriptions and release notes.
- If your team requires stricter rules (e.g., 2 reviewers), document that in the project README.    