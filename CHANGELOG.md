# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- add astarte_import tool, which allows users to import devices and data using XML files.
- Add new `/v1/socket` route for Astarte Channels. The `/socket` route is **deprecated** and will be
  removed in a future release.

### Changed
- Use separate docker images with docker-compose
- Use Scylla instead of Cassandra with docker-compose

## [0.10.2] - 2019-12-09

## [0.10.1] - 2019-10-02

## [0.10.0] - 2019-04-16

## [0.10.0-rc.0] - 2019-04-03

## [0.10.0-beta.3] - 2018-12-19
### Fixed
- docker-compose: Ensure CFSSL persists the CA when no external CA is provided.

## [0.10.0-beta.2] - 2018-10-19
### Added
- Automatically add begin and end delimiters to authorization regular expressions.

## [0.10.0-beta.1] - 2018-08-10
### Added
- First Astarte release.
