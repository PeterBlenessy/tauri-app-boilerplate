# Changelog
All notable changes to this project will be documented in this file.

## Changelog format guideline
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

### vMAJOR.MINOR.PATCH - YYYY-MM-DD

- Added new features.
- Changed existing functionality.
- Deprecated soon-to-be removed features.
- Removed features.
- Fixed bugs.
- Security in case of vulnerabilities.

## [BACKLOG]

### [MAJOR]

### [MINOR]

### [PATCH]
- Add support for [Windows code signing](https://tauri.app/v1/guides/distribution/sign-windows).
- Add support for [Linux code signing](https://tauri.app/v1/guides/distribution/sign-linux).

## v0.0.7 - [UNRELEASED]

## v0.0.6 - 2023-05-23
- Added support for Updater.

## v0.0.5 - 2023-05-21
- Removed signing identity from tauri.conf.json.

## v0.0.4 - 2023-05-21
- Added signing identity to tauri.conf.json.

## v0.0.3 - 2023-05-21
- Added support for [macOS code signing](https://tauri.app/v1/guides/distribution/sign-macos).

## v0.0.2 - 2023-05-21
- Changed the bundle identifier in `tauri.conf.json > tauri > bundle > identifier` from `com.tauri.dev` to `com.addable.tauri-app-boilerplate`.

## v0.0.1 - 2023-05-21
- Initial release after running cargo create-tauri-app and setting upp GitHub Actions release.