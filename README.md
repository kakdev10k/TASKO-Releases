# TASKO — Windows releases

Personal Windows workspace for Novel/Donghua video production, YouTube/Telegram
VIP publishing and daily tasks. Local SQLite storage; usable offline.

Download **Setup.exe** from the [latest release](https://github.com/kakdev10k/TASKO-Releases/releases/latest).
Windows x64. The installer is currently unsigned; Windows may show SmartScreen.

**v1.0.1 is the first published release and automatic-update baseline.** If using
an earlier local build, install v1.0.1 once. Later stable updates are checked and
downloaded automatically in the installed app. Open Settings → Update for status
or Restart & install. The app never forces a restart during work.

Keep `RELEASES` and `.nupkg` assets available: TASKO uses them to update. Ordinary
users only need Setup.exe. Checksums are in each release's `SHA256SUMS.txt`.

Your records stay in `%LOCALAPPDATA%\TASKO`; application code installs separately
under `TASKODesktop`. Uninstall keeps your data. Export a backup before changing
computers. Update checks need internet; ordinary task workflows do not.

This public repository contains distribution files and release notes only.
Source code is maintained privately. No GitHub token is bundled in the app.
