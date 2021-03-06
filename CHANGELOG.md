# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [0ver](https://0ver.org) (more or less).

## [Unreleased]

## [0.0.2] - 2020-06-29

### Added

- New `ttl`, `min-ttl` and `force-generate` flags on the **get** function to manipulate credentials lengths
- New `status` function to disclose some info about the current context, cached credentials and Vault server connectivity

### Changed

- Removed some typos in the CLI flags definition
- Removed unused parameter RenewBefore on the AWSCredential objects
- Added some tests

## [0.0.1] - 2020-06-26

### Added

- Working state of the app
- Makefile
- LICENSE
- README

[Unreleased]: https://github.com/mvisonneau/vac/compare/0.0.2...HEAD
[0.0.2]: https://github.com/mvisonneau/vac/tree/0.0.2
[0.0.1]: https://github.com/mvisonneau/vac/tree/0.0.1
