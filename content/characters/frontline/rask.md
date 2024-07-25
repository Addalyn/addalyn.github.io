+++
archetype = "frontline"
title = "Rask"
+++

**Short Description:** A plasma-fueled, hybrid beast who thrives in the thick of battle.

| **Role**          | Frontline |
| ----------------- | --------- |
| **Affiliation**   | Evos      |
| **Actual Health** | 200       |

| **Stat**   | **Value**                                                 |
| ---------- | --------------------------------------------------------- |
| Health     | {{< stat-bar color="green" percentage="80" value="8" >}}  |
| Damage     | {{< stat-bar color="red" percentage="40" value="4" >}}    |
| Survival   | {{< stat-bar color="blue" percentage="80" value="8" >}}   |
| Difficulty | {{< stat-bar color="orange" percentage="40" value="4" >}} |

## Abilities

### Ability 1: Maul

- **Phase:** Blast
- **Cooldown:** None
- **Free:** No
- **Description:** Claw your enemies, doing 30 direct damage to those adjacent to you, and 25 direct damage to those farther away.
- **Energy Gained:** Gain 8 energy per enemy hit.
- **Target Type:** Free aim
- **Target Range:** 1
- **Area of Effect:** Cone

| **Mod Name**    | **Description**                                                                           | **Cost** | **Type**   |
| --------------- | ----------------------------------------------------------------------------------------- | -------- | ---------- |
| Primal Fury     | Generate an additional 3 energy on near targets and 1 energy on far targets.              | 1        | Damage Up  |
| Crippling Slash | Adjacent enemies hit are slowed for the turn.                                             | 2        | Bad Status |
| Shredding Steel | Cover damage reduction is halved.                                                         | 2        | Damage Up  |
| Beastial        | Near enemies take an additional 1 damage and further enemies take an additional 3 damage. | 3        | Damage Up  |

**Default Mod:** Crippling Slash

---

### Ability 2: Upheaval

- **Phase:** Blast
- **Cooldown:** 4
- **Free:** No
- **Description:** Knockback an enemy, dealing 25 direct damage. Move cursor in or out to adjust knockback distance.
- **Energy Gained:** Gain 10 energy if you hit an enemy.
- **Target Type:** Free aim
- **Target Range:** 7
- **Area of Effect:** Line

| **Mod Name** | **Description**                                | **Cost** | **Type**        |
| ------------ | ---------------------------------------------- | -------- | --------------- |
| Power Ripple | Gain 6 additional energy if you hit an enemy.  | 1        | Energy          |
| Fling        | Increases range by 1 and knockback range by 1. | 2        | Range Up        |
| Aftershock   | Affects all targeted enemies.                  | 3        | Target Increase |
| Ravage       | Deals an additional 10 damage.                 | 3        | Damage Up       |

**Default Mod:** Fling

---

### Ability 3: Pain Train

- **Phase:** Dash
- **Cooldown:** 4
- **Free:** No
- **Description:** Trample over enemies, dealing 25 direct damage.
- **Energy Gained:** Gain 8 energy per enemy hit.
- **Target Type:** Free aim
- **Target Range:** 7
- **Area of Effect:** Cone

| **Mod Name**      | **Description**                                | **Cost** | **Type**        |
| ----------------- | ---------------------------------------------- | -------- | --------------- |
| Mad Dash          | Increases damage at the landing location by 3. | 1        | Damage Up       |
| Pounce            | Gain 4 additional Energy per target hit.       | 2        | Energy          |
| Surge             | Increases range by 1.                          | 2        | Target Increase |
| Trample Underfoot | Enemies hit are slowed for the turn.           | 3        | Bad Status      |

**Default Mod:** Trample Underfoot

---

### Ability 4: Augmented Regeneration

- **Phase:** Prep
- **Cooldown:** 8
- **Free:** Yes
- **Description:** Gain 10 health per turn if over 60 health. Activate when at 65 or less health to gain 15 health per turn instead. Lasts 2 turns.
- **Energy Gained:** Gain 5 energy.
- **Target Type:** Self

| **Mod Name**     | **Description**                                                                         | **Cost** | **Type**    |
| ---------------- | --------------------------------------------------------------------------------------- | -------- | ----------- |
| Unrelenting      | Gain Unstoppable for the turn.                                                          | 1        | Good Status |
| Pain Tolerance   | Increases the threshold to 90 health.                                                   | 2        | Special     |
| Quick Mend       | Gain all health over one turn, 20 health if above the threshold, or 30 health if below. | 2        | Special     |
| Shielding Factor | Gain 15 shields on use.                                                                 | 3        | Shield Up   |

**Default Mod:** Pain Tolerance

---

### Ability 5: Uncontrollable Fury

- **Phase:** Blast
- **Energy Cost:** Activation Cost: 100 energy
- **Description:** Automatically activates at full energy, resetting all cooldowns and creating a zone of plasma that deals 20 indirect damage and lasts for 2 turns.  
  **Passive:** Gain energy when damaged.
- **Free:** Yes
- **Target Type:** Area of Effect
- **Target Range:** 7
- **Area of Effect:** Zone

| **Mod Name**      | **Description**                                      | **Cost** | **Type**    |
| ----------------- | ---------------------------------------------------- | -------- | ----------- |
| Rejuvenating Rage | Gain 10 health.                                      | 1        | Shield Up   |
| Controllable Fury | No longer triggers automatically.                    | 2        | Special     |
| Driving Rage      | Grants Unstoppable and Haste until end of next turn. | 2        | Good Status |
| Fueled by Rage    | Grants Might for the next 2 turns.                   | 3        | Good Status |

**Default Mod:** Driving Rage

## Dossier

**SKILLS:** Clinical Exobiology, preening.

**KNOWN FOR:** EvoS' crowning achievement.

**ORIGINS:** Evolution Solutions Birthing Vats.

Evolution Solutions is tight-lipped about their crowning achievement's inception. Despite the hybrid beast's enviable mass market popularity, only a handful of people know Rask's true origins. Conspiracy theorists have spread tales of a nightmarish production that cost thousands of lives, millions of ISO, and left the Depths in disrepair. But since when have rumors stopped Rask Plushies from flying off the shelves?

Rask's "Power Juice" flows through his body at all times. Despite its branding, its chemical makeup is fully unique from the Rask drink that shares its name. Which is good. Because that would be gross.

## Story

**Friends:**

- **Quark:** Rask doesn't understand a word Quark says, but it generally accompanies heals.
- **Phaedra:** A distant plasma-relation exists between the two.

**Rivals:**

- **Grey:** He has a feeling she doesn't like him.
