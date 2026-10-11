# Sprout Stealth

**Sprout Stealth** is a racial mechanic of the first two phases of the [Fungal Lineage](Fungal-Lineage.md). Being tiny (2/3 of a block and 1 block tall), the [Myconid Sprout](Myconid-Sprout.md) and the [Cordyceptic Stalker](Cordyceptic-Stalker.md) vanish inside tall vegetation, making them very hard for creatures to notice.

| | |
|---|---|
| **Type** | Racial mechanic (passive) |
| **Races** | [Myconid Sprout](Myconid-Sprout.md), [Cordyceptic Stalker](Cordyceptic-Stalker.md) |
| **Cost** | None |
| **Activation** | Automatic |

---

## Contents

- [Activation](#activation)
- [Effects](#effects)
- [Ending Stealth](#ending-stealth)
- [Notes](#notes)

---

## Activation

Stealth turns on automatically when **all** of these are true:

| Condition | Details |
|---|---|
| Race | Your race is [Myconid Sprout](Myconid-Sprout.md) or [Cordyceptic Stalker](Cordyceptic-Stalker.md) |
| Cover | Both your feet and your eyes are inside a **cover block** |
| Biome | Any biome |
| State | You are alive and not in Spectator mode |

### Cover blocks

| Block | ID |
|---|---|
| Tall Grass | `minecraft:tall_grass` |
| Large Fern | `minecraft:large_fern` |

> **Note for modpack makers:** the cover blocks come from the block tag `fungalrebirth:sprout_stealth_cover` and can be changed with a data pack.

---

## Effects

While stealth is on, a **green vignette** appears around the edges of your screen.

| Situation | Effect |
|---|---|
| Creature that has **not** noticed you yet | Only notices you within **4 blocks** |
| Creature that is **already** hostile to you | Keeps chasing you only while it is within **8 blocks**. Beyond that, it loses you and goes back to the 4-block rule. |

A creature counts as already hostile if it noticed you up close, saw you outside the grass, or was hit by you.

The effect works on both vanilla creatures and Tensura monsters. Hostile creatures within 64 blocks are checked every 0.2 seconds.

---

## Ending Stealth

| Situation | Result |
|---|---|
| Leaving the cover | Stealth lasts **1 more second**, so gaps in the vegetation don't reveal you |
| Attacking a creature | Stealth **stays on** |
| Dying or switching to Spectator mode | Stealth ends immediately |
| Evolving into [Mycelial Dreadnought](Mycelial-Dreadnought.md) (or any other race) | Stealth ends immediately and no longer works |

---

## Notes

- Sprout Stealth does not make you invisible. Creatures that get within 4 blocks will still notice you.
- Combined with the Myconid Sprout's 3-block jump, tall grass is the best place to escape a fight.

---

## See Also

- [Myconid Sprout](Myconid-Sprout.md)
- [Cordyceptic Stalker](Cordyceptic-Stalker.md)
- [Spore Deprivation](Spore-Deprivation.md)
- [Fungal Lineage](Fungal-Lineage.md)
- [Home](Home.md)
