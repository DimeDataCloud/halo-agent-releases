<h1 align="center">H.A.L.O. Agent OS Releases</h1>

<p align="center">Installers and the auto-update feed for the H.A.L.O. Agent OS desktop app.</p>

## What this is

This repository holds build artifacts and the auto-update feed only. It contains no source code.

The desktop app uses `electron-updater`, which reads its release metadata from this repository. The repository is public so that update checks work without authentication.

The desktop app is **HALO Local**: the full agent harness running on your own computer, with your own engines and keys. Connecting it to a hosted workspace at [haloagent.tech](https://haloagent.tech) is an optional setting.

## Who it is for

- Users who want to install H.A.L.O. Agent OS on Windows.
- Anyone checking which version is current or where the update feed points.

## Installing

1. Open the [Releases](../../releases) page.
2. Download the installer for the version you want.
3. Run it. Windows installers are currently unsigned, so SmartScreen will warn on first run. Choose "More info" and then "Run anyway" only if you trust the download source.

## Update feed

Installed copies of the app check this repository for newer releases and download them from the Releases page. Nothing else in this repository is read by the app.

## Repository layout

```
.
├── LICENSE    Terms for the installers and update files
└── README.md  This file
```

## Source and issues

The application source is not published here. It is kept in a private repository.

## Status

Windows installers are currently unsigned.

## License

Copyright (c) 2026 Dime Data. All rights reserved. See [LICENSE](LICENSE). The installers and update files are licensed for use of the application only. No licence is granted to copy, modify, redistribute or reverse engineer them without written permission from the copyright holder.
