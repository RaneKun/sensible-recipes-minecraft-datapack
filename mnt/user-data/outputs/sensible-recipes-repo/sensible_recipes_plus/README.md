# Sensible Recipes +

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](../LICENSE)
[![Minecraft](https://img.shields.io/badge/Minecraft-1.20.1-brightgreen.svg)](https://www.minecraft.net/)
[![Pack Format](https://img.shields.io/badge/Pack%20Format-15-blue.svg)](https://minecraft.wiki/w/Data_pack)
[![Type](https://img.shields.io/badge/Type-Datapack-orange.svg)]()
[![Environment](https://img.shields.io/badge/Environment-Client%20%2B%20Server-purple.svg)]()

Everything in [Sensible Recipes](../sensible_recipes/), extended across a large selection of content mods. Built specifically for modpacks — if you're running a heavily modded 1.20.1 instance with the supported mods below, this pack integrates seamlessly to give every mod's wood types, stone variants, and blocks the same quality-of-life treatment as vanilla.

> ⚠️ **This pack replaces Sensible Recipes — do not use both at the same time.**

---

## ✨ Features

Includes **all features from [Sensible Recipes](../sensible_recipes/)**, plus the following mod-specific additions:

### 🪚 Unicutter Recipes for Modded Blocks
The Unicutter (stonecutter) recipe system is extended to every supported mod's wood types and stone variants. For each mod's materials, you get the same treatment as vanilla:

- Log → Stripped Log, Planks, Slabs, Stairs, Fences, Fence Gates, Doors, Trapdoors, Buttons, Pressure Plates, Signs
- Stone variants → efficient conversions with extra output
- Slab → full block recovery for all mod blocks

### ♻️ Slab Recovery for Modded Blocks
All supported mod slabs can be crafted back into their full block form (2 slabs → 1 block), same as vanilla.

### 🚪 Trapdoor Recipe Fixes
Modded trapdoor recipes are added or corrected for all supported mods.

### 🏷️ Extended Item Tags
The `minecraft:iron_ingots`, `minecraft:iron_blocks`, `minecraft:obsidian`, and other key vanilla tags are extended to include equivalent mod items, enabling broader recipe compatibility:

- `minecraft:iron_ingots` → includes **BetterEnd Thallasium Ingot**, **BetterNether Cincinnasite Ingot**
- `minecraft:iron_blocks` → includes **BetterEnd Thallasium Block**
- `minecraft:obsidian` → includes BetterNether obsidian variants (Blue Obsidian, Weeping Obsidian, etc.)

---

## 🧩 Supported Mods

| Mod | Unicutter Recipes | Slab Recovery | Trapdoors | Notes |
|---|:---:|:---:|:---:|---|
| **Better Archaeology** | ✅ | — | — | |
| **Better End** | ✅ | ✅ | ✅ | Thallasium added to iron tags |
| **Better Nether** | ✅ | ✅ | ✅ | Cincinnasite added to iron tags; obsidian variants added to obsidian tag |
| **Biomes O' Plenty** | ✅ | ✅ | ✅ | |
| **Biomes We've Gone** | ✅ | ✅ | ✅ | |
| **Bygone Nether** | ✅ | ✅ | — | |
| **Deeper Darker** | ✅ | ✅ | ✅ | |
| **Dungeon Now Loading** | ✅ | — | — | |
| **Fish of Thieves** | ✅ | — | — | |
| **Glass Carpet** | ✅ | — | — | |
| **More Slabs Stairs and Walls** | — | ✅ | — | |
| **Naturalist** | — | ✅ | — | |
| **Nature's Spirit** | ✅ | ✅ | ✅ | |
| **Nemo's Mossy Blocks** | ✅ | ✅ | — | |
| **Nemo's Vertical Slabs** | ✅ | — | — | |
| **Regions Unexplored** | ✅ | ✅ | ✅ | |
| **Ribbits** | ✅ | — | — | |
| **Spawn** | ✅ | — | — | |
| **Vanilla Backport** | ✅ | — | — | |
| **YUNG's Cave Biomes** | — | ✅ | — | |

---

## ⚠️ Important — Custom Tag Warning

This datapack modifies vanilla item tags (under the `minecraft` namespace) to include items from supported mods. These tags are used in crafting recipes such as Minecarts, Beacons, and other iron/obsidian-dependent items.

**If you are using this datapack in a custom modpack that does not have all supported mods installed**, some recipes may appear broken in-game (e.g., iron-crafting recipes showing invalid ingredients). This is because the tag files still reference items from mods you haven't installed.

**To fix this**, open the datapack and manually edit the following tag files to remove any entries for mods you don't have:

```
data/minecraft/tags/items/iron_ingots.json
data/minecraft/tags/items/iron_blocks.json
data/minecraft/tags/items/obsidian.json
data/minecraft/tags/items/glass.json
data/minecraft/tags/items/iron_ingots_alternative_1.json
data/minecraft/tags/items/iron_ingots_alternative_2.json
```

Simply remove any item entries referencing mods not present in your instance and save. No other files need to be changed.

> This pack was originally built for a specific modpack where all supported mods are present. If you are adapting it for your own modpack, the tag edits above are the only thing you need to worry about.

---

## 🔧 Compatibility

| Minecraft Version | Pack Format | Supported |
|---|---|---|
| 1.20.1 | 15 | ✅ Yes |

**Mod Loader:** Compatible with both **Fabric** and **Forge** (datapacks are loader-agnostic).

**Environment:** Works on both client and server. Install server-side for multiplayer — clients do not need it.

---

## 📥 Installation

1. Download `Sensible_Recipes_Plus.zip`
2. Place the zip file inside your world's `datapacks` folder:
   ```
   .minecraft/saves/<YourWorldName>/datapacks/
   ```
3. If you are missing any of the supported mods, edit the tag files listed in the [warning section above](#️-important--custom-tag-warning) before loading the pack.
4. Launch or reload your world and run:
   ```
   /reload
   ```
5. *(Optional)* Install the [Stonecutter to Unicutter](../stonecutter_to_unicutter/) resource pack to rename the Stonecutter block to "Unicutter" in-game.

**For servers:** Place the zip in `<server_root>/world/datapacks/` and run `/reload`.

> Do **not** use Sensible Recipes and Sensible Recipes + together — the + version already includes everything from the base pack.

---

## 🖼️ Screenshots / Previews

*Coming soon.*

---

## 📝 Credits

- **Author:** [RaneKun](https://github.com/RaneKun)
- Built for modpack integration — every mod's wood and stone deserves the same love as vanilla.

---

## 📄 License

[MIT License](../LICENSE) — Free to use, modify, and redistribute with credit.
