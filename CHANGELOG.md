# Change log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](https://semver.org/).

The format of this change log follows the advice given at [Keep a CHANGELOG](https://keepachangelog.com).

## [Unreleased]

### Added

- Allow 'insecure' packages (required for Moodle Composer transition).

### Changed

- Switch to https://moodle.org repository.

### Removed

- Removed unnecessary Moodle installation path
- Removed unused `cweagans/composer-patches` plugin approval

## [1.0.3] - 2026-01-16

### Changed

- Removed `cweagans/composer-patches` dependency.

## [1.0.2] - 2026-01-16

### Added

- Added `auth.json` to `.gitignore`.

## [1.0.1] - 2026-01-06

### Added

- Ignore the `/testdata` directory.

### Changed

- Correct paths for ignored directories.

## [1.0.0] - 2026-01-06

### Added

- Include cweagans/composer-patches as a default dependency
- Provide default `.gitignore`

### Changed

- Switch to released version of `moodle/moodle-composer-scaffold`.

## [0.4.0] - 2025-12-19

### Changed

- Use a minimum version of Moodle (^5.1).

## [0.3.1] - 2025-12-18

### Fixed

- Add gitattributes to ignore certain files from distribution.

## [0.3.0] - 2025-12-18

### Changed

- Updated the scaffold project name to `moodle/moodle-composer-scaffold`.

## [0.2.0] - 2025-12-18

### Added

- Initial release
