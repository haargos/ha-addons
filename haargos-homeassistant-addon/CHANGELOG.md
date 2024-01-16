# Changelog

## [1.4.0] - 2024-01-16

### Added

- Add-ons support
- Support for Supervisor-based logs - supervisor, host, audio, multicast, DNS.

## [1.3.0] - 2024-01-09

### Added

- Support for notifications and direct links to the HA instance
- Direct links to ZHA, devices, automations, scenes, scripts and more

### Fixed

- Fixed occurences where observations were not sent to the server

## [1.2.1] - 2023-12-07

### Added

- Adds support for linking to Zigbee devices, Automations, Scripts, Scenes and Logs from inside of an installation.

## [1.2.0] - 2023-12-07

### Added

- Adds support for docker installations outside of Home Assistant environment.
  See images with version suffixed with `-docker` - based on alpine.

### Fixed

- Gathering logs when a singular line is too long now doesn't fail.
- CPU frequency is now gathered given different OSes.
- Zigbee device gathering when Home Assistant loses state information on them.

## [1.1.36] - 2023-11-28

- Empty release

### Changed

- Changed addon output texts

## [1.1.35] - 2023-11-28

### Changed

- Changed addon output texts

## [1.1.34] - 2023-11-28

### Changed

- Changed addon output texts

## [1.1.33] - 2023-11-28

### Added

- Initial Haargos release

[1.4.0]: https://github.com/haargos/ha-addons/compare/v1.3.0...v1.4.0
[1.3.0]: https://github.com/haargos/ha-addons/compare/v1.2.1...v1.3.0
[1.2.1]: https://github.com/haargos/ha-addons/compare/v1.2.0...v1.2.1
[1.2.0]: https://github.com/haargos/ha-addons/compare/v1.1.36...v1.2.0
[1.1.36]: https://github.com/haargos/ha-addons/compare/v1.1.35...v1.1.36
[1.1.35]: https://github.com/haargos/ha-addons/compare/v1.1.34...v1.1.35
[1.1.34]: https://github.com/haargos/ha-addons/compare/v1.1.33...v1.1.34
[1.1.33]: https://github.com/haargos/ha-addons/releases/releases/tag/v1.1.33
