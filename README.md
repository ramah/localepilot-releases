# LocalePilot

Desktop app to import, validate, translate, review and export localization files. This repository holds the signed and notarized downloads only.

## Latest version

| Version | Date | Download | SHA-256 |
| --- | --- | --- | --- |
| 1.0.0 | 2026-11-11 | [LocalePilot-1.0.0-macos.dmg](https://github.com/ramah/localepilot-releases/releases/download/v1.0.0/LocalePilot-1.0.0-macos.dmg) | [.sha256](https://github.com/ramah/localepilot-releases/releases/download/v1.0.0/LocalePilot-1.0.0-macos.sha256) |

Permanent link to the installer of the latest version: <https://github.com/ramah/localepilot-releases/releases/latest/download/LocalePilot-macos.dmg> (checksum: `LocalePilot-macos.sha256`).

## Install

1. Download the `.dmg` of the latest version and open it (or unzip the `.zip`).
2. Drag **LocalePilot.app** into your Applications folder.
3. Open it. macOS checks the notarization on first launch, so it needs an internet connection once.

## Verify the download

Put the `.zip` and its `.sha256` file in the same folder, then run:

```sh
shasum -a 256 -c LocalePilot-<version>-macos.sha256
```

## History

- [v1.0.0](https://github.com/ramah/localepilot-releases/releases/tag/v1.0.0), 2026-11-11
