# Release distribution

Official public builds are attached to this repository's GitHub Releases.

Each release should include:

- A versioned ZIP whose top level contains `manifest.json`.
- Release notes describing user-visible changes and known issues.
- A SHA-256 checksum for the ZIP.
- Clear identification of pre-release builds.

## Manual installation

1. Download and extract the ZIP from the desired release.
2. Open `chrome://extensions`.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder containing `manifest.json`.

Manual installations do not automatically receive updates from the Chrome Web Store. Return to the Releases page for updates, and replace the previously extracted build after reviewing the new release notes.
