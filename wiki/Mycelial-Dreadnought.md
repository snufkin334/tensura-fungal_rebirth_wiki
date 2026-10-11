# Mycelial Dreadnought

> *"A colossal mass of armored mycelium. Slow, but nearly unstoppable."*

The **Mycelial Dreadnought** is the third phase of the [Fungal Lineage](Fungal-Lineage.md). The stalker has grown into a towering mass of armored mycelium. It gives up speed and agility in exchange for a huge jump in health and a wall of physical resistances, and it can root itself into the ground to turn incoming blows into a devastating shockwave.

| | |
|---|---|
| **Race ID** | `fungalrebirth:mycelial_dreadnought` |
| **Phase** | 3 of 5 |
| **Type** | Majin |
| **Starting race** | No |
| **Evolves from** | [Cordyceptic Stalker](Cordyceptic-Stalker.md) |
| **Evolves into** | [Myco-Lich Luminary](Myco-Lich-Luminary.md) |
| **Intrinsic Skill** | [Mycelial Reprisal](Mycelial-Reprisal.md) |

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

Evolve from a [Cordyceptic Stalker](Cordyceptic-Stalker.md). Each requirement counts for 50% of the evolution progress.

| Requirement | Amount | Weight |
|---|---|---|
| Existence Points (EP) | 88,000 | 50% |
| Master the skill *Strengthen Body* | Mastered | 50% |

> **Note:** Just having *Strengthen Body* is not enough. The skill must be **mastered**.

---

## Stats

| Stat | Value | Change from [Cordyceptic Stalker](Cordyceptic-Stalker.md) |
|---|---|---|
| Health | 225 | +200 |
| Spiritual Health | 675 | +600 |
| Magicules | 107,200 | +100,400 |
| Aura | 12,800 | +12,620 |
| Attack Damage | ×1.00 | Up from ×0.80 |
| Movement Speed | ×0.85 | Down from ×1.05 |
| Height | 2 blocks | Up from 1 block |
| Jump Height | Vanilla (~1.25 blocks) | Down from 3 blocks |

The Dreadnought is the slowest phase of the lineage and the only one with a normal Minecraft jump.

---

## Skills

### Intrinsic Skills

Unique skills from earlier phases are kept.

| Skill | Gained at | Type |
|---|---|---|
| [Fungal Anatomy](Fungal-Anatomy.md) | Phase 1 | Toggle |
| [Spore Puppeteer](Spore-Puppeteer.md) | Phase 2 | Active, 2 modes |
| [Mycelial Reprisal](Mycelial-Reprisal.md) | **Phase 3** | Active |

### Mycelial Reprisal

> *"Plant your massive frame into the soil to absorb incoming kinetic energy, releasing it in a devastating eruption."*

Mycelial Reprisal is an active skill that must be placed on Tensura's ability bar. It works in two steps.

#### Step 1: Root (first press)

You become **Rooted** for up to **10 seconds**. The message *"Rooted! Absorbing kinetic energy..."* appears, and a counter on the action bar shows your stored energy and remaining time.

| While rooted | Normal | Mastered |
|---|---|---|
| Movement | You cannot move, jump or be knocked back | Same |
| Effects | Resistance II | Resistance III + Regeneration II |
| Damage absorbed | 35% of all incoming damage | 45% of all incoming damage |
| Max Kinetic Spore Energy | 200 | 400 |

The absorbed part of each hit is cancelled and stored as **Kinetic Spore Energy**. Absorption happens before armor and resistances. Once the energy is full, hits are still reduced by the same amount, but no more energy is stored. Damage that bypasses invulnerability (such as `/kill` or the void) is not absorbed.

#### Step 2: Release (second press, or after 10 seconds)

The roots break and all stored energy is released as a **shockwave** around you.

| Shockwave | Normal | Mastered |
|---|---|---|
| Damage to each enemy | Equal to the stored energy (up to 200) | Equal to the stored energy (up to 400) |
| Radius | 10 blocks | 15 blocks |
| Knockback | Knockback IV | Knockback IV |
| Other effects | Tensura screen shake, explosion sound and orange spores | Same |

The knockback is applied even with 0 stored energy, so you can use the skill just to push enemies away. Allies, pets, teammates and your spore puppets are not hit.

| Cost and cooldown | Normal | Mastered |
|---|---|---|
| Magicule cost | 5,000 (paid when rooting) | 7,500 (paid when rooting) |
| Cooldown | 40 seconds | 30 seconds |
| Mastery | +1 per release | — |

The cooldown starts when the energy is released, whether you press the key again or the 10 seconds run out.

See [Mycelial Reprisal](Mycelial-Reprisal.md) for full details.

---

## Resistances and Traits

Resistances are cumulative, so every resistance from earlier phases is kept.

| Name | Type | Gained at |
|---|---|---|
| Poison Resistance | Resistance | Phase 1 |
| Abnormal Condition Resistance | Resistance | Phase 2 |
| Pain Resistance | Resistance | Phase 2 |
| **Pain Nullification** | Resistance | **Phase 3** |
| **Paralysis Resistance** | Resistance | **Phase 3** |
| **Physical Attack Resistance** | Resistance | **Phase 3** |
| **Pierce Attack Resistance** | Resistance | **Phase 3** |
| Magicule Poison Immunity | Racial trait | All phases |

The Tensura skill **Poison**, learned as a Myconid Sprout, is also kept.

---

## Racial Mechanics

### No more Sprout Stealth

At 2 blocks tall, the Dreadnought can no longer hide in tall grass. [Sprout Stealth](Sprout-Stealth.md) stops working as soon as you evolve into this phase.

---

## Evolution

| Evolves into | Requirement 1 (50%) | Requirement 2 (50%) |
|---|---|---|
| [Myco-Lich Luminary](Myco-Lich-Luminary.md) | 400,000 EP | Master 6 spells of the **Aspectual**, **Spiritual** or **Summoning** type |

> **Note:** Every spell of those types that is already mastered counts, even ones mastered before this phase. Miscellaneous spells do not count. If you forget a spell, it stops counting. The evolution screen shows your progress as *X/6*.

---

## Strategy

- **Root into big hits.** Activate Mycelial Reprisal right before a strong enemy attacks. Every hit you take while rooted charges the shockwave and hurts you less.
- **Surround yourself first.** The shockwave hits every enemy in range for the full stored energy, so it is strongest against groups.
- **Use it as a panic button.** Even with no energy stored, the release pushes enemies away with Knockback IV.
- **Mind the cost.** Each activation costs 5,000 Magicules (7,500 when mastered), which is a large part of your 107,200 pool.
- **Start learning spells early.** The next evolution needs 6 mastered Aspectual, Spiritual or Summoning spells, and spells mastered now already count.

---

## See Also

- [Fungal Lineage](Fungal-Lineage.md)
- [Cordyceptic Stalker](Cordyceptic-Stalker.md)
- [Myco-Lich Luminary](Myco-Lich-Luminary.md)
- [Mycelial Reprisal](Mycelial-Reprisal.md)
- [Home](Home.md)
