<div align="center">

![Version](https://img.shields.io/badge/ShadowedUF-v3.2.12-blue.svg?style=for-the-badge)
[![Downloads](https://img.shields.io/github/downloads/Xurkon/ShadowedUnitFrames/total?style=for-the-badge&color=e67e22)](https://github.com/Xurkon/ShadowedUnitFrames/releases)
[![Documentation](https://img.shields.io/badge/Documentation-View%20Docs-58a6ff?style=for-the-badge)](https://xurkon.github.io/ShadowedUnitFrames/)
[![Patreon](https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white)](https://www.patreon.com/Xurkon)
[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.me/Xurkon)
![License](https://img.shields.io/github/license/Xurkon/ShadowedUnitFrames?style=for-the-badge&color=2980b9)

<br/>

**A lightweight, highly configurable unit frame addon for World of Warcraft.**

[Download Latest](https://github.com/Xurkon/ShadowedUnitFrames/releases/latest) &nbsp;&bull;&nbsp; [View Source](https://github.com/Xurkon/ShadowedUnitFrames) &nbsp;&bull;&nbsp; [Documentation](https://xurkon.github.io/ShadowedUnitFrames/)

</div>

---

## About

Shadowed Unit Frames (SUF) is a comprehensive unit frame addon that provides fully customizable frames for Player, Target, Party, Raid, and more. This is a maintained fork with support for custom class colors on private servers like Ascension.

---

## Features

- **Fully Customizable Frames** - Configure individual unit frames for Player, Target, Party, Raid, Boss, Arena, and more
- **Custom Class Colors** - Support for both standard WoW classes and custom server classes (Ascension, etc.)
- **Tag System** - Display dynamic text on frames using built-in or custom tags
- **Aura Tracking** - Buff and debuff display with filtering and sorting options
- **Portrait Support** - 3D and 2D character portraits
- **Heal Predictions** - Visual healing prediction and absorbs
- **Combat Text** - Floating combat text for damage and healing
- **Power Bars** - Support for all power types (Mana, Rage, Energy, Runic Power, etc.)

---

## Installation

1. [Download](https://github.com/Xurkon/ShadowedUnitFrames/releases/latest) the latest release
2. Extract the archive — you will get a folder named `ShadowedUnitFrames`
3. Move that folder into your `Interface/AddOns/` directory:
   ```
   World of Warcraft/
   └── Interface/
       └── AddOns/
           └── ShadowedUnitFrames/  ← place it here
   ```

**Note:** Shadowed UF Options (the configuration panel) is included in this package and loads on demand.

---

## Private Server Support

This fork includes special support for custom class colors on private servers:

### Ascension / Conquest of Azeroth

On Ascension realms, all 32 class tokens are automatically detected from `RAID_CLASS_COLORS` and made available in the class color options panel. This includes custom classes like Prophet, Ranger, Necromancer, Wildwalker, and more.

---

## Configuration

Access the options panel via:
- Blizzard Interface Options → AddOns → Shadowed Unit Frames
- Type `/suf` in chat

### Key Options

| Tab | Description |
|-----|-------------|
| **General** | Global settings, layout options |
| **Units** | Configure individual frames (Player, Target, Party, Raid, etc.) |
| **Tags** | Custom text tags using the tag system |
| **Auras** | Buff and debuff display settings |
| **Colors** | Class colors, health colors, power colors |
| **Help** | Tag documentation and Lua programming resources |

---

## Tag System

SUF includes a powerful tag system. Example tags:

```
[name]           - Unit name
[level]          - Unit level
[class]          - Class name
[health]         - Current health
[health:percent] - Health percentage
[power]          - Current power
[power:percent]  - Power percentage
[status]         - Dead/Offline/AFK status
```

---

## Credits

- **Shadowed** — Original addon developer
- **Xurkon** — Fork maintainer, Ascension class color support

---

## License

MIT License — see [LICENSE](LICENSE) for details.