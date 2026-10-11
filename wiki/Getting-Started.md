# Getting Started

![Myconid Sprout in the Ancient Forest](link_da_imagem)

This page explains how to begin a playthrough as a fungal race: how to choose the starting race, where you spawn, what you can do on day one, and how to reach your first evolution.

> **Tip:** For the full stats of every phase, see [[Fungal Lineage]]. For the starting race itself, see [[Myconid Sprout]].

---

## Contents

- [Choosing the Starting Race](#choosing-the-starting-race)
- [Where You Spawn](#where-you-spawn)
- [Your Starting Kit](#your-starting-kit)
- [Survival Tips](#survival-tips)
- [Your First Evolution](#your-first-evolution)
- [Where to Go Next](#where-to-go-next)

---

## Choosing the Starting Race

[[Myconid Sprout]] is the only fungal race you can pick when you reincarnate. The other four phases can only be reached by evolving.

| Property | Value |
|---|---|
| Race ID | `fungalrebirth:myconid_sprout` |
| Difficulty (selection screen) | Hard |
| Appears in starting selection | Yes, added automatically |

The addon adds Myconid Sprout to Tensura's starting race list for you. It writes `fungalrebirth:myconid_sprout` into the `Races.startingRaces` field of Tensura's `reincarnation_config` file when the game or server starts. If the race is already in the list, nothing is changed.

> **Note for server owners:** the config file is edited and saved automatically. If you remove the race from the list by hand, it will be added back the next time the server starts.

---

## Where You Spawn

Every time a player becomes a Myconid Sprout (on world creation, on reincarnation or through a command), they are **teleported to the Ancient Forest** and their **spawn point is set there**.

| Step | What happens |
|---|---|
| 1 | The game searches for the nearest **Labyrinth** tree (`tensura:labyrinth/labyrinth_tree`), first within 200 chunks, then within 500 chunks. The search starts from the player's position if they are in the Overworld, or from the world spawn otherwise. |
| 2 | If a Labyrinth is found, the player is placed **16 to 32 blocks** from the edge of the tree, in a random direction. Up to 12 directions are tried until safe ground is found. |
| 3 | If no Labyrinth is found, the game searches for the nearest **Ancient Forest** biome instead (up to 6,400 blocks, then up to 16,000 blocks) and places the player there. |
| 4 | If no Ancient Forest is found either, the player stays at the normal spawn. |

"Safe ground" means a solid block that is not leaves, a log or liquid, with 2 free blocks above it.

The spawn point is forced, so it works without a bed and no "Respawn point set" message is shown. Sleeping in a bed or using a respawn anchor later replaces it as usual.

> **Tip:** The Labyrinth is rare (Tensura places at most one per 100×100 chunks), so the first teleport can take a moment while the world generates.

---

## Your Starting Kit

### Base stats

| Stat | Value |
|---|---|
| Health | 8 (4 hearts) |
| Spiritual Health | 24 |
| Magicules | 400 – 600 (rolled on reincarnation) |
| Aura | 10 – 20 (rolled on reincarnation) |
| Attack Damage | ×0.50 |
| Movement Speed | ×1.10 |
| Height | 2/3 of a block |
| Jump Height | 3 blocks |

### Skills and traits

| Name | Type | Notes |
|---|---|---|
| [[Fungal Anatomy]] | Intrinsic Skill (toggle, no cost) | +15% speed, permanent Night Vision, no fall damage up to 10 blocks |
| Poison Resistance | Resistance | Granted by the race |
| Poison | Common Skill (Tensura) | Learned when you become a Myconid Sprout. It is learned permanently and kept after evolving. |
| Magicule Poison Immunity | Racial trait | Every fungal race is immune to Magicule Poison |
| [[Sprout Stealth]] | Racial mechanic | You hide inside tall grass and large ferns |
| [[Spore Deprivation]] | Racial mechanic | You weaken outside the Ancient Forest |

> **Tip:** Turn on [[Fungal Anatomy]] right away. It costs nothing to keep active, and it gains 1 mastery point every 30 seconds while it is on.

---

## Survival Tips

### Stay in the Ancient Forest

While you are a Myconid Sprout and outside the `tensura:ancient_forest` biome (this includes any other dimension), you receive [[Spore Deprived]]:

| Effect | Value |
|---|---|
| Movement Speed | −45% (same as Slowness III) |
| Mining Speed | 9% of normal (same as Mining Fatigue II) |
| Attack Speed | −20% |
| Magicule Regeneration | None (natural regeneration stops; the Sleep Mode bonus still works) |

The effect is removed as soon as you return to the Ancient Forest, switch to Creative mode or evolve into [[Cordyceptic Stalker]].

### Hide in tall grass

With your tiny body, you can use [[Sprout Stealth]]. While your body is inside **tall grass** or a **large fern**, in any biome:

| Situation | Detection range |
|---|---|
| Creature that has not noticed you yet | Only notices you within **4 blocks** |
| Creature already hostile to you | Loses track of you beyond **8 blocks** |

A green vignette appears on your screen while stealth is active. Stealth lasts 1 more second after you leave the grass, so gaps in the bushes won't reveal you. Hitting a creature does not end stealth.

### Use your jump and fall resistance

You can jump up 3-block walls, and [[Fungal Anatomy]] lets you fall up to 10 blocks without damage. Use height to escape threats you cannot fight. With only 4 hearts and half damage, most fights are a bad idea early on.

---

## Your First Evolution

To evolve from [[Myconid Sprout]] into [[Cordyceptic Stalker]], you need two things. Each requirement counts for **50%** of the evolution progress.

| Requirement | Amount | Weight |
|---|---|---|
| Existence Points (EP) | 2,000 | 50% |
| Consume [[Cryptid Insectoid Pupa]] | 3 | 50% |

### Getting Cryptid Insectoid Pupae

| Source | Chance | Notes |
|---|---|---|
| Breaking a Brown Mushroom in the Ancient Forest | 0.8% | Must be broken by a player. The pupa replaces the mushroom drop. |
| Breaking a [[Rotten Oak Log]] | 25% | Without Silk Touch. With Silk Touch, the log drops itself instead. |
| [[Pile of Rotten Logs]] chests | 4% per chest | 1 pupa |

> **Tip:** The best source is the [[Pile of Rotten Logs]]. About 10% of the oak logs in each pile are Rotten Oak Logs, and the chest can also contain a pupa. Watch out: 60% of piles spawn with 1 or 2 Phantaspores nearby.

The pupa can always be eaten, even with a full hunger bar, so you can consume all 3 at once. Each one gives **Nausea (10 s)** and **Poison I (5 s)**. Your Poison Resistance helps here.

---

## Where to Go Next

- [[Fungal Lineage]]: the full evolution tree and stats.
- [[Myconid Sprout]]: everything about the starting race.
- [[Cordyceptic Stalker]]: your next phase.
- [[Pile of Rotten Logs]]: where to farm pupae.
- [[Home]]
