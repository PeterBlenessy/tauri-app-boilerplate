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

## v0.0.14 - [UNRELEASED]

## v0.0.13 - 2023-05-24
- Changed Updater endpoint.

## v0.0.12 - 2023-05-24
- Test release in order to verify that Updater works now that relevant artefacts are automatically built, signed and released using Github Actions.

## v0.0.11 - 2023-05-24
- Added conditional check for platform being macos-latest when setting aarch64-apple-darwin as target to avoid it being installed on windows and linux platforms.

## v0.0.10 - 2023-05-24
- Removed macOS universal-apple-darwin as it defaulted to x86_64-apple-darwin.
- Added aarch64-apple-darwin as target for rust setup, otherwise it will default to x86_64-apple-darwin.

## v0.0.9 - 2023-05-24
- Added new matrix settings as args to tauri-action.
- Fixed release date for v0.0.8.

## v0.0.8 - 2023-05-24
- Changed GitHub Actions matrix settings to include all macOS architectures.

## v0.0.7 - 2023-05-23
- Added environment variables TAURI_PRIVATE_KEY and TAURI_KEY_PASSWORD to release.yml. Needed by Updater.

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