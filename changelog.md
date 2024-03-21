# Changelog
All notable changes to `cnj-hello-backend-spring` will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
### Changed
### Fixed

## [8.2.0] - 2024-02-28
### Changed
- upgraded Spring Boot to version 3.2.4
- consolidated common dependencies
- upgraded common cloudtrain dependencies

## [8.1.0] - 2024-01-09
### Changed
- simplified POM

## [8.0.0] - 2023-11-30
### Changed
- upgraded Spring Boot to version 3.1.5
- upgraded Java to version 21
- upgraded Maven plugins and dependencies
- build now packages and pushes Helm charts
- deploy now uses packaged Helm charts
- consolidated POM with other showcases
- consolidated system tests with other showcases
- build tags git branch after successful completion
- commit-stage builds produce Docker images for linux/amd64 and linux/arm64/v8 platforms now
- Docker images use Generational Z garbage collector by default

## [7.4.0] - 2023-07-05
### Changed
- added explicit dependency to CloudTrain Maven repository to POM to simplify local builds
- allowed anonymous read access to CloudTrain Maven repository to simplify local builds
- added global docker-compose.yml file to simplify local execution 
- improved documentation in README.md

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
