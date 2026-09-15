# Product screenshots to provide

No usable application screenshots were found in either repository or their available Git history. Existing images are branding assets only. Do not use browser test fixtures or mockups as product screenshots.

## Three priority captures from the Mac

| File | What to show | Proposed README caption |
| --- | --- | --- |
| `relaydesk-overview.png` | The full RelayDesk window, connection sidebar, several tabs, and a named workspace. Use sample host profiles only. | Your connections, sessions, and workspace in one macOS window. |
| `relaydesk-split-view.png` | Two or three actual terminals side by side: one local shell and real SSH sessions to a demo environment. Keep tabs and workspace controls visible. | Keep local tools and remote sessions side by side. |
| `relaydesk-sftp.png` | A connected demo SSH terminal beside the real SFTP browser, with harmless sample files and a completed sample transfer. | Work with remote files without leaving the active session. |

Optional fourth image: a real tmux layout, saved-workspace selector, or terminal-trigger editor if it adds something clearly visible and representative. Do not create a screenshot simply to complete a feature list.

## Capture quality

- Use the real 2.11.0 application on your Mac. Capture the application window at its native Retina resolution, ideally at least 2000 pixels wide; do not upscale.
- Keep the same appearance, window proportions, and readable terminal font across images.
- Use demonstration hosts and sample files only. Real SSH/SFTP operations must run against a demo environment; never stage fake output.
- Avoid menus or tooltips covering the workspace, unrelated windows, notifications, and the desktop.
- Check the sidebar, tab titles, prompt, paths, history, terminal output, and transfer list for personal or work data. Do not include passwords, keys, tokens, production hosts, or private usernames.
- Supply the three original PNGs with a short description of the workflow and confirmation that they show demonstration data. They can then be reviewed and embedded without inventing any content.

## Integration

Use the overview below the README hero, followed by split-view and SFTP captures beside their corresponding workflow sections. The current screenshot notice must be removed only when the real files exist. Use meaningful alt text and the captions above. A social-preview revision can incorporate the approved overview later.
