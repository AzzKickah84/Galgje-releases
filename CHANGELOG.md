# Galgje Changelog

All notable changes to Galgje are documented here.

## v20.0.19.20260714020145 — July 14, 2026

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
