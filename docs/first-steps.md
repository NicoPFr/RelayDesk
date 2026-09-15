# First steps

[← Documentation](README.md)

These workflows describe RelayDesk 2.11.0. Start with the [installation guide](installation.md). Interface labels below match the current French interface.

## Open a local terminal

Choose **Ouvrir un terminal local** on the empty workspace, or use **⌘T**. Commands run on your Mac. Standard **⌘C** and **⌘V** copy and paste; **Ctrl+C** is sent to the shell to interrupt a process.

Use a harmless command such as `pwd` to check where you are before working with files.

## Connect over SSH

Your existing OpenSSH aliases can appear in **Connexions**. To create a profile, open the **•••** menu and choose the action to add a host. Enter the host, account, and port for a server you are authorized to use, then save it.

Double-click a host to connect. Authentication follows the profile and your SSH setup. A session's status remains visible in the workspace; read any error before retrying.

For an initial test, use a non-production host and sample files. Never enter a real credential into a public issue or screenshot.

## Work with remote files

Open the **SFTP** pane for the active SSH session. **Distant** shows remote files; **Local** shows files on your Mac; **Transferts** shows queued transfer operations.

Navigate to the intended directory before uploading or downloading. Use the file's context menu for the available actions. Check the source, destination, and any replacement confirmation before continuing.

## Keep sessions organized

Use tabs to switch between sessions and the terminal layout control to show multiple terminals. Folders and favorites help organize connections; named workspaces keep a set of sessions together for later use.

**⇧⌘P** opens the command palette. Shared input is optional: select the intended target sessions before enabling it, especially when commands could change more than one host.

## Ask for help

If a workflow fails, note the app version, macOS version, the operation, and what happened. Use the [bug report template](https://github.com/NicoPFr/RelayDesk/issues/new?template=bug_report.md), and remove private information from any attachments.
