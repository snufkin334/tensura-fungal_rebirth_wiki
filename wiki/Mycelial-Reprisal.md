# Mycelial Reprisal

![Mycelial Reprisal icon](link_da_imagem)

> *"Plant your massive frame into the soil to absorb incoming kinetic energy, releasing it in a devastating eruption."*

**Mycelial Reprisal** is the Intrinsic Skill of the [[Mycelial Dreadnought]], the third phase of the [[Fungal Lineage]]. The user roots itself into the ground, turns part of every blow it takes into stored energy, and then releases it all as a shockwave.

| | |
|---|---|
| **Skill ID** | `fungalrebirth:mycelial_dreadnought_trait` |
| **Type** | Intrinsic Skill |
| **Activation** | Press (ability bar), two steps |
| **Granted by** | [[Mycelial Dreadnought]] (Phase 3) |
| **Kept in later phases** | Yes |
| **Magicule cost** | 5,000 (when rooting) |
| **Cooldown** | 40 seconds (after release) |

---

## Contents

- [Activation](#activation)
- [Step 1: Rooted](#step-1-rooted)
- [Step 2: Release](#step-2-release)
- [Cost and Cooldown](#cost-and-cooldown)
- [Mastery](#mastery)
- [Notes](#notes)

---

## Activation

Place the skill on Tensura's **ability bar**.

1. **First press:** you become **Rooted** (Step 1).
2. **Second press**, or after **10 seconds**: the stored energy is released (Step 2).

---

## Step 1: Rooted

You plant yourself into the ground for up to **10 seconds**. The message *"Rooted! Absorbing kinetic energy..."* appears. While rooted, the action bar shows *"Kinetic Spore Energy: X/Y (Zs)"*.

| While rooted | Normal | Mastered |
|---|---|---|
| Movement | Speed, jump and knockback are set to zero | Same |
| Effects | Resistance II | Resistance III + Regeneration II |
| Damage absorbed | **35%** of every hit | **45%** of every hit |
| Max Kinetic Spore Energy | 200 | 400 |

- The absorbed part of each hit is **cancelled** and added to your **Kinetic Spore Energy**.
- Absorption happens **before** armor and resistances are applied.
- When the energy is full, hits are still reduced by the same percentage, but no more energy is stored.
- Damage that bypasses invulnerability (such as `/kill` or the void) is not absorbed.
- The rooted state is saved on the player, so it continues if you log out and back in.

---

## Step 2: Release

The roots break and **all** stored energy erupts as a shockwave around you.

| Shockwave | Normal | Mastered |
|---|---|---|
| Damage to each enemy | Equal to the stored energy (max 200) | Equal to the stored energy (max 400) |
| Radius | 10 blocks | 15 blocks |
| Knockback | Knockback IV | Knockback IV |

- The rooted state ends **before** the damage is dealt, so the shockwave never absorbs itself.
- The **knockback** is applied even with 0 stored energy, so the release can be used just to push enemies away.
- Only **enemies** are hit. You, your teammates, Tensura allies and subordinates, your pets and your [[Spore Puppeteer]] puppets are not affected.
- The release triggers a Tensura **screen shake**, an explosion sound, and a burst of orange spores.

---

## Cost and Cooldown

| | Normal | Mastered |
|---|---|---|
| Magicule cost | 5,000 | 7,500 |
| When it is paid | When rooting (the release is free) | Same |
| Cooldown | 40 seconds | 30 seconds |
| When the cooldown starts | On release (manual or automatic) | Same |

> **Note:** The mastered version costs **more** Magicules, but in exchange it absorbs more damage, stores twice the energy, reaches farther and recharges faster.

---

## Mastery

| Mastery | Value |
|---|---|
| Gain | +1 per release |

| Upgrade when mastered | Normal | Mastered |
|---|---|---|
| Effects while rooted | Resistance II | Resistance III + Regeneration II |
| Damage absorbed | 35% | 45% |
| Max energy (and max damage) | 200 | 400 |
| Shockwave radius | 10 blocks | 15 blocks |
| Cooldown | 40 seconds | 30 seconds |
| Magicule cost | 5,000 | 7,500 |

---

## Notes

- The highest possible shockwave damage is 200 (400 mastered). To reach it, you must take about 572 damage while rooted (about 889 mastered) before armor and resistances.
- Rooting yourself inside your own [[Twilight Moss]] combines both skills well: enemies attacking you take Darkness damage while they charge your shockwave.

---

## See Also

- [[Mycelial Dreadnought]]
- [[Fungal Lineage]]
- [[Spore Puppeteer]]
- [[Twilight Moss]]
- [[Home]]
