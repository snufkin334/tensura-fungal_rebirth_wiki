# Spore Puppeteer

![Spore Puppeteer icon](link_da_imagem)

> *"Exhale parasitic spores into the body of a weakened creature. The spores only take root in wounded hosts of lesser existence: a battered mind is lulled into a docile stupor, while a host on the brink of collapse is wholly overtaken, fighting at your side until the spores devour it from within. Beings whose existence is utterly dwarfed by your own need not be wounded at all: they surrender to the spores the moment they touch them. Through Spore Strings, your will reaches every puppet nearby, driving them against the foe you set your eyes upon. Once mastered, the strings carry every command a hive could ever need."*

**Spore Puppeteer** is the Intrinsic Skill of the [[Cordyceptic Stalker]], the second phase of the [[Fungal Lineage]]. It infects weakened creatures with parasitic spores, turning them into temporary puppets or making them neutral. Its second mode, **Spore Strings**, commands those puppets.

| | |
|---|---|
| **Skill ID** | `fungalrebirth:cordyceptic_stalker_trait` |
| **Type** | Intrinsic Skill |
| **Activation** | Press (ability bar) |
| **Modes** | 2: *Default* and *Spore Strings* |
| **Granted by** | [[Cordyceptic Stalker]] (Phase 2) |
| **Kept in later phases** | Yes |
| **Magicule cost** | 80 + 40% of the target's EP (Default mode only) |
| **Cooldown** | 15 seconds (Default mode only) |

---

## Contents

- [Activation](#activation)
- [Mode 1: Default](#mode-1-default)
- [Puppets and Neutral Creatures](#puppets-and-neutral-creatures)
- [Mode 2: Spore Strings](#mode-2-spore-strings)
- [Mastery](#mastery)
- [Messages](#messages)

---

## Activation

Place the skill on Tensura's **ability bar** and press its key. Press **Alt + the skill key** to switch between the two modes.

---

## Mode 1: Default

Look at a living creature within **5 blocks**, with a clear line of sight, and press the skill key.

### Who can be infected

| Target | Can be infected? |
|---|---|
| Common mobs | Yes |
| Players | No |
| Bosses | No |
| Spiritual or divine creatures (such as daemons and spirits) | No |
| Creatures immune to mind control | No |
| Creatures that already have an owner (pets, other players' allies) | No |

### Result

First, the target's EP must be **below 50% of your EP**. Then its health decides the result:

| Target's EP (vs. yours) | Target's health | Result |
|---|---|---|
| 50% or more | Any | Fails (too strong) |
| Below 5% | Any | Becomes your **puppet** |
| 5% to below 50% | Below 25% | Becomes your **puppet** |
| 5% to below 50% | 25% to 50% | Becomes **neutral** |
| 5% to below 50% | Above 50% | Fails (too healthy) |

A creature whose existence is "utterly dwarfed" by yours (below 5% of your EP) surrenders at any health.

### Cost and cooldown

| | Normal | Mastered |
|---|---|---|
| Magicule cost | 80 + 40% of the target's EP | 80 + 30% of the target's EP |
| Cooldown | 15 seconds | 8 seconds |

- The cost is taken from your **current** Magicules.
- It is only paid on a **successful** use (puppet or neutral). Nothing is spent and no cooldown starts if the target is invalid.
- If you don't have enough Magicules, the skill fails with Tensura's standard message.

---

## Puppets and Neutral Creatures

| | Puppet | Neutral |
|---|---|---|
| Duration | 3 minutes (6 mastered) | 3 minutes |
| Healing | Recovers 40% of its max health (60% mastered) | None |
| Behavior | Becomes your temporary subordinate: follows you and fights for you | Stops targeting you and does not attack you |
| Can be named | No (*"A spore puppet has no name of its own."*) | Yes, with Tensura's normal rules |
| When the time runs out | **Dies**: the spores devour it from within | Returns to normal |

- Puppets use Tensura's ownership system, so they show you as their owner, like any Tensura ally.
- The timer is saved on the creature itself, so it keeps counting even if you log out or the chunk unloads.
- Puppets count as allies for the addon's area skills, so they are not hurt by [[Mycelial Reprisal]] or the Celestial Burst of [[Perennial Rebirth]], and they receive the buffs of [[Twilight Moss]].

---

## Mode 2: Spore Strings

Spore Strings link you to your puppets within **32 blocks**. They work like Tensura's *Thought Communication*, but only for your own puppets. This mode has **no cost and no cooldown**.

### Not mastered

| Action | Result |
|---|---|
| Press while looking at a creature (up to 24 blocks) | All nearby puppets attack it, and stop staying in place if they were |

### Mastered

When Spore Puppeteer is mastered, Spore Strings gain every command of Thought Communication:

| Action | Result |
|---|---|
| Press while looking at a creature | All nearby puppets attack it |
| Press while looking at a puppet | Cycles **that puppet's** movement: Follow, Wander, Stay |
| Shift + press while looking at a puppet | Cycles **that puppet's** behavior: Passive, Aggressive, Protect, Neutral |
| Press without looking at anyone | Cycles the movement of **all** puppets: Follow, Wander, Stay |
| Shift + press without looking at a puppet | Cycles the behavior of **all** puppets: Passive, Aggressive, Protect, Neutral |

> **Note:** Movement and behavior orders use Tensura's subordinate system, which only Tensura creatures have. Vanilla puppets (zombies, spiders and others) only obey the attack order.

---

## Mastery

| Mastery | Value |
|---|---|
| Gain | +1 per successful use of the Default mode |
| Spore Strings | Does not give mastery |

| Upgrade when mastered | Normal | Mastered |
|---|---|---|
| Puppet duration | 3 minutes | 6 minutes |
| Puppet healing | 40% | 60% |
| EP part of the cost | 40% | 30% |
| Cooldown | 15 seconds | 8 seconds |
| Spore Strings | Attack order only | All orders |

---

## Messages

| Situation | Message |
|---|---|
| No creature in range | *Your spores find no host nearby.* |
| Invalid target | *This creature's mind rejects your spores.* |
| Target already has an owner | *This creature already bends to another will.* |
| Target's EP is too high | *This creature's existence is too strong for your spores to take root.* |
| Target's health is too high | *This creature is still too vigorous. Weaken it first.* |
| Target becomes neutral | *(Name) sinks into a spore-induced stupor.* |
| Target becomes a puppet | *(Name) is now your spore puppet.* |
| Strings: no target | *Look at a creature for your puppets to hunt.* |
| Strings: no puppets nearby | *None of your spore puppets can feel your strings from here.* |
| Strings: invalid target | *Your puppets will not turn against that one.* |
| Strings: attack | *Your puppets lunge at (Name).* |
| Strings: Follow / Wander / Stay | *Your puppets crawl after you.* / *Your puppets drift off to roam.* / *Your puppets root themselves in place.* |
| Strings: Passive / Aggressive / Protect / Neutral | *Your puppets fall docile and will not fight.* / *Your puppets hunger for any foe in sight.* / *Your puppets stand guard around you.* / *Your puppets will only strike back.* |
| Strings: order not supported | *This puppet's mind is too simple for such an order.* |

---

## See Also

- [[Cordyceptic Stalker]]
- [[Fungal Lineage]]
- [[Fungal Anatomy]]
- [[Mycelial Reprisal]]
- [[Home]]
