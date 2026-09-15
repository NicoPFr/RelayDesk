# Local data and privacy

[← Documentation](README.md)

RelayDesk uses local application state to remember connections, preferences, and workspaces. This page describes the current implementation; it does not make a blanket claim that all activity stays offline.

## Data on your Mac

RelayDesk's application data directory is `~/Library/Application Support/RelayDesk`. Depending on the features you use, it contains connection profiles, settings, host organization, saved commands, command history, and terminal transcripts. Interface preferences and session-restoration state also use the application's WebKit storage.

The app reads the OpenSSH configuration and authentication mechanisms selected on your Mac. SSH identities and an optional PKCS#11 provider are runtime configuration; they must not be included in the distributed application. Temporary local copies may be created when you edit or transfer remote files.

Saved commands, transcripts, hostnames, and paths can contain sensitive information even when they are not credentials. Consider the contents before enabling logging or sharing files.

## Network activity

SSH and SFTP connect to the hosts you select. Opening a link or an external editor can involve another application. Update checks require a configured update channel, which is not enabled in 2.11.0. These facts should not be interpreted as a guarantee about every network action made by your shell, remote command, editor, or SSH configuration.

## Reporting a problem

GitHub Issues and their attachments are public. Share the smallest useful excerpt and remove passwords, keys, tokens, real hostnames, addresses, private paths, and operational command output. Do not upload your complete configuration, application data directory, or SSH directory.

The release package must contain application resources and legal notices only, with no developer or user profiles, workspaces, logs, transcripts, or credentials. Artifact inspection and an isolated first-launch test are separate parts of release qualification.
