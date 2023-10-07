# Community Hass.io Add-ons: MagicMirror²

All notable changes to this add-on will be documented in this file.

The format is based on [Keep a Changelog][keep-a-changelog]
and this project adheres to [Semantic Versioning][semantic-versioning].

## Unreleased

No unreleased changes yet.

## [v0.26.1] (2023-10-08)

### Changed
- Internal Restructuring to avoid many copies

## [v0.26.0] (2023-10-08)

### Changed
- Move to S6 Startup system

## [v0.25.4] (2023-10-08)

### Changed
- Explicitly disable apparmor

## [v0.25.3] (2023-10-07)

Prior versions are still crashing due to unknown reasons, this is the attempt to fix that.

### Changed
- Remove double installation of nodejs and remove fixed build images


## [v0.25.2] (2023-10-07)

Prior versions are still crashing due to unknown reasons, this is the attempt to fix that.

### Changed
- Removed initial cloning of repo, will be performed on "rebuild" in Homeassistant then

## [v0.25.1] (2023-10-06)

### Changed
- Removed unsafe-perm from most places


## [v0.25.0] (2021-11-01)

### Changed
- Adapted internal Home assistant URL to the current one
- Switched places of repository urls

## [v0.23.0] (2018-07-18)

### Added
- Ability to run command after module installation.

## [v0.22.0] (2018-07-18)

### Added
- Default config with ip and host corrected
- HASS moduled for MM added with configuration

## [v0.21.5] (2018-07-17)

### Added

- Update MagicMirror² addon logging
- Added commands to trouble shoot via local docker container.

## [v0.21.4] (2018-07-13)

### Added

- Update MagicMirror² addon to handle module install.

## [v0.20.0] (2018-07-13)

### Added

- Initial release of MagicMirror² addon

[keep-a-changelog]: http://keepachangelog.com/en/1.0.0/
[semantic-versioning]: http://semver.org/spec/v2.0.0.html
[v0.20.0]: https://github.com/sytone/hassio-addons/tree/v0.20.0
[v0.21.4]: https://github.com/sytone/hassio-addons/tree/v0.21.4
[v0.21.5]: https://github.com/sytone/hassio-addons/tree/v0.21.5
[v0.22.0]: https://github.com/sytone/hassio-addons/tree/v0.22.0
[v0.23.0]: https://github.com/sytone/hassio-addons/tree/v0.23.0
