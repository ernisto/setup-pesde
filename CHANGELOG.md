# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- `pesde-version` param to `version`

### Removed

- `lune-version`

## [0.3.2] - 2024-12-28

### Changed

- Revert to caching `~/.pesde` dir as a whole

## [0.3.1] - 2024-12-28

### Changed

- Changes internal code to be more reliable and readable
- Cache option will only cache `~/.pesde/bin` now

## [0.3.0] - 2024-12-06

### Added

- Caches `./pesde` directory (default false)
- `cache` input
- `path` input
- Improved testing for all OS types

## [0.2.0] - 2024-12-01

### Added

- Lune is now installed alongside Pesde as it is a prerequisite
- `lune-version` input

### Changed

- `version` -> `pesde-version` to create distinct version inputs

## [0.1.0] - 2024-11-29

### Added

Initial release!

[unreleased]: https://github.com/2jammers/setup-pesde/compare/v0.3.2...HEAD
[0.3.2]: https://github.com/2jammers/setup-pesde/compare/v0.3.1...v0.3.2
[0.3.1]: https://github.com/2jammers/setup-pesde/compare/v0.3.0...v0.3.1
[0.3.0]: https://github.com/2jammers/setup-pesde/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/2jammers/setup-pesde/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/2jammers/setup-pesde/tag/v0.1.0
