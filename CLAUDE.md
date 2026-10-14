# OmaPaper Dark — Omarchy theme

The dark sibling of OmaPaper. Read `~/.config/omarchy/themes/omapaper/CLAUDE.md` first: goal,
owner feedback history and all design rules live there and apply here too.

- Lives at `~/.config/omarchy/themes/omapaper-dark/` = repo `wstough/omarchy-omapaper-dark-theme`
  (shows as "Omapaper Dark"). Apply: `omarchy theme set omapaper-dark`.
- Wallpapers are BUILT FROM THE LIGHT REPO: `cd ../omapaper && tools/make-wallpapers.sh --dark`
  reads `tools/wallpapers-dark.list` and writes into this repo's `backgrounds/`. Sources live in
  the light repo's `tools/sources/`. The logo wallpaper is copied from `../omapaper/backgrounds/22-omarchy-ink.png`.
- Owner's rule for this set: similar kinds of images to the light set (people, city/architecture,
  sky, animals) but NONE of the same artworks, except the Omarchy logo, inverted.
  Prefer naturally dark images; light-ground prints use `-neg` styles (scratchboard look).
- Palette: bg `#1A1917`, bone `#E4DFD3`, accent light graphite `#A8A398`, code inks at ~7:1
  (`../omapaper/tools/check-palette.py colors.toml`).
