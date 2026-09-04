# H.A.L.O. Agent OS — releases

Distribution channel for the [H.A.L.O. Agent OS](https://haloagent.tech) desktop
app. This repository holds **build artifacts and the auto-update feed only** —
no source. `electron-updater` in the shipped app reads its releases from here,
which is why it is public: update checks are unauthenticated.

Downloads are on the [Releases](../../releases) page.

The desktop app is **HALO Local**: the full agent harness running on your own
computer with your own engines and keys, free. Connecting it to a hosted
workspace at haloagent.tech is a setting, not a requirement.

Windows installers are currently unsigned — SmartScreen warns on first run.

Issues and source live in the main repository, not here.
