<h1 align="center">
  <img src="assets/app-icon.png" alt="Tavi app icon" width="150">
  <br>
  Tavi
</h1>

<p align="center">
  An API client. Your APIs. Your workspace.
</p>

<p align="center">
  <a href="https://github.com/LuisGil15/tavi/releases/latest"><img src="https://img.shields.io/badge/version-1.0.2-0A84FF?style=flat-square" alt="Latest direct version 1.0.2"></a>
  <img src="https://img.shields.io/badge/macOS-15%2B-black?style=flat-square&logo=apple" alt="macOS 15 or later">
  <img src="https://img.shields.io/badge/Developer%20ID-signed-34C759?style=flat-square" alt="Signed with Developer ID">
  <img src="https://img.shields.io/badge/Apple-notarized-34C759?style=flat-square" alt="Notarized by Apple">
</p>

<p align="center">
  <a href="https://ko-fi.com/luisgildev"><img src="https://img.shields.io/badge/Ko--fi-Support-FF5E5B?style=flat-square&logo=ko-fi&logoColor=white" alt="Support Tavi on Ko-fi"></a>
  <a href="https://buymeacoffee.com/luisgil"><img src="https://img.shields.io/badge/Buy_Me_a_Coffee-Support-FFDD00?style=flat-square&logo=buy-me-a-coffee&logoColor=black" alt="Support Tavi on Buy Me a Coffee"></a>
</p>

<table align="center" cellpadding="0" cellspacing="0">
  <tr>
    <td align="center"><a href="https://apps.apple.com/mx/app/tavi/id6819794965"><img src="assets/app-store-badge-black-en.svg" alt="Download on the App Store" width="180" height="60"></a></td>
    <td width="20">&nbsp;</td>
    <td align="center"><a href="https://github.com/LuisGil15/tavi/releases/latest"><img src="assets/download-tavi-direct.svg" alt="Download Tavi Direct for macOS" width="180" height="60"></a></td>
  </tr>
</table>

Tavi is a native, local-first REST client for Mac and iPad. Organize APIs into workspaces and folders, send requests, and keep your environments and response history close at hand.

## What you can do

- Build requests with HTTP methods, query parameters, headers, authentication, and JSON or raw bodies.
- Organize APIs into workspaces and folders, then reuse global and environment-specific variables.
- Keep secrets in Apple Keychain and request history on your device.
- Capture values from JSON responses to use in later requests.
- Import Tavi, Insomnia, OpenAPI, and Swagger collections; export selected workspaces.
- Keep workspaces local or enable optional private iCloud sync.

## Install

### App Store

Get Tavi for Mac and iPad from the [App Store](https://apps.apple.com/mx/app/tavi/id6819794965). App Store updates arrive through Apple.

### Homebrew (macOS)

The Homebrew cask installs **Tavi Direct**, the signed and notarized macOS edition. The tap is private, so access must be granted before installation.

```sh
brew tap LuisGil15/tavi
brew install --cask tavi
```

Update later with:

```sh
brew update
brew upgrade --cask tavi
```

The cask is maintained in [LuisGil15/homebrew-tavi](https://github.com/LuisGil15/homebrew-tavi).

### Manual installation (macOS)

**Requirements:** macOS 15 or later.

1. Download [Tavi Direct 1.0.2](https://github.com/LuisGil15/tavi/releases/download/v1.0.2/Tavi-1.0.2.dmg).
2. Open the disk image and drag **Tavi** to **Applications**.
3. Launch Tavi from Applications.

Tavi Direct is signed with Developer ID and notarized by Apple. You should not need to disable Gatekeeper or remove the quarantine attribute.

## Updates and integrity

The [latest release](https://github.com/LuisGil15/tavi/releases/latest) contains the current signed macOS build and its release files. Tavi Direct 1.0.2 adds in-app updates for future direct releases; users upgrading from 1.0.1 need to install 1.0.2 manually once. The App Store version updates separately through Apple.

## Privacy

Tavi does not require an account. Workspace data stays on your device unless you enable private iCloud sync. Secret values are stored in Apple Keychain. Read the [privacy and security notes](https://github.com/LuisGil15/tavi-source/blob/main/docs/PRIVACY.md).

## Links

- [Latest Tavi Direct release](https://github.com/LuisGil15/tavi/releases/latest)
- [App Store](https://apps.apple.com/mx/app/tavi/id6819794965)
- [Source code](https://github.com/LuisGil15/tavi-source)
- [Homebrew cask](https://github.com/LuisGil15/homebrew-tavi)
- [Report an issue](https://github.com/LuisGil15/tavi/issues)

<details>
<summary>Release maintenance</summary>

Publish signed, notarized macOS artifacts as GitHub Releases in this repository. Keep the versioned DMG, ZIP, checksum, and appcast feed consistent with the Homebrew cask and direct-update feed. Do not upload source archives or project files here.

</details>

---

<p align="center">Made with care by Luis Gil.</p>
