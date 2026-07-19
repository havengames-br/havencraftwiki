---
title: Volatile Sludge
description: The Withering Spire's living slime hazard — base, corrupted, and giant forms.
published: true
date: 2026-07-19T00:00:00.000Z
tags: monsters, withering-spire
editor: markdown
dateCreated: 2026-07-19T00:00:00.000Z
---

# Volatile Sludge

A small, unstable slime that's as much hazard as it is monster — it doesn't hit you directly so much as poison the air around itself and spit at range. You'll rarely find it just standing around a room; most of the Spire's Volatile Sludge shows up **summoned** — by [Bilepod](/monsters/withering-spire/aldric-fennwick), by [Verdelith](/monsters/withering-spire/verdelith)'s Last Gasp, by the [Noxious Bloom](/monsters/withering-spire/noxious-bloom), or split off from its own Giant form when that dies.

**Found in:** [Withering Spire](/dungeons/withering-spire) — scattered rarely on its own, but constantly summoned by other threats

| Stat | Value |
| --- | --- |
| Health | 40 |
| Damage | 0 (ability-based) |
| Threat | Low |

## Abilities

- **Sludge Aura** (every 10s) — poisons anyone within 3.5 blocks just for standing close.
- **Sludge Spit** — a slow poison projectile, 6 damage on hit, fired at range or on melee contact.
- **Death Burst** — pops a small poison cloud when it dies, so finishing it in melee still costs you a tick.
- **Acid Pool** — leaves a lingering poison-and-damage puddle behind on death.

## Drops

| Drop | Amount | Chance |
| --- | --- | --- |
| Experience | 35–60 | Always |
| Normal Soul (Tier 2) | — | Guaranteed |
| Diamond / Quartz / Obsidian / Slime Ball / Gold Ingot | — | Common treasure bundle |
| Toxic consumable (Venomtip Arrows / Toxic Splash Flask / Spider Eye) | — | 40% |
| [Warrior Soul](/items/souls) | 1 | 1.2% |

## Corrupted Volatile Sludge

A faster, harder-hitting mutation that actively attacks instead of just lingering — and rides a second, weaker sludge into battle with it.

| Stat | Value |
| --- | --- |
| Health | 30 (a leaner "&2&lVolatile Sludge" variant runs 20 HP / 8 damage) |
| Damage | 5–8 |
| Threat | Low |

- Same aura, spit, and death-burst kit as the base Sludge, with a yellow-tinted aura and a shorter poison duration but a higher level.
- Spawns mounted on a second sludge rider.
- **Note:** the dungeon's spawner data references this variant under a slightly different internal name than its mob definition (`CrackedVolatileSlime` vs. the defined `CrackedVolatileSludge`) — worth a sanity check, since a mismatch like that usually means the spawner silently fails to place anything. See the dungeon page notes.

## Giant Volatile Sludge

The elite version — a genuine bruiser rather than background hazard, and a rare find (only one placed in the whole dungeon).

| Stat | Value |
| --- | --- |
| Health | 120 |
| Damage | 0 (ability-based) |
| Threat | Elite |

- Same aura/spit/death-burst kit as the base Sludge, scaled up.
- **Splits on death** — bursts into two regular Volatile Sludge on top of its own death burst.

**Drops (Giant only):**

| Drop | Amount | Chance |
| --- | --- | --- |
| Experience | 90–140 | Always |
| Elite Soul (Tier 3) | — | Guaranteed |
| Diamond / Quartz / Obsidian / Slime Ball / Gold Ingot | — | Guaranteed elite treasure bundle |
| Toxic consumable (Venomtip Arrows / Toxic Splash Flask / Spider Eye) | — | Guaranteed |
| Utility consumable (Haste Draught / Enchanted Golden Apple) | — | Guaranteed |
| [Warrior Soul](/items/souls) | 1 | 2% |
| Small Auto Salvager/Seller | 1 | 1% |

## Related

- [Aldric Fennwick / Bilepod](/monsters/withering-spire/aldric-fennwick) — summons these constantly
- [Noxious Bloom](/monsters/withering-spire/noxious-bloom) — spits these out on a timer
- [Monsters index](/monsters)
