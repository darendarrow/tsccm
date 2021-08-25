# Changelog

All notable changes to [**TSCCM** *(Tenable.SC CLI Manager)* by LimberDuck][1] project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.0.2] - 2021-08-25

### Added

- `role --list` command lists parameters `id`, `name`, `createdTime`, `modifiedTime`, `organizationCounts`
- `--port` option to specify port number

### Changed

- `credential --list` command lists parameters `id`, `name`, `ownerUsername`, `createdTime`, `modifiedTime`
- `group --list` command lists parameters `id`, `name`, `createdTime`, `modifiedTime`
- `policy --list` command lists parameters `id`, `name`, `ownerUsername`, `createdTime`, `modifiedTime`
- `scan --list` command lists parameters `id`, `name`, `ownerUsername`, `createdTime`, `modifiedTime`
- `scan-result --list` command lists parameters `id`, `name`, `ownerUsername`, `createdTime`, `modifiedTime`
- `user --list` command lists parameters `id`, `username`, `firstname`, `lastname`, `roleName`, `createdTime`, `modifiedTime`, `lastLogin`
- `status` command renamed to `server`
- `server` options `--status`, `--ips`, `--version

## [0.0.1] - 2021-08-18

- initial release


[0.0.2]: https://github.com/LimberDuck/nessus-file-analyzer/compare/v0.0.1...v0.0.2
[0.0.1]: https://github.com/LimberDuck/tsccm/releases/tag/v0.0.1

[1]: https://github.com/LimberDuck/tsccm