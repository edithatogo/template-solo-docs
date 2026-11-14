# Contributing

## Development

Use Node 24 for parity with the pinned Markdown action. The reusable workflow's action 24.1.0 includes `markdownlint-cli2` 0.23.1. The following command runs that CLI version without adding a package manifest to this code-free starter:

Use descriptive headings, relative links for repository-owned pages and examples that a reader can follow. Keep Markdown formatting aligned with the committed configuration. Separate any publishing workflow from source validation.

See [BOOTSTRAP.md](BOOTSTRAP.md) when creating a new project from this starter.

## Validation

```sh
npx --yes markdownlint-cli2@0.23.1 "**/*.md"
```

Run from the repository root so `.markdownlint-cli2.yaml` is applied. CI currently checks Markdown formatting. Inspect local links and examples and record any separate external-link validation; this workflow does not establish external link availability or successful publication.

Record the command, tool versions and outcome in the pull request. Distinguish
passed, failed, skipped and unavailable checks; include a hosted run link when
available. Required automated checks must pass before integration.

## Pull requests

Use a focused branch such as `fix/short-summary`, `feat/short-summary` or
`docs/short-summary`. Explain the problem and resulting behaviour, link related
issues, and include the validation evidence. Keep commits reviewable and update
affected documentation, examples and tests with the change. Identify any
compatibility, generated-output, release or data impact.

The repository has one maintainer. Automated review and required checks replace
mandatory human approval; do not add a second-reviewer, team or CODEOWNERS gate.
Preserve unrelated work and existing security/publication requirements.

## Security and support

Use the repository's issue chooser for reproducible bugs or scoped proposals.
For usage questions, include a minimal safe example and what you have already
tried. Follow [SECURITY.md](SECURITY.md) for vulnerabilities; do not put private
data, credentials or sensitive exploit details in public issues or logs.

Follow the account's
[code of conduct](https://github.com/edithatogo/.github/blob/main/CODE_OF_CONDUCT.md).
When adopting this template under a different owner, replace this link with the
new project's policy and verify its support and private-reporting routes.
