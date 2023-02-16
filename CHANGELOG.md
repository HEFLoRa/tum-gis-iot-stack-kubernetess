# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
Versions are prefixed with `tum-gis-iot-stack-k8s-` due to usage of
[chart-releaser-action](https://github.com/helm/chart-releaser-action).
For releases `< 1.0.0` minor version step indicate breaking changes.

## [tum-gis-iot-stack-k8s-0.9.0] - 2023-02-16

### Added

- Support for high availability
  [PostgreSQL database backend](https://artifacthub.io/packages/helm/bitnami/postgresql-ha)

### Changed

- Reworked [README.md](README.md)
- Documentation updates
- Minor changes to default values
- Bump FROST-Server `2.0.6` --> `2.1.0`
- Expose Grafana SMTP settings in `values.yml`

## [tum-gis-iot-stack-k8s-0.8.2]: - 2023-02-03

### Changed

- Grafana database creation container now uses `template1` db for connection,
  as it is usually available on all postgres servers.

## [tum-gis-iot-stack-k8s-0.8.1]: - 2023-02-02

### Changed

- Bump Grafana `9.3.2` --> `9.3.6`

## [tum-gis-iot-stack-k8s-0.8.0]: - 2023-01-17

- Versions before this release are development snapshots

## [template] - 2023-01-01

### Added

### Changed

### Removed

### Fixed

### Security

### Deprecated

[template]: https://keepachangelog.com/en/1.0.0/
[tum-gis-iot-stack-k8s-0.8.0]: https://github.com/tum-gis/tum-gis-iot-stack-k8s/compare/tum-gis-iot-stack-k8s-0.1.1...tum-gis-iot-stack-k8s-0.8.0
[tum-gis-iot-stack-k8s-0.8.1]: https://github.com/tum-gis/tum-gis-iot-stack-k8s/compare/tum-gis-iot-stack-k8s-0.8.0...tum-gis-iot-stack-k8s-0.8.1
[tum-gis-iot-stack-k8s-0.8.2]: https://github.com/tum-gis/tum-gis-iot-stack-k8s/compare/tum-gis-iot-stack-k8s-0.8.1...tum-gis-iot-stack-k8s-0.8.2
[tum-gis-iot-stack-k8s-0.9.0]: https://github.com/tum-gis/tum-gis-iot-stack-k8s/compare/tum-gis-iot-stack-k8s-0.8.2...tum-gis-iot-stack-k8s-0.9.0