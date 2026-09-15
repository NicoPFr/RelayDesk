# Releases

[← Documentation](README.md)

## RelayDesk 2.11.0

[Release notes and download](https://github.com/NicoPFr/RelayDesk/releases/tag/v2.11.0)

The first public release brings local terminals, SSH, SFTP/SCP, tabs and split views, host organization, saved workspaces, and command tools to a universal macOS application.

- **Asset:** `RelayDesk.dmg`, containing Apple Silicon and Intel executables.
- **Minimum target:** macOS 12. Broader OS and hardware compatibility testing remains pending.
- **Signing:** ad hoc; no Developer ID signature and no notarization.
- **Launch verification:** the maintainer confirmed this exact DMG launches and works on macOS. Independent clean-user, persistence/relaunch, and complete compatibility testing are not claimed.
- **Limitations:** primarily French interface; no configured public in-app update channel; further tmux/TUI and hardware PKCS#11 field qualification needed.

SHA-256:

```text
9f6fc6867305eb60f593b270c1c3713711cd277a55cfbb1cddd8e4ae7252c6c9
```

## Download convention

[Latest release](https://github.com/NicoPFr/RelayDesk/releases/latest) · [Download latest DMG](https://github.com/NicoPFr/RelayDesk/releases/latest/download/RelayDesk.dmg) · [All releases](https://github.com/NicoPFr/RelayDesk/releases)

Every release uses the stable asset name `RelayDesk.dmg`, while its version is recorded in the tag, release notes, and application metadata. This keeps the README's main download link unchanged between releases. Links under a specific tag continue to identify that version. Never silently replace a published artifact; publish a new version when its contents change.

Future release notes will describe actual changes, compatibility coverage, signing status, installation details, and the checksum of the published DMG. See [GitHub's release-link documentation](https://docs.github.com/en/repositories/releasing-projects-on-github/linking-to-releases).
