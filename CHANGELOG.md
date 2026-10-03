# Changelog

## [v0.0.4]

### Added

- GB mode: palette **GBC** (index 0) — per-game colorization from the GBC
  boot ROM tables

### Changed

- SDK update
- Allow to cancel game caching

### Fixed

- Autofire now working as expected

### Install

**Core**

- Download `tgbdual-vx.x.x.zip` from the GitHub release and unzip it onto the
  SD card root (it places `cores/tgbdual.bin`).
- Put ROMs under `/roms/gb/` (`.gb`) and `/roms/gbc/` (`.gbc`).
- Optional boot ROMs: `/bios/gb/gb_bios.bin`, `/bios/gb/gbc_bios.bin`.
- Optional cheats: `.ggcodes` in /cheats/gb or /cheats/gbc.
- Requires firmware whose ABI matches `SDK_VERSION` in this repository.
