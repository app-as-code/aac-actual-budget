# Changelog

All notable changes to this deployment definition are documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Changed

- Upstream image tracks Actual Budget `26.10.0-alpine` as defined in `service.yml`.

## [0.0.1]

### Added

- Initial App-as-Code service definition for Actual Budget.
- Web interface on port 5006 with Traefik routing and automatic DNS.
- Persistent data volume for user data.
- Optional OpenID Connect login configuration.
- README with configuration reference and project icon.
