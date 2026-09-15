# Installing RelayDesk

[← Documentation](README.md)

**The first public release is still being qualified. There is no public DMG download yet.** This guide describes the intended installation journey; the complete first-launch test remains pending in an isolated macOS environment.

## Requirements

The universal candidate targets macOS 12 or later, with Apple Silicon and Intel executables. A deployment target is not a claim that every supported OS version or Mac has been tested. The release notes will state the actual qualification coverage.

SSH and file transfers use the system's OpenSSH tools. A remote account and access to the corresponding server are needed for SSH/SFTP. Core terminal and SSH workflows do not require a cloud account. The main application interface is currently in French.

## When the release is available

1. Visit the official [GitHub Releases](https://github.com/NicoPFr/RelayDesk/releases) page.
2. Read the version's known limitations and download its RelayDesk DMG. The repository's ZIP archive is documentation, not the application.
3. Compare the downloaded file's SHA-256 with the checksum in those release notes, if you want to verify that the download matches the published file.
4. Open the DMG and drag **RelayDesk** to **Applications**.
5. Open RelayDesk from Applications and follow macOS's security guidance.

## Signing and macOS security

The first release is planned without Developer ID signing and without notarization. It may carry an ad-hoc signature for bundle integrity; that is not an Apple-issued developer identity or an Apple malware review.

macOS may warn that the developer cannot be verified or that Apple cannot check the app for malicious software, and may prevent it from opening. Behavior can also depend on device-management policies. Read [Apple's guidance on safely opening apps](https://support.apple.com/102445). Do not disable system protections or remove quarantine metadata to follow this guide.

If macOS prevents launch, report the exact message and your macOS version through [GitHub Issues](https://github.com/NicoPFr/RelayDesk/issues/new?template=installation_problem.md). Avoid repeated launch attempts or changes to security settings just to make the application run.

## First launch and updates

A fresh user environment should not inherit the developer's hosts, sessions, or workspaces. RelayDesk can discover your own existing OpenSSH configuration on your Mac; those are your connections, not bundled sample or developer data.

A public update channel is not configured for this candidate. Check the GitHub Releases page for future versions. No automatic-update guarantee is made.
