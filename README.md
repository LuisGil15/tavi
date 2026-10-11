# Tavi Releases

Private distribution repository for signed Tavi macOS release artifacts. This
repository contains release binaries and checksums only; application source is
maintained separately in `LuisGil15/tavi-source`.

## Release assets

Each version is published as a GitHub Release tagged `v<version>` with:

- `Tavi-<version>.dmg` for drag-and-drop installation;
- `Tavi-<version>.zip` for managed deployment;
- `Tavi-<version>.sha256` for integrity verification.

The Homebrew cask in `LuisGil15/homebrew-tavi` downloads the versioned DMG from
this repository. Keep release tags and asset names consistent with that cask.

## Publishing

Build and sign artifacts from the source checkout with `scripts/release-macos.sh`,
then publish the generated files from its `dist/` directory:

```sh
gh release create "v<VERSION>" dist/Tavi-<VERSION>.dmg dist/Tavi-<VERSION>.zip dist/Tavi-<VERSION>.sha256 \
  --repo LuisGil15/tavi \
  --title "Tavi <VERSION>" \
  --notes-file <RELEASE_NOTES_FILE>
```

Do not upload source archives or project files to this repository.
