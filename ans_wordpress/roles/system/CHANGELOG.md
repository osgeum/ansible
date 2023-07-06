# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.1.0]

### Added

- all: OracleLinux9 support

## [2.0.0]

### Changed

- Replaced OSS code license

## [1.9.2]

### Added

- all: Fedora36 support

### Fixed

- sys_package: make uninstall optional for git, binary

## [1.8.0]

### Added

- all: RockLinux8, Ubuntu22.4 support

## [1.7.0]

### Added

- sys_package: add brew tap and cask support

### Fixed

- sys_repository: added temporary sudo privilege to homebrew during install, brew repositories

## [1.6.0]

### Added

- sys_repository: MacOSX support, brew (HomeBrew) repository type
- sys_package: MacOSX support, brew (HomeBrew) package type
- sys_user: MacOSX support, group description (dummy field)
- sys_mc: MacOSX support, brew (HomeBrew) package type
- sys_sudo: MacOSX support
- sys_shell: MacOSX support

### Changed

- sys_package: promoted var path to end-state
- sys_shell: normalized sys_shell_users input fields
  - user -> name
  - access.owner -> access.user.owner
  - access.group -> access.group.owner

## [1.5.0]

### Added

- all: RHEL-8 and AlmaLinux8 compatibility
- sys_tools: deploy grep, gawk, sed, lsof

## [1.4.1]

### Fixed

- sys_gui_cinnamon: fixed dconf dump path

## [1.4.0]

### Added

- sys_mc: overwrite user setup flag
- sys_shell: overwrite user setup flag

### Changed

- sys_shell: moved user parameter to end-state

### Fixed

- sys_gui_cinnamon: add missing dconf path to dconf dump template

## [1.3.7]

[Unreleased]: https://github.com/serdigital64/aplatform64/compare/2.1.0...HEAD
[2.1.0]: https://github.com/serdigital64/aplatform64/compare/2.0.0...2.1.0
[2.0.0]: https://github.com/serdigital64/aplatform64/compare/1.9.2...2.0.0
[1.9.2]: https://github.com/serdigital64/aplatform64/compare/1.8.0...1.9.1
[1.8.0]: https://github.com/serdigital64/aplatform64/compare/1.7.0...1.8.0
[1.7.0]: https://github.com/serdigital64/aplatform64/compare/1.6.0...1.7.0
[1.6.0]: https://github.com/serdigital64/aplatform64/compare/1.5.0...1.6.0
[1.5.0]: https://github.com/serdigital64/aplatform64/compare/1.4.1...1.5.0
[1.4.1]: https://github.com/serdigital64/aplatform64/compare/1.4.0...1.4.1
[1.4.0]: https://github.com/serdigital64/aplatform64/compare/1.3.7...1.4.0
[1.3.7]: https://github.com/serdigital64/aplatform64/releases/tag/1.3.7
