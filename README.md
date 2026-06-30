# Maodie

Maodie is a custom Codex pet inspired by the Chinese internet rescue cat known as "Yuantou Maodie": a round-headed orange tabby with airplane ears, hissing energy, and compact meme-cat body language.

This folder is arranged as a small GitHub-ready project for sharing or archiving the pet.

![Maodie contact sheet](docs/contact-sheet.png)

## Project Contents

- `pets/maodie/pet.json`: Codex pet manifest.
- `pets/maodie/spritesheet.webp`: Codex-compatible sprite atlas.
- `docs/INSTALL.md`: setup instructions.
- `docs/ASSET_MANIFEST.md`: build artifact notes.
- `docs/contact-sheet.png`: visual QA sheet.
- `docs/previews/*.gif`: per-state animation previews.

## Current Status

The completed pet has been generated and installed locally at:

`/Users/wyx/.codex/pets/maodie/`

This GitHub project folder is self-contained. The final build artifacts are also available at:

`/Users/wyx/Documents/codex_pets/maodie-run/`

## Pet States

Maodie includes the full Codex pet animation set:

| State | Preview |
| --- | --- |
| idle | ![idle](docs/previews/idle.gif) |
| running-right | ![running-right](docs/previews/running-right.gif) |
| running-left | ![running-left](docs/previews/running-left.gif) |
| waving | ![waving](docs/previews/waving.gif) |
| jumping | ![jumping](docs/previews/jumping.gif) |
| failed | ![failed](docs/previews/failed.gif) |
| waiting | ![waiting](docs/previews/waiting.gif) |
| running | ![running](docs/previews/running.gif) |
| review | ![review](docs/previews/review.gif) |

## Notes

The final accepted version keeps the rows the user liked, and specifically repairs the left/right movement and failed-state rows so they match the round orange Maodie identity.

No Git commands are required to use this folder locally. If you publish it, create a repository through your preferred GitHub workflow.
