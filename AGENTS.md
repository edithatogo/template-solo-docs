# AGENTS.md

## Repository map

- `docs/index.md`: documentation entry point.
- `.markdownlint-cli2.yaml`: project Markdown rules.
- `.github/workflows/ci.yml`: pinned shared Markdown CI caller.
- `README.md`: repository purpose and adoption guidance.

## Development and validation

Read [CONTRIBUTING.md](CONTRIBUTING.md) for the required setup, exact local
commands and evidence requirements. Run the pinned Markdown lint command from CONTRIBUTING; do not describe it as an external link check.
Use an evidenced release tag or deployed revision when publication needs versioning. Do not invent a package version or claim a deployment from a successful lint run.

## Operating model

This repository is maintained by one developer. Automated review, tests and
security gates replace mandatory human approvals. Do not add CODEOWNERS approval
requirements, team assignments or a second-maintainer dependency. Use a focused
branch and reviewable pull request; preserve unrelated and unmerged work.

## Boundaries

Never commit credentials or sensitive data. Keep generated files reproducible.
Prefer one authoritative configuration and link to it from tool-specific files.
Source validation does not authorize publication. Keep a deployed-revision
receipt for any separately approved publishing process.

Use [BOOTSTRAP.md](BOOTSTRAP.md) for adoption decisions. Keep the applicability
declarations in `.github/community-bootstrap.json` aligned with actual project
configuration; they do not substitute for observed GitHub settings.
