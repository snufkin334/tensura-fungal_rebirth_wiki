# Myconid Sprout

![Myconid Sprout](link_da_imagem)

> *"A tiny mushroom sprout born in the Ancient Forest. Fragile, but nimble and a prodigious jumper."*

The **Myconid Sprout** is the first phase of the [[Fungal Lineage]] and the only fungal race that can be chosen as a starting race. It is a tiny, fragile mushroom that depends on the spores of the Ancient Forest to stay strong. What it lacks in strength, it makes up for in speed, jumping, stealth and fall resistance.

| | |
|---|---|
| **Race ID** | `fungalrebirth:myconid_sprout` |
| **Phase** | 1 of 5 |
| **Type** | Majin |
| **Starting race** | Yes |
| **Selection difficulty** | Hard |
| **Evolves from** | — |
| **Evolves into** | [[Cordyceptic Stalker]] |
| **Intrinsic Skill** | [[Fungal Anatomy]] |

![Myconid Sprout race icon](link_da_imagem)

---

## Contents

- [Obtaining](#obtaining)
- [Stats](#stats)
- [Skills](#skills)
- [Resistances and Traits](#resistances-and-traits)
- [Racial Mechanics](#racial-mechanics)
- [Evolution](#evolution)
- [Strategy](#strategy)
- [Trivia](#trivia)

---

## Obtaining

The Myconid Sprout is selected on the **starting race screen** when you reincarnate. The addon adds it to Tensura's starting race list automatically.

When a player becomes a Myconid Sprout, by selection, reincarnation or command:

1. They learn the Tensura skill **Poison**.
2. They are **teleported to the Ancient Forest**, 16 to 32 blocks from the edge of the **Labyrinth** tree, and their spawn point is set there. If no Labyrinth is found, they are sent to the nearest Ancient Forest instead.

See [[Getting Started]] for the full spawn rules.

---

## Stats

| Stat | Value | Compared to a Human |
|---|---|---|
| Health | 8 | 4 hearts instead of 10 |
| Spiritual Health | 24 | 60 for a Human |
| Magicules | 400 – 600 | Rolled on reincarnation |
| Aura | 10 – 20 | Rolled on reincarnation |
| Attack Damage | ×0.50 | Half damage |
| Movement Speed | ×1.10 | 10% faster |
| Height | 2/3 of a block | 1.8 blocks for a Human |
| Jump Height | 3 blocks | About 1.25 blocks for a Human |

> **Note:** The jump is tuned so the Sprout can reliably jump onto a 3-block wall (the actual peak is 3.25 blocks), but not a 4-block one.

---

## Skills

### Intrinsic Skill

| Skill | Type | Cost | Summary |
|---|---|---|---|
| [[Fungal Anatomy]] | Toggle | None | While active: bonus speed, permanent Night Vision and no fall damage within a safe distance |

| Effect | Normal | Mastered |
|---|---|---|
| Movement Speed bonus | +15% | +25% |
| Safe fall distance | 10 blocks | 15 blocks |
| Night Vision | Permanent | Permanent |

Fungal Anatomy can be toggled from the skill menu or by pressing its key on the ability bar. While it is on, it gains **1 mastery point every 30 seconds**. The skill is kept after evolving. See [[Fungal Anatomy]] for full details.

### Learned Skills

| Skill | Source | Notes |
|---|---|---|
| Poison | Tensura Common Skill | Learned when the race is set. It is kept permanently, even after evolving. |

---

## Resistances and Traits

| Name | Type | Description |
|---|---|---|
| Poison Resistance | Resistance | Granted by the race |
| Magicule Poison Immunity | Racial trait | Never affected by Magicule Poison. Shared by every fungal race. |

---

## Racial Mechanics

### Spore Deprivation

Away from the spores of the Ancient Forest, the sprout withers. While a Myconid Sprout is outside the `tensura:ancient_forest` biome (any other dimension also counts), it receives the [[Spore Deprived]] effect, with infinite duration:

| Effect | Value |
|---|---|
| Movement Speed | −45% (same as Slowness III) |
| Mining Speed | 9% of normal (same as Mining Fatigue II) |
| Attack Speed | −20% |
| Magicule Regeneration | None (the Sleep Mode bonus still works) |

The effect is checked every half second. It is removed when you return to the Ancient Forest, switch to Creative or Spectator mode, or evolve. See [[Spore Deprivation]].

### Sprout Stealth

Being only 2/3 of a block tall, the sprout disappears inside tall vegetation. While its body is inside **tall grass** or a **large fern**, in any biome, [[Sprout Stealth]] turns on:

| Situation | Effect |
|---|---|
| Creature that has not noticed you | Only notices you within **4 blocks** |
| Creature already hostile to you | Loses track of you if you get more than **8 blocks** away |
| Leaving the grass | Stealth lasts 1 more second, so small gaps don't reveal you |
| Attacking | Does not end stealth |

A green vignette appears on screen while stealth is active. This mechanic also works for the [[Cordyceptic Stalker]].

---

## Evolution

| Evolves into | Requirement 1 (50%) | Requirement 2 (50%) |
|---|---|---|
| [[Cordyceptic Stalker]] | 2,000 EP | Consume 3 [[Cryptid Insectoid Pupa]] |

### Where to find Cryptid Insectoid Pupae

| Source | Chance |
|---|---|
| Breaking a Brown Mushroom in the Ancient Forest (by hand or tool, as a player) | 0.8% |
| Breaking a [[Rotten Oak Log]] without Silk Touch | 25% |
| [[Pile of Rotten Logs]] chest | 4% per chest |

The pupa can always be eaten, even when you are not hungry. Each one gives **Nausea** for 10 seconds and **Poison I** for 5 seconds.

---

## Strategy

- **Turn on Fungal Anatomy immediately.** It has no cost, and mastering it early gives you a 25% speed bonus and 15 blocks of safe falling.
- **Don't leave the Ancient Forest.** Spore Deprived slows you down and stops your Magicule regeneration, which makes it very hard to grow outside your home biome.
- **Avoid fair fights.** With 8 HP and half damage, use tall grass to sneak around and your 3-block jump to escape onto terrain that enemies can't reach.
- **Farm the Pile of Rotten Logs.** It is the best source of pupae, but 60% of piles have 1 or 2 Phantaspores nearby.

---

## Trivia

- The Myconid Sprout is the only phase of the lineage marked as **Hard** difficulty. All later phases are marked as Easy, but that rating is only shown on the starting race screen.
- Its spawn behavior is similar to Tensura's Daemon, which is sent to the Hell dimension when the race is set.

---

## See Also

- [[Fungal Lineage]]
- [[Getting Started]]
- [[Cordyceptic Stalker]]
- [[Home]]
