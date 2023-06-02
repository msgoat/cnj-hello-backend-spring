# Changelog
All notable changes to `cnj-hello-backend-spring` will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
### Changed
### Fixed

## [7.3.0] - 2023-06-02
### Changed
- upgraded to Spring Boot 3.1.0
- switched back from undertow to tomcat

## [7.2.0] - 2023-02-22
### Changed
- upgraded to Spring Boot 3.0.2
- consolidated versions of all dependencies with Spring Boot versions
- consolidated usage of cnj-common-test* libraries

## [7.1.0] - 2022-11-25
### Changed
- upgraded to Spring Boot 3.0.0

## [7.0.0] - 2022-11-16
### Changed
- upgraded to Java 17
- added new envvar AGENT_JAVA_OPTS to configure java agents without changing the default java options

## [6.3.0] - 2022-11-11
### Added
### Changed
- upgraded to Spring Boot 2.7.5
- activated liveness and readiness health endpoints

## [6.2.0] - 2022-11-08
### Added
### Changed
- moved build from Drone to AWS CodeBuild

## [6.1.0] - 2022-05-24
### Added
### Changed
- switched to Eclipse Temurin 11 Alpine image to shrink image size
- upgraded to Spring Boot 2.7.0

## [6.0.0] - 2022-05-24
### Added
### Changed
- re-released version 6.0.0 after repo split
