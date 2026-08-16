# H.A.L.O. Agent OS — releases

Distribution channel for the [H.A.L.O. Agent OS](https://haloagent.tech) desktop
app. This repository holds **build artifacts and the auto-update feed only** —
no source. `electron-updater` in the shipped app reads its releases from here,
which is why it is public: update checks are unauthenticated.

Downloads are on the [Releases](../../releases) page.

The desktop app is a thin client. It loads `https://haloagent.tech` and keeps the
native pieces — tray, notifications, dictation, auto-update — so desktop and
mobile are the same session rather than two copies of one that drift.

Issues and source live in the main repository, not here.
