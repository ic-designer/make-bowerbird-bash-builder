# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

```markdown
## [Unreleased] - YYYY-MM-DD

### Added
### Changed
### Deprecated
### Fixed
### Security
```

## [Unreleased] - YYYY-MM-DD

### Added
### Changed
- The string comparisons in the tests are now performed using
  `bowerbird::test:compare-strings` instead of `test`.
- The files comparisons in the tests are now performed using
  `bowerbird::test:compare-files` instead of `test`.
- Updated the `bowerbird-deps` and `bowerbird-test` calls to the new syntax.
### Deprecated
### Fixed
### Security


## [0.1.0] - 2024-06-07

### Added
- Migrated the bash build recipes to a separate repo.
- Created documentation for the public macros.
### Changed
- Test are now run using Bowerbird Test Tools.
