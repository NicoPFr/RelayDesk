<p align="center">
  <img src="assets/brand/relaydesk-icon.png" alt="RelayDesk app icon" width="96" height="96">
</p>

# RelayDesk

**A native macOS terminal and SSH client — fast, elegant, and built for a modern developer workflow.**

Local terminals, remote servers, and files. One place to work.

**macOS · Free to use · Proprietary software**

[Explore the features](#features) · [Download status](#download) · [Documentation](docs/README.md) · [Get help](#support)

<!-- HERO: Embed assets/screenshots/relaydesk-overview.png only after an authentic,
privacy-reviewed application capture has been added. Do not use a mock interface. -->

## Keep your work in context

Connect to a server, inspect a file, run a command, and move to the next session. RelayDesk keeps the terminal and remote files together so you can spend less time switching between tools.

It is built for developers, system administrators, and anyone who works with several SSH hosts from a Mac. Familiar shortcuts, Finder drag and drop, and an interface that follows the system appearance make the workspace feel at home on macOS.

This repository is RelayDesk's official home for product information, documentation, feedback, and future releases. Application source code is not distributed here.

## Features

The following capabilities exist in the current application. **Public downloads are not available yet.**

| | Your workflow |
| --- | --- |
| **Terminal, local or remote** | Open a shell on your Mac or connect over SSH using your OpenSSH configuration, keys, and agent. Search terminal output and adjust its font and theme. |
| **Room for multiple sessions** | Work in tabs or split views. Name and organize sessions, then save a workspace to return to it later. |
| **Files beside the terminal** | Browse remote files over SFTP, upload and download with SFTP or SCP, follow queued transfers, and open remote files in an external editor. |
| **Connections in order** | Group hosts into folders, mark favorites, and search your connections. |
| **Fewer repeated steps** | Find actions in the command palette, reuse saved commands and session history, and send input to explicitly selected sessions. |

### A few principles behind the product

**The terminal comes first.** Give active sessions room to breathe; keep secondary controls close when you need them.

**Your existing SSH setup belongs here.** Work with the configuration and identities you already use. Core terminal and SSH workflows do not require a cloud account.

**Control stays with you.** Choose the targets for shared input, review sensitive pastes, and keep remote files attached to the session you are working in.

## See RelayDesk in action

Authentic application screenshots are being prepared. They will show the current interface and real terminal and file operations using non-sensitive sample data.

<!-- DEMO: Once reviewed, embed the real GIF here and link the MP4 and transcript.
Media preparation and publication criteria: assets/demo/README.md. -->

## Download

**The first public release is coming soon.**

RelayDesk will be distributed through [GitHub Releases](https://github.com/NicoPFr/RelayDesk/releases). The first release candidate is being qualified; there is no public application download yet.

The first release is planned **without Developer ID signing and without notarization**. An ad-hoc signature does not identify the developer to Apple, and macOS may block the first launch. See the [installation guide](docs/installation.md) for the intended download path and security information.

GitHub's **Code → Download ZIP** downloads this documentation repository, not the application.

## Requirements and current limitations

- **macOS:** the universal release candidate targets macOS 12 or later on Apple Silicon and Intel. Compatibility qualification is still in progress.
- **Language:** the main interface is currently in French; broader localization is planned.
- **Distribution:** Developer ID signing and notarization are deferred. A public update channel is not configured.
- **Advanced environments:** hardware PKCS#11 tokens and complex tmux/TUI workflows still need further field qualification.

## Documentation

[Installation](docs/installation.md) · [First steps](docs/first-steps.md) · [Local data and privacy](docs/privacy.md) · [Release status](docs/releases.md)

The [documentation overview](docs/README.md) is the starting point for using RelayDesk and reporting a problem.

## Roadmap

| Stage | Focus |
| --- | --- |
| **Available** | Local terminals, SSH, SFTP/SCP, tabs and splits, host organization, saved workspaces, and everyday command tools in the current application. |
| **In development** | Qualification of the first universal macOS release, installation journey, and real product media. |
| **Planned** | Developer ID signing and notarization, and broader interface localization. |
| **Future** | Terminal folding and outlining to make long output easier to navigate. |

These are directions, without fixed dates. Planned features are not promises for the first public release.

## Support

[Search existing issues](https://github.com/NicoPFr/RelayDesk/issues) or open one of the following:

- [Bug report](https://github.com/NicoPFr/RelayDesk/issues/new?template=bug_report.md) — what happened, your versions, and how to reproduce it.
- [Installation problem](https://github.com/NicoPFr/RelayDesk/issues/new?template=installation_problem.md) — macOS version, processor, and the exact message you see.
- [Feature request](https://github.com/NicoPFr/RelayDesk/issues/new?template=feature_request.md) — the workflow you want to improve and why.
- [Question](https://github.com/NicoPFr/RelayDesk/issues/new?labels=question&title=Question%3A%20) — help understanding RelayDesk or its availability.

English and French are welcome. Issues are public: remove credentials, private hostnames, and sensitive content from logs and screenshots.

## Support RelayDesk

**RelayDesk is free to use and developed independently.**

Sponsorships help support ongoing development, maintenance, bug fixes and new features. Supporting the project is optional and helps keep it sustainable over time.

GitHub Sponsors is not active yet. A verified sponsorship link will be added here when it is available.

<!-- Add the verified GitHub Sponsors link and .github/FUNDING.yml only after activation. -->

## License

RelayDesk is **proprietary software**, free to use for personal or professional purposes under the [RelayDesk license](LICENSE). Redistribution, modification, and derivative works require permission except where the license or applicable law permits them.

Bundled third-party components retain their own licenses; see [third-party notices](THIRD_PARTY_NOTICES.txt).

Copyright © 2026 Nicolas Peeters. All rights reserved.
