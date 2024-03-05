# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.6] - 2024-03-05
### Fixed
- Added `UTF-8 BOM` to the generated header file, which is necessary for NSIS to interpret the file as being `UTF-8`.

## [1.0.5] - 2023-11-10
### Added
- Added logging of the `makensis` call with arguments.
### Fixed
- Tweaked the logic of the `compress` parameter to only be explicit when it deviates from the default option.
- Clarified the use of the `compress` and `compression` parameters in the documentation.

## [1.0.4] - 2023-11-07
### Added
- Implemented `compress` as a parameter for the `makensis` call.

## [1.0.3] - 2020-11-26
### Fixed
- Fixed makensis location resolution from OS path environment variable ([#6](https://github.com/DigitalMediaServer/nsis-maven-plugin/pull/6)). Thanks to [@adamretter](https://github.com/adamretter) for pinpointing the problem.

## [1.0.2] - 2019-06-13
### Fixed
- [@adamretter](https://github.com/adamretter) improved `autoNsisDir` resolution ([#3](https://github.com/DigitalMediaServer/nsis-maven-plugin/pull/3)).

## [1.0.1] - 2019-05-03
### Added
- Created this changelog.

### Fixed
- [@gieza](https://github.com/gieza) fixed double hyphen bug for local artifact when using `classifier` ([#2](https://github.com/DigitalMediaServer/nsis-maven-plugin/pull/2)).

## [1.0.0] - 2018-07-29
### First release

[Unreleased]: https://github.com/DigitalMediaServer/nsis-maven-plugin/compare/v1.0.6...HEAD
[1.0.6]: https://github.com/DigitalMediaServer/nsis-maven-plugin/compare/v1.0.5...v1.0.6
[1.0.5]: https://github.com/DigitalMediaServer/nsis-maven-plugin/compare/v1.0.4...v1.0.5
[1.0.4]: https://github.com/DigitalMediaServer/nsis-maven-plugin/compare/v1.0.3...v1.0.4
[1.0.3]: https://github.com/DigitalMediaServer/nsis-maven-plugin/compare/v1.0.2...v1.0.3
[1.0.2]: https://github.com/DigitalMediaServer/nsis-maven-plugin/compare/v1.0.1...v1.0.2
[1.0.1]: https://github.com/DigitalMediaServer/nsis-maven-plugin/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/DigitalMediaServer/nsis-maven-plugin/releases/tag/v1.0.0
