# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-02-12

### Added
- Initial release with semantic versioning support
- Main branch versioning based on merged PR source branch
- Optional pre-release versioning for feature/fix/chore branches
- Smart tag detection to prevent duplicate tags
- Support for custom major version
- Outputs: `version` and `is-prerelease`

### Features
- Feature branches (`feature/*`, `feat/*`) bump minor version
- Fix branches (`fix/*`, `hotfix/*`) bump patch version
- Chore branches (`chore/*`) bump patch version
- Pre-release mode creates versioned tags: `-alpha.N`, `-fix.N`, `-chore.N`
- Automatic tag creation and push

[1.0.0]: https://github.com/TheKathan/semantic-versioning/releases/tag/v1.0.0
