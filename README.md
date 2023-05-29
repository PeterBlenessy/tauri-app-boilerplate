# Tauri + Vue 3

This template should help get you started developing with Tauri + Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

## Getting started

* Download the zip-archive](https://github.com/PeterBlenessy/tauri-app-boilerplate/archive/refs/heads/master.zip) and unpack it.
* Install [prerequisites for developing Tauri apps](https://tauri.app/v1/guides/getting-started/prerequisites)
* Run `yarn tauri dev` to launch the app.

## Customize - general

* Search and replace any occurences of `PeterBlenessy`, `addable`and `tauri-app-boilerplate` with what better corresponds to your project.
* Edit the `version` in `package,json`.
* Edit `CHANGELOG.md` to reflect your needs. Note, that the scripts in `package.json` use the release version comments from this file as git commit messages.

## Customize - bundle, sign, notarize, update
* Install [GitHub CLI](https://cli.github.com) if you intend to use the git related scripts in `package.json`.
* If you intend to sign and notarize your macOS app, follow the description for [macOS Code Signing](https://tauri.app/v1/guides/distribution/sign-macos). This allows the app to automatically update itself when an update is available. See next bullet.
* Make sure to configure required secrets if you intend to build and release your app binaries using GitHub Actions and the release.yml workflow that is included.
* Replace the `tauri.updater.pubkey` with your own pubic key for signing the Updater files. Read more [here](https://tauri.app/v1/guides/distribution/updater).

## Next steps
What comes hereafter is up to you and to get a head start, make sure to check out the [Tauri guides](https://tauri.app/v1/guides/).