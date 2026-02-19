# SpellcastingImprovements

**Version:** 1.1.1  
**Author:** the-xorcist  
**Release Date:** February 19, 2026

## Description

A quality-of-life mod for Erenshor that enhances the spellcasting system with fixes for spell stacking, buff management, movement speed mechanics, spellbook management, and crowd control mechanics.

## Features

- **DoT Break Fix** - Prevents damage-over-time (DoT) effects from triggering the 20% chance to break crowd control effects like roots and mezzes
- **Resist Break Notifications** - Displays chat messages when targets break free from CC effects due to resist checks
- **Spell Stacking Fix** - Automatically removes lower-level spells when casting higher-level versions on the same spell line
- **Click-Off Buffs** - Click on buff icons to remove beneficial spells from yourself
- **Spellbook Management** - Right-click spells to move/swap them in your spellbook, plus a delete button to remove unwanted spells
- **Backward Speed Cap Fix** - Allows movement speed buffs to increase backward movement speed (configurable percentage)

## Installation

1. Install [BepInEx](https://docs.bepinex.dev/articles/user_guide/installation/index.html) for Erenshor
2. Copy `SpellcastingImprovements.dll` to your `BepInEx/plugins` folder
3. Launch the game
4. (Optional) Copy `the-xorcist.spellcastingimprovements.cfg` to your `BepInEx/config` folder for preset defaults

## Configuration

All options can be configured in `BepInEx/config/the-xorcist.spellcastingimprovements.cfg`:

| Option | Default | Description |
|--------|---------|-------------|
| BackwardSpeedBuffPercent | 50 | Percentage of movement buff applied to backward speed cap (0-100) |

## Changelog

### v1.1.1 - February 19, 2026
- Initial release

## Source Code

Source code is included in the `-source.zip` archive.
