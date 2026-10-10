# Changelog

## [v0.0.5]

### Added

- Nothing.

### Changed

- Default palette is not GBC palette anymore.

### Fixed

- SGB: colorize sprites from the ATTR map (like real hardware / mGBA), not
  a fixed palette 1 — fixes inverted/wrong OBJ colors in Donkey Kong ’94

### Install

**Core**

- Download `tgbdual-vx.x.x.zip` from the GitHub release and unzip it onto the
  SD card root (it places `cores/tgbdual.bin`).
- Put ROMs under `/roms/gb/` (`.gb`) and `/roms/gbc/` (`.gbc`).
- Optional boot ROMs: `/bios/gb/gb_bios.bin`, `/bios/gb/gbc_bios.bin`.
- Optional cheats: `.ggcodes` in /cheats/gb or /cheats/gbc.
- Requires firmware whose ABI matches `SDK_VERSION` in this repository.
