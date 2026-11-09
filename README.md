# Cardapter

Ref: CDP-WEB-001-R1

Cardapter plays real Atari 2600 cartridges on a Commodore 64 / Ultimate 64. It finally builds the 1983 "Cardapter 1" adapter, which was advertised but never shipped.

The project page is `index.html`.

## Contents
- **Emulator** — an Atari 2600 emulator written in 6510 assembly (ACME), with Python test tools
- **C64 cartridge reader** — hardware that reads a 2600 cartridge's ROM through the C64 expansion port
- **Enclosure** — a reshaped Commodore 1750 REU shell (v40)
- **Prototyping rig case** — a case for the TexElec protoboard bench rig (v0.9.18)
- **VIC-20 board** — a board with socketed real Atari chips (Rev 2.1 planned)

## Publishing with GitHub Pages
1. Create a repository and add `index.html` and this README at the root.
2. Go to **Settings → Pages → Build and deployment**, set the source to *Deploy from a branch*, and choose `main` / `(root)`.
3. The site goes live at `https://<username>.github.io/<repo>/`.
