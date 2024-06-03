# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

### Added

### Changed

### Deprecated

### Removed

### Fixed

## [0.1.0]

### Added

- First release of `github.come/elastic/elastic-agent-autodiscover`.
- Add CHANGELOG.md for documenting changes in `elastic-agent-autodiscover`.


[Unreleased]: https://github.com/elastic/elastic-agent-autodiscover/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/elastic/elastic-agent-autodiscover/compare/v0.0.0...v0.1.0


## [0.6.2]

### Changed

- Usage of env var `NODE_NAME` precedes `machine-id` for kubernetes node discovery.


[0.6.2]: https://github.com/elastic/elastic-agent-autodiscover/compare/v0.6.1...v0.6.2


## [0.6.7]

### Changed

- Update NewNodePodUpdater and NewNamespacePodUpdater functions to conditionally check and update kubernetes metadata enrichment of pods


[0.6.7]: https://github.com/elastic/elastic-agent-autodiscover/compare/v0.6.2...v0.6.7

## [0.6.9]

### Changed

- Update GenerateHints function to check supported list of hints


[0.6.9]: https://github.com/elastic/elastic-agent-autodiscover/compare/v0.6.8...v0.6.9

## [0.6.12]

### Changed

- Enhance GenerateHints function to check supported list of hints for multiple datastreams and metricsets


[0.6.12]: https://github.com/elastic/elastic-agent-autodiscover/compare/v0.6.10...v0.6.12


## [0.6.13]

### Changed

- Enhance GenerateHints function with validate flag to enable the validation of hints


[0.6.13]: https://github.com/elastic/elastic-agent-autodiscover/compare/v0.6.12...v0.6.13

## [0.6.14]

### Changed

- Bump golang.org/x/net from 0.17.0 to 0.23.0 [#90]

[0.6.14]: https://github.com/elastic/elastic-agent-autodiscover/compare/v0.6.13...v0.6.14
[#90]: https://github.com/elastic/elastic-agent-autodiscover/pull/90

## [0.7.0]

Release date: 2024-06-03

### Changed

- Update Kubernetes client library `client-go` from `v0.23.4` to `v0.29.5` [#93]

  This is a breaking change that removes support for [PodSecurityPolicy](https://kubernetes.io/docs/concepts/security/pod-security-policy/).

[0.7.0]: https://github.com/elastic/elastic-agent-autodiscover/compare/v0.6.14...v0.7.0
[#93]: https://github.com/elastic/elastic-agent-autodiscover/pull/93
