# RelayDesk application screenshots

These images were captured from the unmodified public RelayDesk 2.11.0 macOS
application on Apple Silicon, using an isolated demonstration profile.
They are native window captures, not browser fixtures, mockups or AI-generated UI.
Original PNG dimensions are 2984 × 1670. No upscaling or retouching was applied.

| Image | Workflow |
| --- | --- |
| [Overview](relaydesk-overview.png) | One loopback SSH connection, a local terminal tab and the SFTP pane in the same window. |
| [Local and SSH split](relaydesk-split-local-ssh.png) | Two actual shells side by side: macOS local shell and SSH to a temporary localhost endpoint. |
| [SFTP](relaydesk-sftp.png) | Public macOS timezone files browsed through the SSH session's SFTP connection. A download through the app was verified against the source SHA-256. |

The endpoint is localhost, not a production system. The visible `demo` prompts
are deliberately configured shell prompts; they are not account or privilege
claims. Terminal results come from real commands. The sample timezone files
are public operating-system data; no private host, configuration or operational
output is included. The pictures do not prove compatibility with every remote
server, an execution-speed benchmark or support for future features.

The locomotive and social-preview images in `assets/brand` are branding, not
application screenshots. Refer to the release notes for package limitations.
