# Cordyceptic Stalker

![Cordyceptic Stalker](link_da_imagem)

> *"A spore-driven predator that feels no pain and hunts from the shadows."*

The **Cordyceptic Stalker** is the second phase of the [[Fungal Lineage]]. The fragile sprout has become a parasitic hunter: it no longer depends on the Ancient Forest, it barely feels pain, and it can infect weakened creatures with its spores to turn them into puppets that fight for it.

| | |
|---|---|
| **Race ID** | `fungalrebirth:cordyceptic_stalker` |
| **Phase** | 2 of 5 |
| **Type** | Majin |
| **Starting race** | No |
| **Evolves from** | [[Myconid Sprout]] |
| **Evolves into** | [[Mycelial Dreadnought]] |
| **Intrinsic Skill** | [[Spore Puppeteer]] |

![Cordyceptic Stalker race icon](link_da_imagem)

---

## Contents

- [Obtaining](#obtaining)
- [Stats](#stats)
- [Skills](#skills)
- [Resistances and Traits](#resistances-and-traits)
- [Racial Mechanics](#racial-mechanics)
- [Evolution](#evolution)
- [Strategy](#strategy)

---

## Obtaining

Evolve from a [[Myconid Sprout]]. Each requirement counts for 50% of the evolution progress.

| Requirement | Amount | Weight |
|---|---|---|
| Existence Points (EP) | 2,000 | 50% |
| Consume [[Cryptid Insectoid Pupa]] | 3 | 50% |

Once you evolve, [[Spore Deprived]] is removed and no longer applies: the Stalker can roam outside the Ancient Forest freely.

---

## Stats

| Stat | Value | Change from [[Myconid Sprout]] |
|---|---|---|
| Health | 25 | +17 |
| Spiritual Health | 75 | +51 |
| Magicules | 6,800 | Fixed (was 400 – 600) |
| Aura | 180 | Fixed (was 10 – 20) |
| Attack Damage | ×0.80 | Up from ×0.50 |
| Movement Speed | ×1.05 | Down from ×1.10 |
| Height | 1 block | Up from 2/3 of a block |
| Jump Height | 3 blocks | Same |

---

## Skills

### Intrinsic Skills

Unique skills from earlier phases are kept.

| Skill | Gained at | Type |
|---|---|---|
| [[Fungal Anatomy]] | Phase 1 | Toggle |
| [[Spore Puppeteer]] | **Phase 2** | Active, 2 modes |

### Spore Puppeteer

> *"Exhale parasitic spores into the body of a weakened creature. The spores only take root in wounded hosts of lesser existence..."*

Spore Puppeteer is an active skill that must be placed on Tensura's ability bar. It has **two modes**; press **Alt + the skill key** to switch between them.

#### Mode 1: Default (infect)

Look at a living creature within **5 blocks** and press the skill key. The result depends on the target's EP and health:

| Target's EP (vs. yours) | Target's health | Result |
|---|---|---|
| 50% or more | Any | Fails: *"too strong for your spores"* |
| Below 5% | Any | Becomes your **puppet** |
| 5% to below 50% | Below 25% | Becomes your **puppet** |
| 5% to below 50% | 25% to 50% | Becomes **neutral** to you for 3 minutes |
| 5% to below 50% | Above 50% | Fails: *"still too vigorous"* |

| Outcome | Normal | Mastered |
|---|---|---|
| **Puppet** duration | 3 minutes | 6 minutes |
| Puppet heals | 40% of its max health | 60% of its max health |
| After the duration | The spores consume the puppet and it dies | Same |
| **Neutral** duration | 3 minutes (no healing) | 3 minutes |

A puppet becomes your temporary subordinate: it follows and defends you like any Tensura ally. Puppets **cannot be named**, since they are going to die. Neutral creatures stop targeting you and can still be named normally.

**Cannot be infected:** players, bosses, spiritual or divine creatures (such as daemons and spirits), creatures immune to mind control, and creatures that already have an owner.

| Cost and cooldown | Normal | Mastered |
|---|---|---|
| Magicule cost | 80 + 40% of the target's EP | 80 + 30% of the target's EP |
| Cooldown | 15 seconds | 8 seconds |
| Mastery | +1 per successful use | — |

The cost is taken from your current Magicules and is only paid on a successful use (puppet or neutral). Nothing is spent if the target is invalid.

#### Mode 2: Spore Strings (command)

Spore Strings link you to your puppets within **32 blocks**. It works like Tensura's *Thought Communication*, but only for your own puppets. It has **no cost and no cooldown**, and it does not give mastery.

| Action | Not mastered | Mastered |
|---|---|---|
| Press while looking at a creature (up to 24 blocks) | All nearby puppets attack it | Same |
| Press while looking at a puppet | — | Cycles that puppet's movement: Follow, Wander, Stay |
| Shift + press while looking at a puppet | — | Cycles that puppet's behavior: Passive, Aggressive, Protect, Neutral |
| Press without looking at anyone | — | Cycles the movement of all puppets |
| Shift + press without looking at a puppet | — | Cycles the behavior of all puppets |

> **Note:** Movement and behavior orders use Tensura's subordinate system, which only exists on Tensura creatures. Vanilla puppets (zombies, spiders and others) only obey the attack order. When this happens, you see the message *"This puppet's mind is too simple for such an order."*

See [[Spore Puppeteer]] for full details.

---

## Resistances and Traits

| Name | Type | Description |
|---|---|---|
| Abnormal Condition Resistance | Resistance | New at this phase |
| Poison Resistance | Resistance | Kept from Phase 1 |
| Pain Resistance | Resistance | New at this phase. Pain Nullification is added on top of it in Phase 3. |
| Magicule Poison Immunity | Racial trait | Shared by every fungal race |

The Tensura skill **Poison**, learned as a Myconid Sprout, is also kept.

---

## Racial Mechanics

### Sprout Stealth

The Stalker is still only 1 block tall, so it keeps [[Sprout Stealth]]. While its body is inside **tall grass** or a **large fern**, creatures that have not noticed it only notice it within **4 blocks**, and hostile creatures lose track of it beyond **8 blocks**. This mechanic stops working when you evolve into a [[Mycelial Dreadnought]].

### No more Spore Deprivation

Unlike the [[Myconid Sprout]], the Stalker does **not** receive [[Spore Deprived]] outside the Ancient Forest.

---

## Evolution

| Evolves into | Requirement 1 (50%) | Requirement 2 (50%) |
|---|---|---|
| [[Mycelial Dreadnought]] | 88,000 EP | Master the skill *Strengthen Body* |

> **Note:** Having *Strengthen Body* is not enough: it must be **mastered**.

---

## Strategy

- **Weaken first, infect second.** Bring a target below 25% health to turn it into a puppet. Creatures between 25% and 50% only become neutral.
- **Pick targets wisely.** The cost scales with the target's EP. A target with very low EP compared to yours (below 5%) can be infected at any health, and it also costs very little.
- **Puppets are disposable.** They die when the spores run out, so use them as shields and damage dealers rather than long-term companions.
- **Prefer Tensura creatures as puppets.** Only they accept movement and behavior orders from Spore Strings.
- **Grow your EP.** You need 88,000 EP for the next evolution, which is a big jump from 2,000.

---

## See Also

- [[Fungal Lineage]]
- [[Myconid Sprout]]
- [[Mycelial Dreadnought]]
- [[Spore Puppeteer]]
- [[Home]]
