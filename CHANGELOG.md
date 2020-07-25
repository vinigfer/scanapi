# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- The report page now has a favicon [#223](https://github.com/scanapi/scanapi/pull/223)
- Bandit security audit tool [#219](https://github.com/scanapi/scanapi/pull/219)

### Removed
- APIKeyMissingError

## [1.0.5] - 2020-07-18
### Fixed
- Status icons on report were not vertically centered [#195](https://github.com/scanapi/scanapi/pull/195)

## [1.0.4] - 2020-06-25

## [1.0.3] - 2020-06-25
### Added
- MANIFEST.in

## [1.0.2] - 2020-06-25
### Fixed
- Fix for TemplateNotFound Error [#197](https://github.com/scanapi/scanapi/pull/197)

## [1.0.1] - 2020-06-25
### Fixed
- Report example images not loading on PyPI [#193](https://github.com/scanapi/scanapi/pull/193)

## [1.0.0] - 2020-06-25
### Added
- Add new HTML template [#157](https://github.com/scanapi/scanapi/pull/157)
- Tests key [#152](https://github.com/scanapi/scanapi/pull/152)
- `-h` alias for `--help` option [#172](https://github.com/scanapi/scanapi/pull/172)
- Test results to report [#177](https://github.com/scanapi/scanapi/pull/177)
- Add test errors to the report [#187](https://github.com/scanapi/scanapi/pull/187)
- Hides sensitive info in URL [#185](https://github.com/scanapi/scanapi/pull/185)
- CLI options explanation [#189](https://github.com/scanapi/scanapi/pull/189)

### Changed
- Unified keys validation in a single method [#151](https://github.com/scanapi/scanapi/pull/151)
- Default template to html [#173](https://github.com/scanapi/scanapi/pull/173)
- Project name color on html reporter to match ScanAPI brand [#172](https://github.com/scanapi/scanapi/pull/172)
- Hero banner on README [#180](https://github.com/scanapi/scanapi/pull/180)
- Entry point to `scanapi:main` [#172](https://github.com/scanapi/scanapi/pull/172)
- `--spec-path` option to argument [#172](https://github.com/scanapi/scanapi/pull/172)
- Improve test results on report [#186](https://github.com/scanapi/scanapi/pull/186)
- Improve Error Message for Invalid Python code error [#187](https://github.com/scanapi/scanapi/pull/187)
- Handle properly exit errors [#187](https://github.com/scanapi/scanapi/pull/187)
- Update README.md [#191](https://github.com/scanapi/scanapi/pull/191)

### Fixed
- Duplicated status code row from report [#183](https://github.com/scanapi/scanapi/pull/183)
- Sensitive information render on report [#183](https://github.com/scanapi/scanapi/pull/183)

### Removed
- Console Report [#175](https://github.com/scanapi/scanapi/pull/175)
- Markdown Report [#179](https://github.com/scanapi/scanapi/pull/179)
- `--reporter` option [#179](https://github.com/scanapi/scanapi/pull/179)

## [0.1.0] - 2020-05-14
### Added
- Automated pypi deploy - [#144](https://github.com/scanapi/scanapi/pull/144)

## [0.0.19] - 2020-05-11
### Added
- PATCH HTTP method - [#113](https://github.com/scanapi/scanapi/pull/113)
- Ability to have API spec in multiples files - [#125](https://github.com/scanapi/scanapi/pull/125)
- CLI `--config-path` option - [#128](https://github.com/scanapi/scanapi/pull/128)
- CLI `--template-path` option - [#126](https://github.com/scanapi/scanapi/pull/126)
- GitHub Action checking for missing changelog entry - [#134](https://github.com/scanapi/scanapi/pull/134)

### Changed
- Make markdown report a bit better - [#96](https://github.com/scanapi/scanapi/pull/96)
- `base_url` keyword to `path` [#116](https://github.com/scanapi/scanapi/pull/116)
- `namespace` keyword to `name` [#116](https://github.com/scanapi/scanapi/pull/116)
- `method` keyword is not mandatory anymore for requests. Default is `get` [#116](https://github.com/scanapi/scanapi/pull/116)
- Replaced `hide` key on report config by `hide-request` and `hide-response` [#116](https://github.com/scanapi/scanapi/pull/116)
- Moved black check from CircleCI to github actions [#136](https://github.com/scanapi/scanapi/pull/136)

### Fixed
- Cases where custom var has upper case letters [#99](https://github.com/scanapi/scanapi/pull/99)

### Removed
- Request with no endpoints [#116](https://github.com/scanapi/scanapi/pull/116)

## [0.0.18] - 2020-01-02
### Changed
- Return params/headers None when request doesn't have params/headers [#87](https://github.com/scanapi/scanapi/pull/87)

### Fixed
- Report-example image not loading on PyPi [#86](https://github.com/scanapi/scanapi/pull/86)

## [0.0.17] - 2019-12-19
### Added
- Added PyPI Test section to CONTRIBUTING.md
- Added templates to pypi package - fix [#85](https://github.com/scanapi/scanapi/pull/85)

## [0.0.16] - 2019-12-18
### Fixed
- Fixed No module named 'scanapi.tree' [#83](https://github.com/scanapi/scanapi/pull/83)

## [0.0.15] - 2019-12-14
### Added
- CodeCov Setup
- CircleCI Setup

### Changed
- Updated Documentation
- Increased coverage
- Used dot notation to access responses inside api spec
- Renamed option report_path to output_path
- Reporter option -r, --reporter [console|markdown|html]

### Fixed
- Fixed join of urls to keep the last slash

### Removed
- Removed requirements files and put every dependency under setup.py
- Removed dcvars key

## [0.0.14] - 2019-10-09
### Added
- Add math, time, uuid and random libs to be used on api spec

## [0.0.13] - 2019-10-07
### Changed
- Bumped version

## [0.0.12] - 2019-08-15
### Added
- Used env variables from os

## [0.0.11] - 2019-08-09
### Added
- Added Docker file

## [0.0.10] - 2019-08-09
### Added
- Add logging
- Option to hide headers fields

### Fixed
- Fix vars interpolation

[Unreleased]: https://github.com/camilamaia/scanapi/compare/v1.0.5...HEAD
[1.0.5]: https://github.com/camilamaia/scanapi/compare/v1.0.4...v1.0.5
[1.0.4]: https://github.com/camilamaia/scanapi/compare/v1.0.3...v1.0.4
[1.0.3]: https://github.com/camilamaia/scanapi/compare/v1.0.2...v1.0.3
[1.0.2]: https://github.com/camilamaia/scanapi/compare/v1.0.1...v1.0.2
[1.0.1]: https://github.com/camilamaia/scanapi/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/camilamaia/scanapi/compare/v0.1.0...v1.0.0
[0.1.0]: https://github.com/camilamaia/scanapi/compare/v0.0.19...v0.1.0
[0.0.19]: https://github.com/camilamaia/scanapi/compare/v0.0.18...v0.0.19
[0.0.18]: https://github.com/camilamaia/scanapi/compare/v0.0.17...v0.0.18
[0.0.17]: https://github.com/camilamaia/scanapi/compare/v0.0.16...v0.0.17
[0.0.16]: https://github.com/camilamaia/scanapi/compare/v0.0.15...v0.0.16
[0.0.15]: https://github.com/camilamaia/scanapi/compare/v0.0.14...v0.0.15
[0.0.14]: https://github.com/camilamaia/scanapi/compare/v0.0.13...v0.0.14
[0.0.13]: https://github.com/camilamaia/scanapi/compare/v0.0.12...v0.0.13
[0.0.12]: https://github.com/camilamaia/scanapi/compare/v0.0.11...v0.0.12
[0.0.11]: https://github.com/camilamaia/scanapi/compare/v0.0.10...v0.0.11
[0.0.10]: https://github.com/camilamaia/scanapi/releases/tag/v0.0.10
