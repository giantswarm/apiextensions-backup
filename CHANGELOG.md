# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Fixed

- Downgrade `apimachinery` due to dependency issues.

## [0.3.0] - 2025-01-22

### Added

- Add `clustersToExcludeRegex` property to etcd backup type in order to skip clusters etcd backup will run.

## [0.2.2] - 2022-06-14

## [0.2.1] - 2022-06-10

### Added

- Add `ClustersRegex` property to etcd backup type in order to allow select which clusters etcd backup will run.

## [0.2.0] - 2022-02-07

### Added

- Add `additionalPrinterColumns` to the CRD so that more information is shown when fetching it from the k8s API.

## [0.1.0] - 2022-01-23

[Unreleased]: https://github.com/giantswarm/apiextensions-backup/compare/v0.3.0...HEAD
[0.3.0]: https://github.com/giantswarm/apiextensions-backup/compare/v0.2.2...v0.3.0
[0.2.2]: https://github.com/giantswarm/apiextensions-backup/compare/v0.2.1...v0.2.2
[0.2.1]: https://github.com/giantswarm/apiextensions-backup/compare/v0.2.0...v0.2.1
[0.2.0]: https://github.com/giantswarm/apiextensions-backup/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/giantswarm/apiextensions-application/releases/tag/v0.1.0
