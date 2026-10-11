# Genesis Mycoseraph

> *"The primordial mycelial seraph, origin and end of the forest."*

The **Genesis Mycoseraph** is the fifth and final phase of the [Fungal Lineage](Fungal-Lineage.md). Awakened as a True Demon Lord, the lich becomes a primordial seraph of mycelium: a being that is at once Majin, Divine and Spiritual. It can root its own rebirth into the soil, returning from a fatal blow in a burst of celestial light.

| | |
|---|---|
| **Race ID** | `fungalrebirth:genesis_mycoseraph` |
| **Phase** | 5 of 5 (final form) |
| **Type** | Majin, Divine, Spiritual |
| **Starting race** | No |
| **Evolves from** | [Myco-Lich Luminary](Myco-Lich-Luminary.md) |
| **Evolves into** | — |
| **Intrinsic Skill** | [Perennial Rebirth](Perennial-Rebirth.md) |

---

## Contents

- [Obtaining](#obtaining)
- [Stats](#stats)
- [Skills](#skills)
- [Resistances and Traits](#resistances-and-traits)
- [Strategy](#strategy)

---

## Obtaining

Evolve from a [Myco-Lich Luminary](Myco-Lich-Luminary.md). Each requirement counts for 50% of the evolution progress.

| Requirement | Amount | Weight |
|---|---|---|
| Existence Points (EP) | 2,000,000 | 50% |
| Awaken as a **True Demon Lord** | Awakened | 50% |

> **Note:** Only the **True Demon Lord** awakening is accepted. A **True Hero** awakening does **not** meet this requirement.

---

## Stats

| Stat | Value | Change from [Myco-Lich Luminary](Myco-Lich-Luminary.md) |
|---|---|---|
| Health | 1,099 | +611 |
| Spiritual Health | 6,099 | +4,635 |
| Magicules | 2,020,000 | +1,560,800 |
| Aura | 480,000 | +439,200 |
| Attack Damage | ×1.00 | Same |
| Movement Speed | ×1.10 | Up from ×1.00 |
| Height | 2 blocks | Same |
| Jump Height | 2 blocks | Same |

---

## Skills

### Intrinsic Skills

Unique skills from every phase are kept, so the Genesis Mycoseraph has all five.

| Skill | Gained at | Type |
|---|---|---|
| [Fungal Anatomy](Fungal-Anatomy.md) | Phase 1 | Toggle |
| [Spore Puppeteer](Spore-Puppeteer.md) | Phase 2 | Active, 2 modes |
| [Mycelial Reprisal](Mycelial-Reprisal.md) | Phase 3 | Active |
| [Twilight Moss](Twilight-Moss.md) | Phase 4 | Active (duration) |
| [Perennial Rebirth](Perennial-Rebirth.md) | **Phase 5** | Active |

### Perennial Rebirth

> *"Channel your sacred energy into the soil to mark it as your cradle of resurrection..."*

Perennial Rebirth is an active skill that must be placed on Tensura's ability bar. It lets you mark a block of soil as the place where you will be reborn after a fatal blow.

#### Marking the soil

Look at a **soil block** within reach (any dirt-type block, such as dirt, grass, podzol, mycelium, moss, mud or farmland) and press the skill key.

| Marking | Normal | Mastered |
|---|---|---|
| Magicule cost | 50,000 + 10% of your **max** Magicules | 50,000 + 5% of your **max** Magicules |
| Mastery | +1 per marked block | — |

While the mark is active:

- You show the [Perennial Rebirth (Effect)](Perennial-Rebirth-Effect.md) status icon.
- You see the marked block with a **golden outline**, even through walls.
- A [Golden Sprout](Golden-Sprout.md) grows on top of the marked block. It cannot be broken or collected, and it disappears with the mark.

Marking a different block moves the mark and charges the cost again. If you look at a block that is not soil, you see *"Nothing can be planted on this block."*

#### The rebirth

When you take a **fatal blow** while the mark is valid, the death is cancelled, like a Totem of Undying:

1. A **Celestial Burst** (a golden explosion) appears where you were struck.
2. You are **teleported on top of the marked block**, and the block breaks.
3. You return with restored resources and regeneration.

| Rebirth | Normal | Mastered |
|---|---|---|
| Health restored | 30% of max | 50% of max |
| Spiritual Health restored | 30% of max | 50% of max |
| Magicules restored | 30% of max | 50% of max |
| Regeneration (30 s) | Regeneration IV + Magicule Regeneration I | Regeneration V + Magicule Regeneration II |
| Cooldown after rebirth | 300 seconds | 150 seconds |

If you already have more than the restored amount, you keep your current value. The rebirth plays the Totem of Undying sound and particles.

#### Celestial Burst

| Celestial Burst | Normal | Mastered |
|---|---|---|
| Radius | 10 blocks | 10 blocks |
| Duration | 4 seconds | 4 seconds |
| Hits | 3 (at 0 s, 2 s and 4 s) | 3 |
| Damage per hit | 200 | 300 |
| Damage split | 45% Light, 45% Holy, 10% Severance | Same |

The burst only hits enemies. It looks like Tensura's *Hellfire* spell, recolored in gold.

#### Rules and limits

| Situation | What happens |
|---|---|
| Rebirth used | The mark is consumed. You must mark a new block after the cooldown. The next death without a mark is a normal death. |
| Shift + press while not looking at a block | Cancels the mark (*"Perennial Rebirth cancelled."*) and starts the cooldown |
| Pressing with an active mark while not looking at a block | Shows *"Already protected. Shift + press while not looking at a block to cancel."* |
| Marked block is broken or stops being soil | The mark disappears, with **no** cooldown |
| Changing dimension with an active mark | The mark is cancelled and the cooldown starts |
| Void damage or `/kill` | Not prevented |
| Holding a Totem of Undying | While the skill can save you, the totem is **not** consumed. If the skill can't act (cooldown, void, `/kill`, invalid block), the totem works normally. |
| Creative mode | No Magicule cost |

See [Perennial Rebirth](Perennial-Rebirth.md) for full details.

---

## Resistances and Traits

Resistances are cumulative, so every resistance from earlier phases is kept.

| Name | Type | Gained at |
|---|---|---|
| Poison Resistance | Resistance | Phase 1 |
| Abnormal Condition Resistance | Resistance | Phase 2 |
| Pain Resistance | Resistance | Phase 2 |
| Pain Nullification | Resistance | Phase 3 |
| Paralysis Resistance | Resistance | Phase 3 |
| Physical Attack Resistance | Resistance | Phase 3 |
| Pierce Attack Resistance | Resistance | Phase 3 |
| Darkness Attack Resistance | Resistance | Phase 4 |
| Light Attack Resistance | Resistance | Phase 4 |
| **Abnormal Condition Nullification** | Resistance | **Phase 5** |
| **Magic Resistance** | Resistance | **Phase 5** |
| **Spiritual Attack Resistance** | Resistance | **Phase 5** |
| **Holy Attack Resistance** | Resistance | **Phase 5** |
| Magicule Poison Immunity | Racial trait | All phases |

The Tensura skill **Poison**, learned as a Myconid Sprout, is also kept.

### Divine and Spiritual

The Genesis Mycoseraph is the only fungal race tagged as both **Divine** (yellow name) and **Spiritual**. Even so, it always keeps a **physical body**: it does not start in Spiritual Form, and if anything puts it into Spiritual Form, it is turned off right away.

---

## Strategy

- **Mark your soil before every big fight.** The rebirth is your safety net, and the Celestial Burst can turn a lost fight around by hitting everything near the spot where you fell.
- **Choose a safe block.** You return on top of the marked block with only part of your health, so mark somewhere enemies can't follow easily.
- **Protect the block.** If the marked block is broken, the mark is lost without warning in combat.
- **Don't change dimensions with a mark.** Doing so cancels the mark and starts the cooldown.
- **Keep your totem.** While Perennial Rebirth is ready, your Totem of Undying is saved for when the skill is on cooldown.

---

## See Also

- [Fungal Lineage](Fungal-Lineage.md)
- [Myco-Lich Luminary](Myco-Lich-Luminary.md)
- [Perennial Rebirth](Perennial-Rebirth.md)
- [Golden Sprout](Golden-Sprout.md)
- [Home](Home.md)
