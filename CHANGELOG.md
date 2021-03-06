# Change log
This log follows the conventions of
[keepachangelog.com](http://keepachangelog.com/).

## [Unreleased]
Nothing yet.

## [Version 0.3.0] - 2019-11-09
### Changed
- Broke the `data` module into three: Added a `measure` module for measurement
  functions and a `schema` module for validation, leaving the rest in place.

### Added
- Added perfunctory support for legends. API stability not guaranteed.
- Added an output `filename` parameter to the CLI, for scripting.
- Exposed the `bowl-radii` and `error-body-positive` parameters through the
  CLI.
- Added an option parser map, for deserialization in the DMOTE application.

### Developer
- Added parameter parsers for use with serialized inputs in other applications.
- Added trivial unit tests.

### Fixed
- More default values now appear in the CLI.

## [Version 0.2.0] - 2019-06-01
### Changed
- Removed CLI-only defaults for DFM error measurements. This reduces
  potential differences between library and CLI results.

### Added
- Added the option of print supports: For stems shorter than skirts, for skirts
  longer than stems, and horizontally, between skirt and stem.
- Added vaulted ceilings to the interior of minimal caps.
- Exposed the `top-size` and `skirt-thickness` parameters through the CLI.

## [Version 0.1.1] - 2019-03-24
### Fixed
- Converted a mandatory `union` to a maybe for marginally simpler maquettes.

### Developer
- Delegated face size to `scad-app`.

## Version 0.1.0 - 2019-03-23
### Added
- Minimal and maquette styles.

[Unreleased]: https://github.com/veikman/dmote-keycap/compare/v0.3.0...HEAD
[Version 0.3.0]: https://github.com/veikman/dmote-keycap/compare/v0.2.0...v0.3.0
[Version 0.2.0]: https://github.com/veikman/dmote-keycap/compare/v0.1.1...v0.2.0
[Version 0.1.1]: https://github.com/veikman/dmote-keycap/compare/v0.1.0...v0.1.1
