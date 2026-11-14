# Solo-maintainer documentation template

[![CI](../../actions/workflows/ci.yml/badge.svg)](../../actions/workflows/ci.yml) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Citation](https://img.shields.io/badge/citation-CFF-blue.svg)](CITATION.cff)

A documentation baseline with Markdown validation, Renovate, and explicit publication boundaries.

## Status

This repository is designed for one maintainer. Automated checks are required;
no second reviewer, CODEOWNERS approval, team membership, or mandatory human
approval is introduced.

## Usage

Choose **Use this template** to start a documentation project, then follow the
[adoption checklist](BOOTSTRAP.md). The initial entry page is `docs/index.md`.
There is no configured site renderer or publication destination.

1. Replace the project name and purpose and add substantive content to
   `docs/index.md`.
2. Add repository-relative links and runnable examples appropriate to the
   documentation's audience.
3. With Node 24, run `npx --yes markdownlint-cli2@0.23.1 "**/*.md"` from the
   repository root.
4. Inspect links and examples separately and record their outcomes before any
   independently configured publication step.

## Development

See [CONTRIBUTING.md](CONTRIBUTING.md) for setup and validation commands, and
[BOOTSTRAP.md](BOOTSTRAP.md) for the adoption checklist.

The pinned shared CI checks Markdown formatting with the committed lint
configuration. External-link availability and example execution need separate
evidence. Publication requires a separate workflow with an explicit target
and a deployed-revision receipt.

## Versioning

Documentation uses immutable release tags or deployed revisions. Do not invent a package version when there is no package artefact.

## Logging

Runtime logging is not applicable to a code-free documentation repository.

## Security

Follow [SECURITY.md](SECURITY.md) for private reporting and the safe contact
fallback if GitHub's **Report a vulnerability** option is unavailable. Do not
include credentials, sensitive source data or exploit details in public issues.

## Citation

See [CITATION.cff](CITATION.cff). Release-specific versions and identifiers are
added only when the release exists.

## License

Repository-authored starter material is MIT licensed; see [LICENSE](LICENSE).
Record third-party and source-data rights separately.
