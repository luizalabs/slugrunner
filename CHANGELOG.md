# Change Log
All notable changes from the Luizalabs team to this project will be documented in this file.

## [3.4.0] - 2018-07-30
### Added
- pt_BR.UTF-8 locale support

## [3.3.0] - 2018-06-28
### Changed
- Remove unused `ONBUILD` instructions of Dockerfile

## [3.2.0] - 2018-06-06
### Changed
- Use heroku:16 as base image
- Install openjdk-8-jre-headless

## [3.1.0] - 2018-03-27
### Fixed
- Solve tar extraction issues by adding `--no-overwrite-dir`

## [3.0.1] - 2018-03-05
### Fixed
- Don't remove the pre-downloaded slug.tgz

## [3.0.0] - 2018-02-28
### Added
- Support to use a previously downloaded slug
- .travis.yml and .ci-docker.sh
