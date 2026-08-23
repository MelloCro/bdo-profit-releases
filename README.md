# BDO Artisan — releases

Download the latest build from the [Releases](../../releases) page.

| File | Use |
|---|---|
| `BDO-Artisan-Setup-<version>.exe` | Installer, with Start-menu and desktop shortcuts |
| `BDO-Artisan-portable-<version>.exe` | Single file, no install |

The app updates itself: it checks this repo on launch, and the header has a
**Check for updates** button — it tells you when a new version exists, and you
decide whether to download it.

Builds are unsigned, so Windows SmartScreen warns on first run — *More info →
Run anyway*.

---

This repository holds **only the built binaries**. It exists separately from the
(private) source so the auto-updater can read releases without shipping a GitHub
token inside the application.
