# Sensible Recipes

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](../LICENSE)
[![Minecraft](https://img.shields.io/badge/Minecraft-1.20.1-brightgreen.svg)](https://www.minecraft.net/)
[![Pack Format](https://img.shields.io/badge/Pack%20Format-15-blue.svg)](https://minecraft.wiki/w/Data_pack)
[![Type](https://img.shields.io/badge/Type-Datapack-orange.svg)]()
[![Environment](https://img.shields.io/badge/Environment-Client%20%2B%20Server-purple.svg)]()

A vanilla-focused datapack that fixes recipes that have always felt off. Craft things that were previously uncraftable, recover resources you thought were lost forever, and process items in bulk without the repetitive grind — all without touching a single mod.

> **Want mod support too?** Check out [Sensible Recipes +](../sensible_recipes_plus/) instead.

---

## ✨ Features

### 🔨 Previously Uncraftable Items
Vanilla Minecraft locks several useful items behind trading, fishing, or dungeon loot with no crafting alternative. Sensible Recipes fixes that:

| Item | Recipe |
|---|---|
| **Saddle** | 3 Leather + 2 Iron Nuggets |
| **Name Tag** | 2 Paper + 2 String + 1 Ink Sac |
| **Chainmail Armor** | Chains + Iron Ingots (full set) |
| **Horse Armor** | Iron / Gold / Diamond Ingots (shaped recipe) |
| **Enchanted Golden Apple** | 8 Gold Blocks + 1 Golden Apple |

---

### ♻️ Slab → Full Block Recovery
Cut a block into slabs and regret it? Craft two slabs of the same type back into the original block. Works across all vanilla wood types and stone variants — no more wasted material.

Covers: all wood planks, stone, cobblestone, andesite, diorite, granite, sandstone, quartz, bricks, and many more.

---

### 📦 Bulk Crafting
Stop crafting one item at a time. These recipes let you produce large quantities in a single craft:

| Item | Bulk Output |
|---|---|
| Bowl | 16 (from logs) |
| Stick | 16 (from logs) |
| Chest | 4 (from logs) |
| Chain | 9 (from iron ingots and block) |
| Cauldron | 9 (from iron blocks) |
| Minecart | 9 (from iron blocks) |
| Bucket | 9 (from iron blocks) |
| Shears | 9 (from iron blocks) |
| Iron Door | 27 (from iron blocks) |
| Lightning Rod | 9 (from copper blocks) |
| Candle | 4 (from wool and honeycomb block) |
| Honeycomb | 4 (from honeycomb balls) |
| Melon Slices | 9 (from melon) |
| Clay Ball | 4 (from clay) |

---

### 🔥 Bulk Smelting
Smelt entire blocks of raw ore at once in the blast furnace:

| Input | Output |
|---|---|
| Block of Raw Iron | Block of Iron |
| Block of Raw Gold | Block of Gold |
| Block of Raw Copper | Block of Copper |

---

### 🪨 Unicutter (Stonecutter) Recipes
The stonecutter — renamed **Unicutter** when paired with the [companion resource pack](../stonecutter_to_unicutter/) — is expanded far beyond stone. Use it as a precision crafting station for wood and more:

- **Log → Stripped Log** (no axe needed)
- **Log → Planks, Slabs, Stairs, Fences, Fence Gates, Doors, Trapdoors, Buttons, Pressure Plates, Signs, Boats**
- **Planks → Slabs, Stairs, Fences, Fence Gates, Trapdoors, Buttons, Pressure Plates**
- **Glass → Panes and Bottles**
- All vanilla wood types supported (Oak, Spruce, Birch, Jungle, Acacia, Dark Oak, Mangrove, Cherry, Bamboo, Crimson, Warped)
- All vanilla glass types supported (Glass, Tined Glass, White, Light Gray, Gray, Black, Brown, Red, Orange, Yellow, Lime, Green, Cyan, Light Blue, Blue, Purple, Magenta, Pink Stained Glass)

This makes the Unicutter a true multi-purpose cutting and crafting station — not just a stone block tool.

---

### 🧪 Quality of Life Recipes

**Glass & Concrete:**
- Smelt any **Concrete Powder → matching Stained Glass** (all 16 colors)
- Craft **6 Glass Panes → 1 Glass Block** (reverse the pane recipe)

**Ice:**
- **1 Packed Ice → 9 Ice** (unpack bulk ice storage)

**Dirt & Terrain Variants:**
- Craft **Grass Block** (Dirt + Bone Meal variants)
- Craft **Podzol** (Dirt + Spruce Saplings/Leaves variants)
- Craft **Mycelium** (Dirt + Mushroom variants)
- Craft **Coarse Dirt** (Dirt + Gravel)
- Craft **Rooted Dirt** (Dirt + Hanging Roots)
- Craft **Red Sand** (Sand + Red Dye)
- Craft **Crimson/Warped Nylium** (Netherrack + Crimson/Warped Fungus)

**Bricks:**
- **1 Bricks block → 4 Brick items** (break blocks back into items)
- Nether Brick equivalent

**Decorated Pot:**
- Recipe now yields **4 Decorated Pots** per craft

**Dyes:**
- Alternative recipes for Black, Brown, and other dyes using different source materials

**Other Notable Recipes:**
- **Beacon** — Obsidian and Glass tag expanded (All glass variants + Crying Obsidian also works)
- **Cobweb** — Now craftable
- **Bell** — Now craftable
- **Totem of Undying** — Now craftable
- **Sculk Sensor** — Now craftable
- **Daylight Sensor** — Glass tag expanded (All glass variants work)
- **Dispenser** — Alternative recipe added
- **Ender Chest** — Obsidian tag expanded(Crying Obsidian also works)

---

## 🔧 Compatibility

| Minecraft Version | Pack Format | Supported |
|---|---|---|
| 1.20.1 | 15 | ✅ Yes |
|(you can use this datapck with modern versions of minecraft as well but some newly added blocks are not supported yet and there may be recipe format changes which have not been tested yet)| x.x |❔|

**Environment:** Works on both client and server. Install server-side for multiplayer — clients do not need it.

---

## 📥 Installation

1. Download `Sensible_Recipes.zip`
2. Place the zip file inside your world's `datapacks` folder:
   ```
   .minecraft/saves/<YourWorldName>/datapacks/
   ```
3. Launch or reload your world and run:
   ```
   /reload
   ```
4. *(Optional)* Install the [Stonecutter to Unicutter](../stonecutter_to_unicutter/) resource pack to rename the Stonecutter block to "Unicutter" in-game.

**For servers:** Place the zip in `<server_root>/world/datapacks/` and run `/reload`.

---

## 📝 Credits

- **Author:** [RaneKun](https://github.com/RaneKun)
- Crafted with care for vanilla survival players who just want things to make more sense.

---

## 📄 License

[MIT License](../LICENSE) — Free to use, modify, and redistribute with credit.
