# Installing RelayDesk

[← Documentation](README.md)

## Download

[Download for macOS](https://github.com/NicoPFr/RelayDesk/releases/latest/download/RelayDesk.dmg) · [Latest release notes and checksum](https://github.com/NicoPFr/RelayDesk/releases/latest)

The download link follows the latest public release. For a specific version, use its release page: [RelayDesk 2.11.0](https://github.com/NicoPFr/RelayDesk/releases/tag/v2.11.0). The DMG is a Release Asset; GitHub's repository ZIP is documentation, not the app.

## Requirements and validation coverage

RelayDesk 2.11.0 contains Apple Silicon and Intel executables and targets macOS 12 or later. This deployment target does not mean every OS version or processor has been tested. The maintainer personally confirmed that this exact DMG launches and works on macOS. The exact OS version and processor for that check were not recorded; a separate fresh-user installation, persistence/relaunch matrix, and broad compatibility testing have not been independently verified.

The main interface is currently primarily in French. SSH/SFTP requires access to a server and the authentication appropriate to that server. Core local terminal and SSH workflows do not require a cloud account.

## Install

1. Download **RelayDesk.dmg** from the official GitHub Release.
2. Compare its checksum with the SHA-256 in the release notes. In Terminal, run `shasum -a 256` followed by the downloaded file's path.
3. Open the DMG and drag **RelayDesk** to **Applications**.
4. Open RelayDesk from Applications and follow macOS's security guidance.

## Signing and macOS security

This release has an ad-hoc signature, **without Developer ID signing and without notarization**. That signature checks bundle integrity; it is not an Apple-issued developer identity or an Apple malware review.

macOS may warn that the developer cannot be verified or that Apple cannot check the app for malicious software, and may prevent it from opening. Device-management policies may also block launch. Read [Apple's guidance on safely opening apps](https://support.apple.com/102445). This guide does not require disabling protections or removing quarantine metadata.

If launch is blocked, report the exact message and your macOS version using the [installation problem template](https://github.com/NicoPFr/RelayDesk/issues/new?template=installation_problem.md).

## First launch and updates

The package contains no developer connection profiles or saved user state. RelayDesk can discover your own OpenSSH configuration; those connections are read from your Mac. See [local data and privacy](privacy.md) before sharing logs or changing application data.

A public in-app update channel is not configured. Use GitHub Releases for future versions and read each version's notes before updating.
