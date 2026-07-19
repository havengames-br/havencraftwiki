---
title: Withering Spire Loot
description: Every custom item from the Spire — bespoke gear, toxic consumables, and treasure tiers.
published: true
date: 2026-07-19T00:00:00.000Z
tags: items, withering-spire
editor: markdown
dateCreated: 2026-07-19T00:00:00.000Z
---

# Withering Spire Loot

Custom items from the [Withering Spire](/dungeons/withering-spire). This dungeon is still in development, and its loot reflects that: a full set of toxic-themed consumables and treasure tiers is live and wired into every drop table, but a whole line of bespoke gear — the boss unique weapon, a poison-hunting shovel, a full armor set — exists in the game files without a confirmed way to obtain it yet. Both are listed below so nothing gets lost, but treat the "Designed Gear" section as a preview, not a confirmed drop.

## Treasure

Trash mobs pay out in diamonds, quartz, obsidian, slime balls, and gold ingots, scaling up in five tiers as things get tougher:

| Tier | Used by | Diamond | Quartz | Obsidian | Slime Ball | Gold Ingot | Netherite Scrap |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Common | Base trash (Volatile Sludge, Cursed Spore Blossom) | 1–2 (12%) | 2–5 (35%) | 1–3 (20%) | 1–3 (30%) | 1–3 (15%) | — |
| Elite | Elite trash (Toxic Apothecary, Vile Repulsor, Rotted Hag, Noxious Bloom, Giant Volatile Sludge) | 1–3 (22%) | 3–8 (45%) | 2–5 (30%) | 2–5 (40%) | 2–5 (20%) | 1 (3%) |
| Mini-Boss | Bilepod | 3–6 | 6–12 | 3–6 | 3–6 | 3–6 (75%) | 1–2 (15%) |
| Boss | Verdelith, Hag Matriarch, Aldric/Bilepod's bonus roll, Grothmire (currently) | 6–12 | 10–20 | 6–12 | 6–12 | 6–12 | 2–4 (60%) |
| Cuboss (defined, not yet wired) | Intended for Grothmire | 8–16 | 14–26 | 8–16 | 20–36 | 8–16 | 3–6 (75%) |

A dedicated **Cuboss** treasure tier exists in the data — richer than the standard Boss tier across the board — but [Grothmire](/monsters/withering-spire/grothmire) currently rolls the same bundle as [Aldric Fennwick/Bilepod](/monsters/withering-spire/aldric-fennwick) instead of its own. See the note on the [dungeon page](/dungeons/withering-spire).

## Consumables

Wired into every drop table in the dungeon — the Spire's signature "toxic pool."

| | Item | What It Does | Source |
| --- | --- | --- | --- |
| | **Venomtip Arrows** | Tipped arrows carrying the Spire's poison. | Common drop across most Withering Spire mobs |
| | **Toxic Splash Flask** | A splash potion of Poison. | Common drop across most Withering Spire mobs |
| | **Spider Eye** | Standard brewing ingredient. | Common drop across most Withering Spire mobs |
| <img src="/assets/items/potions/allfather_heart.png" alt="" width="32"> | **Draught of Haste** | Drink for Haste II for 3 minutes — useful for the Spire's quartz/obsidian deposits and for outrunning the toxic terrain. | Rare drop (1–3%) from most mobs; a better shot (20–30%) as a boss bonus roll. Currently shares its icon with [Heart of the Allfather](/items/viking-stronghold#boss-uniques) — no dedicated art yet. |
| | **Enchanted Golden Apple** | Standard notch apple. | Very rare (1%) from most mobs; a better shot (15–25%) as a boss bonus roll |
| | **Beheading III book** | Endgame beheading enchant book. | 10% from all four bosses |

## Designed Gear

Fully modeled and statted in the game's files, but none of it currently appears in `WitheringSpireDrops.yml` or any dungeon chest function — worth a sanity check before promising players a chase item that can't drop yet.

| | Item | What It Does | Intended Source |
| --- | --- | --- | --- |
| <img src="/assets/items/withering-spire/toxic_fang.png" alt="" width="32"> | **Toxic Fang** | Diamond sword, +10 attack damage, Sharpness VI. Passive: poisons enemies for 5 seconds on hit, dealing armor-ignoring poison damage over time. | Not yet wired to a drop source |
| <img src="/assets/items/withering-spire/toxic_bow.png" alt="" width="32"> | **Toxic Bow** | Bow, Power VI. Arrows slow, nauseate, and poison on hit. | Not yet wired to a drop source |
| <img src="/assets/items/withering-spire/toxic_shovel.png" alt="" width="32"> | **Toxic Shovel** | Netherite shovel, Efficiency VI. Right-click: releases toxic spores for 10 seconds that point toward the nearest dropped item within 48 blocks. Currently only seen equipped on [Cursed Spore Blossom](/monsters/withering-spire/cursed-spore-blossom) — not confirmed to drop for players. | Not yet wired to a drop source |
| <img src="/assets/items/withering-spire/toxic_shield.png" alt="" width="32"> | **Toxic Shield** | Off-hand totem-slot item, unbreakable, +2 hearts, minor knockback resistance. | Not yet wired to a drop source |
| <img src="/assets/items/withering-spire/repulsors_grasp.png" alt="" width="32"> | **Repulsor's Grasp** | Diamond axe/pickaxe (two nearly identical item defs share this name), +12 attack damage, Knockback II. On hit: extra knockback burst and Poison. This appears to be [Verdelith](/monsters/withering-spire/verdelith)'s equipped weapon. | Not yet wired to a drop source |
| <img src="/assets/items/withering-spire/toxic_wing.png" alt="" width="32"> | **Toxic Wing** | A cosmetic wing piece; currently commented out of Verdelith's equipment loadout in the source data. | Not currently equipped or dropped |
| | **Matriarch's Cowl / Shroud / Leggings / Treads** | Leather armor set (green-dyed), Protection V on every piece. The Shroud grants Poison immunity; the Treads grant Slowness immunity and Depth Strider II. | Not yet wired to a drop source |
| | **Draught of Clearing** | Drink to cleanse Poison, Wither, and Confusion. | Not yet wired to a drop source |

## Souls & Keys

- **[Toxic Soul](/items/souls)** — this dungeon's soul currency, dropped by both stages of Aldric/Bilepod, by Verdelith, and (in smaller amounts) by a chance roll off other Withering Spire mobs.
- **Normal / Elite / Boss-tier souls** — the shared tiered soul system, awarded by trash, elite, and boss kills respectively across the dungeon.
- **[Blank Key](/items/keys)** — a 50% drop from all four bosses.
- **Small Auto Salvager / Small Auto Seller** — shared utility items (also purchasable from [traders](/traders)); a very rare (~1%) drop off ordinary Withering Spire monsters, a better (~6–7%) roll from bosses.

## Related

- [Withering Spire](/dungeons/withering-spire)
- [Souls & Currency](/items/souls)
- [Keys](/items/keys)
- [Castle Nocturn Loot](/items/castle-nocturn) — the previous tier
