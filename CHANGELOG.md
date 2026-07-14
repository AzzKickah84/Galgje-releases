# Galgje Changelog

All notable changes to Galgje are documented here.

## v20.1.3.20260714180843 — July 14, 2026

### Data locations (Settings)
- New **Settings → Data locations** tab to manage where game data is stored
- Custom local or network folder (`\\server\share\Galgje`) for stats, logs, history, and backups
- Test read/write access, copy or move existing data with optional ZIP backup
- Startup warning when configured network folder is unavailable
- App settings (language, shortcuts) always stay on this PC; restart required after path change

### Stats Audit
- Audit logging now records manual edits, game-end updates, imports, and reconcile operations
- Fixed empty audit list (old stats captured before save; game-end and import sources wired)
- Filter by player, source type, and date range; improved tab layout

### UI & layout
- Fixed clipping and overlapping controls across Settings, Player Manager, Game Rules, Stats Health, Word Browser, and Live Stats dialogs
- Responsive toolbars and filter rows on narrow window widths

### Offline manual
- User manual updated with screenshots
- Shareable offline ZIP package (`Galgje-Manual-offline-v*.zip`) for distribution without internet

---

## v20.1.2.20260714035621 — July 14, 2026

### Game elapsed time
- Subtle **game elapsed time** counter on the main window (above copyright, no overlap)
- Same elapsed time on Live Stats board, Word Progress window, and winner/dashboard screenshots
- Includes time from resumed games (cumulative, not reset on resume)

---

## v20.1.1 — July 14, 2026

### Word Browser
- New **Played words only** filter to browse words you have already played
- Improved formatting of online word meanings (clearer line breaks and sections)

---

## v20.1.0 — July 14, 2026

### Word Browser
- Online word meanings are now easier to read (line breaks, section headers)
- Definitions from Wiktionary, Van Dale, and dictionary APIs

### GitHub releases
- Cumulative download counter on release pages (never resets on new versions)
- Each release includes installer, manual, press release, and changelog

### Statistics (from v20.0.19)
- Stats Audit tab, authoritative manual stat edits
- Stats Health and Compare Stats ignore options

### Installer
- Keep, back up, or delete existing game data during setup
- Local-time version timestamps
- Shareware license and setup changelog

---

## v20.0.19 — July 14, 2026

### Word Browser
- Online word meanings now work reliably (Wiktionary, Van Dale, dictionary fallbacks)
- Dutch and English definitions shown as plain text in the Word Analysis panel
- Filter text boxes debounced so browsing large word lists stays responsive
- Word Browser available in Player Manager and Tools menu

### Statistics
- Stats Audit tab shows a permanent log of all stat changes
- Manual stat edits are authoritative and never auto-reverted
- Stats Health Center: ignore specific issues
- Compare Stats: ignore button fixed for selected differences

### Installer & versioning
- Build timestamps now use local time (not UTC)
- Installer asks to keep, back up, or delete existing game data
- Shareware license and changelog shown during setup
- Custom `galgje.ico` used throughout app and installer

### Other
- Hall of Fame: player names more prominent on achievement badges
- Network play compatibility based on sequential release numbers
- Sample players created on first launch when no statistics exist

---

## v20.0 series

- Version numbering with build timestamps and internal release numbers for network compatibility
- GameEngine and unit tests for core game logic
- GameLogger and diagnostic log file support
- Stats sets, Player Manager, achievements, and network play
- Data stored in `%LocalAppData%\Galgje` (preserved across upgrades)
- Automatic daily ZIP backups (last 7 days kept)

---

Copyright © 2026 Thijs Boekholt. All rights reserved.
