# Security policy

## Report a vulnerability privately

For a vulnerability affecting RelayDesk or its distribution, use
[Report a vulnerability](https://github.com/NicoPFr/RelayDesk/security/advisories/new).
Private vulnerability reporting is enabled for this repository.

Do not disclose vulnerabilities, credentials or production data in public
issues, pull requests or discussions. Provide the affected version and download
source, macOS version and architecture, impact, and minimal reproduction steps
on an environment you are authorized to test. Redact hostnames, credentials,
personal information and sensitive paths. Do not attach complete terminal logs
or workspace exports.

## Versions and response

Reports concerning the latest published release are investigated first according
to their impact. Prereleases are experimental; earlier or modified builds are
assessed case by case. There is no LTS commitment, guaranteed response time,
guaranteed backport or bug bounty.

The maintainer, [@NicoPFr](https://github.com/NicoPFr), assesses the report and
coordinates remediation and disclosure with the reporter. Public attribution
requires the reporter's consent. Revoke any exposed credentials immediately;
deleting a file or message does not make a leaked secret safe again.

## Scope and limitations

This public repository contains distribution information and documentation,
not the application's private source code. Repository scanners do not certify
the distributed application or replace independent security review.
Install only artifacts from the official releases and follow their stated
signing and compatibility limitations. RelayDesk runs local and remote commands
with the connected user's permissions; it is not a sandbox.
