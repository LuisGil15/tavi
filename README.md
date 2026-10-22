# Tavi

<p align="center">
  A native, local-first REST client for macOS and iPad. Organize APIs, send requests, and keep your workspaces in your control.
</p>

<p align="center">
  <a href="https://github.com/LuisGil15/tavi/releases/latest"><img src="https://img.shields.io/badge/Tavi%20Direct-1.0.2-0A84FF?style=flat-square" alt="Tavi Direct version 1.0.2"></a>
  <img src="https://img.shields.io/badge/macOS-15%2B-black?style=flat-square&logo=apple" alt="macOS 15 or later">
  <img src="https://img.shields.io/badge/Developer%20ID-signed-34C759?style=flat-square" alt="Signed with Developer ID">
  <img src="https://img.shields.io/badge/Apple-notarized-34C759?style=flat-square" alt="Notarized by Apple">
</p>

<p align="center">
  <a href="https://apps.apple.com/mx/app/tavi/id6819794965">
    <img src="assets/app-store-badge-black-en.svg" alt="Download on the App Store" width="180">
  </a>
</p>

Tavi keeps API work in a native workspace: requests, environments, variables, and response history—without requiring an account.

## What you can do

- Organize requests into workspaces and folders.
- Send HTTP requests with query parameters, headers, authentication, and JSON or raw bodies.
- Reuse global and environment variables; store secret values in Apple Keychain.
- Review request history and capture values from JSON responses.
- Import from Tavi, Insomnia, OpenAPI, and Swagger; export selected workspaces.
- Keep data local, or enable private iCloud sync when you choose.

## Choose your Tavi

### App Store

Use the App Store version on Mac and iPad. Updates are delivered through the App Store.

### Tavi Direct for macOS

The direct Mac edition is distributed from this repository. It is signed and notarized by Apple.

**Requirements:** macOS 15 or later.

1. Download [Tavi Direct 1.0.2 for macOS](https://github.com/LuisGil15/tavi/releases/download/v1.0.2/Tavi-1.0.2.dmg).
2. Open the disk image and drag **Tavi** to **Applications**.
3. Launch Tavi from Applications.

You should not need to disable Gatekeeper or remove the quarantine attribute. The 1.0.2 release adds in-app updates for future direct releases. If you are still on 1.0.1, install 1.0.2 manually once.

### Homebrew

Homebrew installs the same direct macOS edition. The tap is private, so access must be granted before using these commands:

```sh
brew tap LuisGil15/tavi
brew install --cask tavi
```

To update later:

```sh
brew update
brew upgrade --cask tavi
```

The cask is maintained in [LuisGil15/homebrew-tavi](https://github.com/LuisGil15/homebrew-tavi).

## Privacy

Tavi does not require an account. Workspace data stays on your device unless you enable private iCloud sync. Secret values are stored in Apple Keychain. Read the [privacy and security notes](https://github.com/LuisGil15/tavi-source/blob/main/docs/PRIVACY.md).

## Links

- [Latest Tavi Direct release](https://github.com/LuisGil15/tavi/releases/latest)
- [App Store](https://apps.apple.com/mx/app/tavi/id6819794965)
- [Source code](https://github.com/LuisGil15/tavi-source)
- [Homebrew cask](https://github.com/LuisGil15/homebrew-tavi)

---

<p align="center">Made with care by Luis Gil.</p>
