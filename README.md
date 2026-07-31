# Solo-maintainer documentation template

[![CI](../../actions/workflows/ci.yml/badge.svg)](../../actions/workflows/ci.yml) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Citation](https://img.shields.io/badge/citation-CFF-blue.svg)](CITATION.cff)

A documentation baseline with Markdown validation, link checking, Renovate, and explicit publication boundaries.

## Status

This repository is designed for one maintainer. Automated checks are required;
no second reviewer, CODEOWNERS approval, team membership, or mandatory human
approval is introduced.

## Start here

1. Replace the project name and purpose.
2. Edit `docs/index.md`.
3. Run the documented Markdown and link checks before publication.

## Development

CI validates the documentation source. Publication should be a separate workflow with an explicit target and deployed-revision receipt.

## Versioning

Documentation uses immutable release tags or deployed revisions. Do not invent a package version when there is no package artefact.

## Logging

Runtime logging is not applicable to a code-free documentation repository.

## Security

Report vulnerabilities privately through GitHub Security Advisories. See
[SECURITY.md](SECURITY.md); do not disclose credentials or sensitive source data
in a public issue.

## Citation

See [CITATION.cff](CITATION.cff). Release-specific versions and identifiers are
added only when the release exists.

## License

Repository-authored starter material is MIT licensed; see [LICENSE](LICENSE).
Record third-party and source-data rights separately.