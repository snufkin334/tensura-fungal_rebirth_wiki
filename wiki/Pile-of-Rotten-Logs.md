# Pile of Rotten Logs

The **Pile of Rotten Logs** is a small structure added by Fungal Rebirth to the **Ancient Forest**. It is a heap of oak logs, some of them rotten, hiding loot chests, and it is often guarded by Phantaspores. It is the best place to find [Rotten Oak Log](Rotten-Oak-Log.md) and [Cryptid Insectoid Pupa](Cryptid-Insectoid-Pupa.md).

| | |
|---|---|
| **Biome** | Ancient Forest (`tensura:ancient_forest`) |
| **Variants** | 2 (one chest or two chests) |
| **Frequency** | Up to 1 per 10×10 chunks |
| **Loot table** | `fungalrebirth:chests/pile_of_rotten_logs` |
| **Mobs** | Phantaspore (Tensura), 60% chance |
| **Locate command** | `/fungalrebirth locatepile` |

---

## Contents

- [Generation](#generation)
- [Variants](#variants)
- [Rotten Logs](#rotten-logs)
- [Phantaspores](#phantaspores)
- [Loot](#loot)
- [Locating a Pile](#locating-a-pile)

---

## Generation

The trees (36 to 57 blocks tall) and rocks of the Ancient Forest are placed late in world generation, so a normal Minecraft structure would end up buried inside them. Instead, the Pile of Rotten Logs is placed **after** the area has fully generated, by looking at the real blocks around it.

| Step | Details |
|---|---|
| 1. Region | The world is divided into regions of **10×10 chunks**. Each region picks one chunk, based on the world seed. |
| 2. Chance | If that chunk is in the Ancient Forest, the region gets a pile with a **90%** chance. |
| 3. Waiting | The pile is only placed once the surrounding chunks are loaded and no player is within 3 chunks, so it never appears in front of a player. |
| 4. Finding a spot | The game searches up to **32 blocks** from the center of the chunk for a spot where the pile fits. |
| 5. Placing | One of the two variants is placed, and the region is marked as done. If no spot is found, the region has no pile. |

### Valid spot

| Requirement | Details |
|---|---|
| Ground | Grass Block, Dirt, Coarse Dirt, Podzol, Rooted Dirt, Mycelium or Tensura's Loose Dirt (not moss or stone) |
| Flatness | Height difference of at most 1 block |
| Water | None |
| Free space | 4 free blocks above the ground, with no logs, leaves, giant mushrooms or rocks |

The chosen spot can be slightly **outside** the Ancient Forest, since only the region's chunk must be in the biome.

> **Note for modpack makers:** the biomes come from the tag `fungalrebirth:has_structure/pile_of_rotten_logs`, and the valid ground from the block tag `fungalrebirth:rotten_log_pile_ground`. Both can be changed with a data pack.

---

## Variants

| Variant | Chests | Chance |
|---|---|---|
| Single-chest pile | 1 | 60% |
| Two-chest pile | 2 | 40% |

---

## Rotten Logs

When a pile is placed, each **oak log** in it has a **10%** chance of becoming a [Rotten Oak Log](Rotten-Oak-Log.md), keeping the same orientation. Breaking a Rotten Oak Log without Silk Touch has a 25% chance of dropping a [Cryptid Insectoid Pupa](Cryptid-Insectoid-Pupa.md).

---

## Phantaspores

| Property | Value |
|---|---|
| Chance of Phantaspores | 60% per pile |
| Amount | 1 (80%) or 2 (20%) |
| Spawn area | Within 6 blocks of the pile's center, on the ground |
| Despawn | Never (they stay to guard the pile) |

The Phantaspore is a monster from Tensura: Reincarnated.

---

## Loot

Each chest is filled the first time it is opened. The loot has three separate pools.

### Pool 1: Common loot (3 to 5 rolls)

| Item | Amount | Chance per roll |
|---|---|---|
| Low Quality Magic Crystal (Tensura) | 1 – 3 | 25.5% |
| Charcoal | 2 – 6 | 18.4% |
| Brown Mushroom | 2 – 5 | 14.3% |
| Cobweb | 1 – 3 | 10.2% |
| Bone | 1 – 4 | 10.2% |
| Red Mushroom | 1 – 3 | 8.2% |
| Golden Apple | 1 – 2 | 7.1% |
| Bottle o' Enchanting | 1 – 3 | 6.1% |

### Pool 2: Metal (1 roll)

| Item | Amount | Chance |
|---|---|---|
| Low Magisteel Nugget (Tensura) | 2 – 6 | 55% |
| Low Magisteel Ingot (Tensura) | 1 | 10% |
| Nothing | — | 35% |

### Pool 3: Pupa (1 roll)

| Item | Amount | Chance |
|---|---|---|
| [Cryptid Insectoid Pupa](Cryptid-Insectoid-Pupa.md) | 1 | 4% |
| Nothing | — | 96% |

> **Note:** In the two-chest variant, each chest rolls its loot separately.

---

## Locating a Pile

Server operators can find the nearest pile that has already been placed with:

```
/fungalrebirth locatepile
```

See [Commands](Commands.md).

---

## See Also

- [Rotten Oak Log](Rotten-Oak-Log.md)
- [Cryptid Insectoid Pupa](Cryptid-Insectoid-Pupa.md)
- [Commands](Commands.md)
- [Getting Started](Getting-Started.md)
- [Home](Home.md)
