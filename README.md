# MBB Continuum

MBB Continuum keeps your World of Warcraft minimap tidy by collecting compatible addon buttons into one compact, expandable menu. It continues the MinimapButtonBag lineage with current Retail compatibility and maintenance.

## Features

- Collects compatible addon minimap buttons into a single button bag.
- Expands in a configurable primary and alternate direction.
- Supports a configurable collapse timeout and maximum buttons per row or column.
- Lets you attach the MBB button to the minimap edge or place it elsewhere on the screen.
- Lets you exclude individual buttons from the bag.
- Stores settings and exclusions per character.
- Includes English, French, German, Korean, Russian, Simplified Chinese, and Traditional Chinese localization.
- Requires no external libraries.

## Compatibility

MBB Continuum 4.0.31 targets World of Warcraft Retail 12.1 (`Interface: 120100`). Classic compatibility is not claimed.

The addon intentionally keeps the internal addon folder and saved-variable names as `MBB`. Replacing an older MBB installation should therefore preserve compatible per-character settings. Do not install multiple MBB forks side by side; remove the old folder first, then install this version as `Interface/AddOns/MBB`.

## Usage

- Left-click the MBB button to show or hide collected buttons.
- Right-click the MBB button to open its options.
- Ctrl + Right-click the MBB button to detach it from or reattach it to the minimap.
- Ctrl + Right-click a collected button to return it to the minimap.

### Slash commands

- `/mbb` — show command help.
- `/mbb buttons` — list the frames currently stored in the MBB bar.
- `/mbb reset position` — reset the MBB button position.
- `/mbb reset all` — reset all MBB settings and exclusions.

The legacy aliases `/minimapbuttonbag` and `/mmbb` remain available.

## Installation

For a manual installation, download a packaged release and extract it into your World of Warcraft `_retail_/Interface/AddOns` directory. The final path must be `_retail_/Interface/AddOns/MBB/MBB.toc`.

Release archives contain only the files required to run the addon, plus its license and generated changelog. Development files are available in the source repository instead of the in-game package.

## Project lineage and credits

MBB Continuum is an independently maintained continuation of MinimapButtonBag and MinimapButtonBag Reborn. Credit for the original addon and its earlier maintenance goes to karlsnyder, vallantv, skunfly, and contributor CosmicCleric. Additional historical contributions are credited in the source history, including Tunhadil, Pericles, and yossa.

Current maintenance is by Zane. View the [source code](https://github.com/xrellana/MBB) or [report an issue](https://github.com/xrellana/MBB/issues) on GitHub.

## License

MBB Continuum is released into the public domain under the [Unlicense](LICENSE).
