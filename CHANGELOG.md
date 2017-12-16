# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.3] - 2017-12-16
### Changed
- Move bugfixes under Fixed headers in this document.

### Fixed
- Now checks if the temporary directory actually contains a Git repository before trying to interact with it.
- Handle case where a word is replaced with itself.

## [1.1.2] - 2017-12-16
### Added
- A test for `getMisspellings`.
- Exponential backoff while trying to clone the repository.

### Removed
- One-second gap between forking and cloning the fork.

## [1.1.1] - 2017-12-15
### Added
- Demo GIF in README.md.
- One-second gap between forking and cloning the fork.

### Changed
- Names of tests for `getMisspellings` and `formatPrompt`.

## [1.1.0] - 2017-12-15
### Added
- Quiet mode.

## [1.0.6] - 2017-12-14
### Fixed
- Typo in README.md.

## [1.0.5] - 2017-12-14
### Added
- Tests for the `formatPrompt` method.

### Changed
- Refactored code to remove `continue` statements.
- Moved call to `formatDiffs` into `addByUserSelection`.

## [1.0.4] - 2017-12-14
### Added
- MIT License.

## [1.0.3] - 2017-12-14
### Added
- Automatic deploys to the NPM registry from Travis.

## [1.0.2] - 2017-12-14
### Fixed
- Fixed a bug where the temporary directory into which the repository would be cloned was being created relative to the current working directory.

## [1.0.1] - 2017-12-14
### Added
- NPM status badge in README.

### Changed
- Location of status badges in README.

## 1.0.0 - 2017-12-14
### Added
- The core Github Spellcheck functionality. Hurray!

[Unreleased]: https://github.com/tbroadley/github-spellcheck-cli/compare/v1.1.0...HEAD
[1.1.0]: https://github.com/tbroadley/github-spellcheck-cli/compare/v1.0.6...v1.1.0
[1.0.6]: https://github.com/tbroadley/github-spellcheck-cli/compare/v1.0.5...v1.0.6
[1.0.5]: https://github.com/tbroadley/github-spellcheck-cli/compare/v1.0.4...v1.0.5
[1.0.4]: https://github.com/tbroadley/github-spellcheck-cli/compare/v1.0.3...v1.0.4
[1.0.3]: https://github.com/tbroadley/github-spellcheck-cli/compare/v1.0.2...v1.0.3
[1.0.2]: https://github.com/tbroadley/github-spellcheck-cli/compare/v1.0.1...v1.0.2
[1.0.1]: https://github.com/tbroadley/github-spellcheck-cli/compare/v1.0.0...v1.0.1