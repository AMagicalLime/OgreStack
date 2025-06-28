# OgreStack

A comprehensive stack size customization mod for RimWorld that allows you to modify stack sizes for various item categories and individual items.

## Features

- **Dynamic Stack Modification**: Stack changes don't require game reloads
- **Two Modes**: Scalar (multiplier) and Fixed (set value)
- **In-Game Settings Menu**: Easy-to-use interface for configuration
- **Preset Configurations**: Quick setup options
- **Individual Item Overrides**: Target specific items via XML
- **Multi-Version Support**: Works with RimWorld 1.1 through 1.6

## Installation

1. Subscribe to this mod in the Steam Workshop
2. Enable it in the RimWorld mod menu
3. Configure your stack sizes in-game via the mod settings

## Usage

### In-Game Settings
- Access settings via Mods → OgreStack
- Choose between Scalar (multiplier) and Fixed modes
- Adjust values for different item categories
- Use presets for quick configuration

### Default Settings
- **Small Volume Resources**: x30 (gold, uranium, etc.)
- **Resources**: 1000 (steel, wood, plasteel, etc.)
- **Raw Food**: 1000 (corn, rice, etc.)
- **Raw Meat**: 1000 (meat, eggs, etc.)
- **Raw Plants**: 2000 (smokeleaf leaves, etc.)
- **Meals**: 150 (fine meal, lavish meal, etc.)
- **Animal Food**: 2000 (kibble, hay, etc.)
- **Foods**: 1000 (pemmican, chocolate, etc.)
- **Items**: 20 (horns, mech serums, etc.)
- **Body Parts & Implants**: 5 (arms, bionics, etc.)
- **Textiles**: 1000 (cloth, wool, etc.)
- **Leather**: 1000 (leather)
- **Stone Blocks**: 2500 (granite, marble, etc.)
- **Manufactured**: x10 (components, wort, chemfuel, etc.)
- **Medicine**: 75 (herbal, glitter, etc.)
- **Drugs**: 4000 (smokeleaf joints, yayo, etc.)
- **Mortar Shells**: 25 (antigrain, high explosive, etc.)
- **Artifacts**: 10 (psychic lances, etc.)
- **Other Stackables**: x10 (other items that stack)

### Individual Item Overrides
Create an `Overrides.xml` file in your mod folder to set specific stack limits for individual items:

```xml
<?xml version="1.0" encoding="utf-8"?>
<OgreStackOverrides>
  <item defName="AIPersonaCore" stackLimit="1" />
  <item defName="TechprofSubpersonaCore" stackLimit="1" />
</OgreStackOverrides>
```

## Load Order
The mod attempts to run after initial processing is complete. If you experience issues, try moving OgreStack to the end of your load order.

## Compatibility
- **Vanilla RimWorld**: Full support
- **Popular Mods**: Vanilla Expanded, Alpha Genes, Medieval Overhaul, and many more
- **Versions**: 1.1, 1.2, 1.3, 1.4, 1.5, 1.6

## Support
- GitHub: https://github.com/cmdprompt/OgreStack
- Report issues on the Steam Workshop page

## Credits
- **Author**: Ogre
- **Maintainer**: Community updates for newer RimWorld versions 