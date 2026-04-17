<!-- Keep a Changelog guide -> https://keepachangelog.com -->

# OceanBase JDBC Driver Changelog

## [Unreleased]

## [1.0.0] - 2026-04-15

### Added
- OceanBase database driver registration for DataGrip and all JetBrains IDEs with database support
- Bundled OceanBase Connector/J versions 2.4.14, 2.4.15, 2.4.16, and 2.4.17 — no internet download required
- Native `jdbc:oceanbase://` URL scheme with host, port (default 2881), and database fields
- Load balance URL template for multi-host HA setups (`jdbc:oceanbase:loadbalance://`)
- MySQL-dialect compatibility: SQL completion, schema introspection, and DDL generation reuse the MySQL engine

## [1.0.1] - 2026-04-17
- Changed plugin icon
