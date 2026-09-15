# RelayDesk demonstration

A real recording has not been published. The shared macOS desktop is currently in use, so desktop recording is paused. The missing prerequisite is an idle macOS session approved for capture, or a separate Mac with RelayDesk and a non-sensitive SSH/SFTP demo environment.

## Short recording plan

Aim for a focused 20–40 second walkthrough:

1. Show the actual RelayDesk window opening with demo profiles.
2. Open a local terminal and execute a short command.
3. Connect to a real demo SSH host and inspect a sample file.
4. Open its SFTP browser and transfer a sample file.
5. End with the terminal and remote files visible together.

Avoid unrelated windows, credentials, private hostnames, and production sessions. Use the actual application interface, without generated frames, simulated interactions, or invented command output. Preserve enough time for viewers to read each step.

## Publication

Save the reviewed recording here as `relaydesk-workflow.mp4`, encoded as H.264. Prepare a small GIF excerpt as `relaydesk-workflow.gif` for inline GitHub README playback, and a text transcript describing the actions. Keep the still overview available for readers who prefer not to view animation.

Only after the files exist and have been reviewed, replace the README's media preparation notice with the GIF, a link to the full video, and the transcript. Verify playback and readability on GitHub. No placeholder video or broken media link should be published.

## Social preview

The repository's custom social preview is configured on GitHub using [the dedicated image](../brand/relaydesk-social-preview.png). It uses the actual RelayDesk icon and product typography at 1280 × 640 pixels; it does not depict a simulated application interface.

A later revision may include an approved application screenshot. Adding an image to Git alone does not configure GitHub's preview; any replacement must also be uploaded in **Settings → General → Social preview** and checked on the repository.
