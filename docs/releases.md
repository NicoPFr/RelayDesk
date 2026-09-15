# Release status

[← Documentation](README.md)

**The first public release is being prepared. There is no application download yet.**

[GitHub Releases](https://github.com/NicoPFr/RelayDesk/releases) will be the official download channel and the public changelog. Each release will include installation instructions, known limitations, and a SHA-256 checksum for its DMG.

## First candidate: 2.11.0

The candidate brings together local terminals, SSH, SFTP/SCP, tabs and split views, host organization, saved workspaces, and command tools in a universal macOS application for Apple Silicon and Intel.

The application and DMG have been built. Package inspection and automated tests have been performed; a clean first launch, representative native workflows, and relaunch still need verification in an independent macOS environment. Real product screenshots will be captured there using sample data. The candidate will be published only after that qualification.

## Distribution details

- The package targets macOS 12 or later. Compatibility testing across macOS versions and Intel hardware is still pending.
- The first release uses an **ad-hoc signature**, with **no Developer ID signing and no notarization**. macOS may block its first launch. See the [installation guide](installation.md).
- The interface is primarily in French.
- A public update channel is not configured; downloads will use GitHub Releases.
- Hardware PKCS#11 authentication and advanced tmux/TUI workflows need further field qualification.

Developer ID signing and notarization are future distribution improvements. The remaining first-release qualification concerns the installed application's behavior and a clean first-run experience.

Follow [release preparation](https://github.com/NicoPFr/RelayDesk/issues/2) for public progress. Published release notes will describe changes actually included in each version, separately from the roadmap.
