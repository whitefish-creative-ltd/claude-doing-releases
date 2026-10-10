<p align="center">
  <a href="https://claudedoing.whitefishcreative.co.uk/"><strong>Claude Doing?</strong></a><br>
  What is Claude doing on your Mac?
</p>

This repository holds the **releases** of Claude Doing?, an activity monitor for Claude by WhiteFish Creative Limited. The source code isn't here.

- **Download:** [claudedoing.whitefishcreative.co.uk](https://claudedoing.whitefishcreative.co.uk/), or the `.dmg` on the [latest release](https://github.com/whitefish-creative-ltd/claude-doing-releases/releases/latest).
- **Updates:** the app checks the latest release's `updates.json` once a day. It's signed by WhiteFish Creative, and the app installs an update only if the signature, the download's SHA-256 and the app's Developer ID signature all check out.

Each release has:

| File | What it is |
| --- | --- |
| `Claude-Doing-<version>.dmg` | The app, signed and notarised by Apple. Open it and drag the app to Applications. |
| `Claude-Doing-<version>.zip` | The same app, for the in-app updater. |
| `updates.json` | The signed update information the app reads. |

Requires macOS 26 or later. Not made by or affiliated with Anthropic.

© WhiteFish Creative Limited · [whitefishcreative.co.uk](https://whitefishcreative.co.uk/)
