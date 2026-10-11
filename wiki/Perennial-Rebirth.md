# Perennial Rebirth

> *"Channel your sacred energy into the soil to mark it as your cradle of resurrection. The chosen earth will glow with a golden aura, blessing you with the promise of Perennial Rebirth. If struck by a fatal blow, your body will unleash a devastating shockwave of celestial energy that scorches nearby enemies. Instead of dying, you will instantly bloom from the marked soil, shattering the ground beneath you as you return with a surge of radiant vitality."*

**Perennial Rebirth** is the Intrinsic Skill of the [Genesis Mycoseraph](Genesis-Mycoseraph.md), the final phase of the [Fungal Lineage](Fungal-Lineage.md). The user marks a block of soil as its cradle of resurrection. When struck by a fatal blow, it releases a burst of celestial energy and is reborn from the marked soil instead of dying.

| | |
|---|---|
| **Skill ID** | `fungalrebirth:genesis_mycoseraph_trait` |
| **Type** | Intrinsic Skill |
| **Activation** | Press (ability bar) |
| **Granted by** | [Genesis Mycoseraph](Genesis-Mycoseraph.md) (Phase 5) |
| **Magicule cost** | 50,000 + 10% of max Magicules (per mark) |
| **Cooldown** | 300 seconds (after rebirth or cancel) |

---

## Contents

- [Activation](#activation)
- [Marking the Soil](#marking-the-soil)
- [The Rebirth](#the-rebirth)
- [Celestial Burst](#celestial-burst)
- [Cancelling and Losing the Mark](#cancelling-and-losing-the-mark)
- [Totem of Undying](#totem-of-undying)
- [Mastery](#mastery)
- [Messages](#messages)

---

## Activation

Place the skill on Tensura's **ability bar**.

| Action | Result |
|---|---|
| Press while looking at a soil block | Marks that block |
| Shift + press while not looking at any block (with an active mark) | Cancels the mark |
| Press while not looking at any block (with an active mark) | Shows how to cancel |

---

## Marking the Soil

Look at a **soil block** within reach and press the skill key. Valid blocks are any **dirt-type** block (such as dirt, grass, podzol, mycelium, moss, mud and rooted dirt) and **farmland**.

| | Normal | Mastered |
|---|---|---|
| Magicule cost | 50,000 + 10% of your **max** Magicules | 50,000 + 5% of your **max** Magicules |

- The cost is taken from your **current** Magicules. It is the same every time; it does not get cheaper with repeated use.
- Marking another block **moves** the mark and charges the cost again.
- In **Creative** mode there is no Magicule cost.

### While the mark is active

- You show the [Perennial Rebirth (Effect)](Perennial-Rebirth-Effect.md) status icon.
- You see the marked block with a **golden outline**, visible **through walls**.
- A [Golden Sprout](Golden-Sprout.md) grows on top of the marked block. It gives off light level 6, cannot be broken in Survival, has no item and drops nothing. It disappears together with the mark.

---

## The Rebirth

When you take a **fatal blow** while your mark is valid, your death is cancelled, like a Totem of Undying:

1. A **Celestial Burst** erupts at the spot where you were struck.
2. You are **teleported** on top of the marked block, and the block **breaks**.
3. You are restored and receive regeneration.
4. The Totem of Undying sound and particles play.

| Rebirth | Normal | Mastered |
|---|---|---|
| Health | 30% of max | 50% of max |
| Spiritual Health | 30% of max | 50% of max |
| Magicules | 30% of max | 50% of max |
| Regeneration for 30 seconds | Regeneration IV + Magicule Regeneration I | Regeneration V + Magicule Regeneration II |
| Cooldown | 300 seconds | 150 seconds |

- If you already have more than the restored amount, you keep your current value.
- The mark is **consumed** by the rebirth. The next death without a new mark is a normal death.
- **Void damage** and `/kill` cannot be prevented.

---

## Celestial Burst

The Celestial Burst is a golden sphere of celestial energy left at the spot of the fatal blow. It looks like Tensura's *Hellfire* spell, recolored in gold and yellow.

| Celestial Burst | Normal | Mastered |
|---|---|---|
| Radius | 10 blocks | 10 blocks |
| Duration | 4 seconds | 4 seconds |
| Hits | 3 (at 0, 2 and 4 seconds) | 3 |
| Damage per hit | 200 | 300 |
| Maximum total damage | 600 | 900 |

Each hit is split into three damage types, all dealt at once:

| Damage type | Share | Per hit (normal) | Per hit (mastered) |
|---|---|---|---|
| Light | 45% | 90 | 135 |
| Holy | 45% | 90 | 135 |
| Severance | 10% | 20 | 30 |

The burst only hits **enemies**. You, your teammates, Tensura allies and subordinates, your pets and your [Spore Puppeteer](Spore-Puppeteer.md) puppets are not affected.

---

## Cancelling and Losing the Mark

| Situation | Result | Cooldown? |
|---|---|---|
| Shift + press while not looking at a block | Mark cancelled (*"Perennial Rebirth cancelled."*) | Yes |
| Changing dimension with an active mark | Mark cancelled; the block is not affected | Yes |
| Marked block broken, replaced or no longer soil | Mark disappears | No |
| Rebirth used | Mark consumed | Yes |

The mark is saved on the player, so it survives logging out and back in.

---

## Totem of Undying

While Perennial Rebirth can save you, a Totem of Undying in your hand is **ignored and not consumed**: the skill saves you instead.

If the skill **cannot** act (it is on cooldown, the damage comes from the void or `/kill`, or the mark is no longer valid), the totem works normally.

---

## Mastery

| Mastery | Value |
|---|---|
| Gain | +1 per marked block |

| Upgrade when mastered | Normal | Mastered |
|---|---|---|
| Mark cost | 50,000 + 10% of max Magicules | 50,000 + 5% of max Magicules |
| Health, Spiritual Health and Magicules restored | 30% | 50% |
| Regeneration | IV | V |
| Magicule Regeneration | I | II |
| Celestial Burst damage per hit | 200 | 300 |
| Cooldown | 300 seconds | 150 seconds |

---

## Messages

| Situation | Message |
|---|---|
| Looking at a block that is not soil | *Nothing can be planted on this block.* |
| Pressing with an active mark while not looking at a block | *Already protected. Shift + press while not looking at a block to cancel.* |
| Mark cancelled | *Perennial Rebirth cancelled.* |

Other outcomes are signaled only by sound.

---

## See Also

- [Genesis Mycoseraph](Genesis-Mycoseraph.md)
- [Fungal Lineage](Fungal-Lineage.md)
- [Golden Sprout](Golden-Sprout.md)
- [Perennial Rebirth (Effect)](Perennial-Rebirth-Effect.md)
- [Home](Home.md)
