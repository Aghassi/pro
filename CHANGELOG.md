# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.11.2 - 2018-05-25

Updated Renovate to v12.21.17

### Fixed
- npmrc: don’t massage naked ‘_auth’

## 0.11.1 - 2018-05-22

### Changed
- Updated Renovate to v12.21.16

### Fixed
- Remove evaluation footer when in commercial mode

## 0.11.0 - 2018-05-09

### Changed
- Updated Renovate to v12.21.2

## 0.10.0 - 2018-04-28

### Added
- Listen on `process.env.PORT` if specified
- Use `process.env.DATABASE_URL` if present

### Changed
- Updated Renovate to v12.7.1

### Fixed
- Don't attempt to load pem app key if already set in env
- Add check to avoid undefined error in err handler

## 0.9.0 - 2018-04-24

Initial release of Renovate Pro
