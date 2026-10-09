# First steps

[← Documentation](README.md)

These workflows describe RelayDesk 2.11.0. Start with the [installation guide](installation.md).
Interface labels below match the current French interface.

## Open a local terminal

Choose **Ouvrir un terminal local** on the empty workspace, or use **⌘T**.
Commands run on your Mac; no SSH server or token is needed for this local session.
Standard **⌘C** and **⌘V** copy and paste; **Ctrl+C** interrupts a shell process.

If a PKCS#11 library is already installed on the Mac, this version can detect it
automatically and show **Token absent**. That message does not prevent opening
a local terminal. If your SSH connections do not use a token, open
**Options → Paramètres** and turn off **Utiliser un token PKCS#11**. Do not
change your authentication settings if your remote environment requires one.

Use a harmless command such as `pwd` to check where you are before working with files.

## Connect over SSH

Your existing OpenSSH aliases can appear in **Connexions**. To create a profile,
open **Options** and choose **Ajouter un hôte…**. Enter the host, account and
port for a server you are authorized to use, then save it.

Double-click a host to connect. Authentication follows the profile and your SSH
setup. Read any connection error before retrying. For an initial test, use a
non-production host and sample files, never a production credential in a screenshot.

## Work with remote files

Open the **SFTP** pane for the active SSH session. **Distant** shows remote files;
**Local** shows files on your Mac; **Transferts** shows transfer operations.

Navigate to the intended directory before uploading or downloading. Use the
file's context menu for available actions. Check the source, destination and
any replacement confirmation before continuing.

## Keep sessions organized

Use tabs to switch sessions and the terminal layout control to show multiple
terminals. Folders and favorites organize connections; named workspaces keep
configurations together for later use. They are not a backup of running processes.

**⇧⌘P** opens the command palette. Shared input is optional: select its intended
target sessions deliberately, especially when a command could change several hosts.

## Ask for help

Note the app version, macOS version, operation and result, then use the
[bug report template](https://github.com/NicoPFr/RelayDesk/issues/new?template=bug_report.md).
Issues and attachments are public: remove credentials, private hosts, paths
and operational output before sharing.
