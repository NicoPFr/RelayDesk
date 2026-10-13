# Installing RelayDesk

[← Documentation](README.md)

## Download

[Try 2.11.1-rc.14 for macOS](https://github.com/NicoPFr/RelayDesk/releases/download/v2.11.1-rc.14/RelayDesk-2.11.1-rc.14.dmg) ·
[Release notes and checksum](https://github.com/NicoPFr/RelayDesk/releases/tag/v2.11.1-rc.14)

This is an **experimental prerelease**, not a stable update. It includes updated
dependencies and input fixes absent from 2.11.0. Its qualified workflows and
remaining compatibility limits are listed in the release notes. The GitHub
`latest` link still selects the earlier stable release, not this candidate.

The latest link follows the current public release. For a specific version,
use its release page. The DMG is a Release Asset; the repository ZIP contains
documentation, not the application.

## Requirements

RelayDesk 2.11.1-rc.14 contains Apple Silicon and Intel executables and targets
macOS 12 or later. This target does not mean every OS and hardware combination
has been tested. The interface is primarily French. A local terminal does not
need a token or a RelayDesk account; SSH requires access to a server and the
authentication appropriate to that server.

## Install

1. Download **RelayDesk-2.11.1-rc.14.dmg** from its official GitHub prerelease.
2. Compare its SHA-256 with the release notes. In Terminal, run `shasum -a 256`
   followed by the downloaded file's path.
3. Open the DMG and drag **RelayDesk** to **Applications**.
4. Open RelayDesk and follow macOS's security guidance.

## Signing and macOS security

This release is ad-hoc signed, **without Developer ID signing or notarization**.
Its signature checks bundle integrity; it is not an Apple-issued developer
identity or malware review. macOS and managed-device policies may block launch.
Read [Apple's guidance on safely opening apps](https://support.apple.com/102445).
This guide does not require disabling protections or removing quarantine metadata.

If launch is blocked, report the exact message and macOS version with the
[installation problem template](https://github.com/NicoPFr/RelayDesk/issues/new?template=installation_problem.md).

## What has been checked

### 2.11.1-rc.14

Local launch, exact native copy/paste followed immediately by Enter, synthetic
sensitive replies excluded from command history, loopback SSH/SFTP, restoration,
default terminal text/cursor and clear, and a native SFTP sample download have
been checked on the maintainer's Mac. The sample matched all 46 source bytes.
Bundle contents and checksum matched the audited package after qualification.
This is not an Intel execution, quarantined browser download or full VoiceOver
qualification. See the [versioned notes](releases/2.11.1-rc.14.md).

### Historical 2.11.0 checks

The public DMG's checksum, Universal executable and bundle integrity have been
checked. On 9 October 2026, an unmodified copy installed under an isolated
user Applications directory launched on macOS 27.0.1, Apple Silicon. A real
local shell executed a harmless command, and a saved command persisted across
relaunch. A separate empty application profile opened a local terminal without
a PIN, even when an installed PKCS#11 library was detected.

This used isolated HOME/application data on the existing Mac, not a newly
created macOS account. It did not test a browser-quarantined download,
Gatekeeper approval, the Finder drag gesture, Intel execution or every OS
version. Broader compatibility and remote-environment qualification remain pending.

## First launch and updates

The package contains no developer profiles or saved user state. RelayDesk can
discover your own OpenSSH configuration. See [first steps](first-steps.md) and
[local data and privacy](privacy.md) before changing settings or sharing logs.

A public in-app update channel is not configured. Use GitHub Releases for
future versions and read each version's notes before installing.
