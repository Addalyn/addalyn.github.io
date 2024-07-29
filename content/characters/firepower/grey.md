+++
archetype = "home"
title = "Grey"
+++

**Short Description:** Champion Tracker with a family fortune she uses to fund her Hunts.

| **Role**          | Firepower |
| ----------------- | --------- |
| **Affiliation**   | Wildcard  |
| **Actual Health** | 120       |

| **Stat**   | **Value**                                                 |
| ---------- | --------------------------------------------------------- |
| Health     | {{< stat-bar color="green" percentage="20" value="2" >}}  |
| Damage     | {{< stat-bar color="red" percentage="70" value="7" >}}    |
| Survival   | {{< stat-bar color="blue" percentage="50" value="5" >}}   |
| Difficulty | {{< stat-bar color="orange" percentage="50" value="5" >}} |

## Abilities

### Ability 1: Tracer Bolt

- **Phase:** Blast
- **Cooldown:** None
- **Free:** No
- **Description:** Deals 34 direct damage and tracks the target for 2 turns. Tracked targets are revealed.
- **Energy Gained:** Gain 12 energy if you hit an enemy.
- **Target Type:** Free aim
- **Target Range:** 7

| **Mod Name**       | **Description**                                                                            | **Cost** | **Type**        |
| ------------------ | ------------------------------------------------------------------------------------------ | -------- | --------------- |
| High-Powered Bolts | Pierce enemies but only deal damage to the initial target. Subsequent enemies are tracked. | 1        | Target Increase |
| Barbed Tip         | Increases energy gained by 3.                                                              | 2        | Energy          |
| Hunt Them Down     | Deal 3 additional damage if the target is tracked.                                         | 2        | Damage Up       |
| Catch the Scent    | Hitting a target with Tracer Bolt reduces the cooldown of Hawk Drone by 1.                 | 3        | Cooldown        |

**Default Mod:** Hunt Them Down

---

### Ability 2: Hawk Drone

- **Phase:** Blast
- **Cooldown:** 2
- **Free:** No
- **Description:** Send out your drone, dealing 14 indirect damage to untracked targets or 18 indirect damage to tracked ones. The drone stays at the location, shooting enemies during the Blast Phase until an ability moves it. These attacks ignore cover.
- **Energy Gained:** Gain 4 energy per enemy hit.
- **Target Type:** Grid
- **Target Range:** 8
- **Area of Effect:** 5x5 square without 4 corner tiles

| **Mod Name**         | **Description**                                          | **Cost** | **Type**    |
| -------------------- | -------------------------------------------------------- | -------- | ----------- |
| Eye in the Sky       | Increase the radius of Hawk Drone's vision by 1.         | 1        | Effect Size |
| Composite Materials  | Increases the maximum range of the drone targeting by 2. | 2        | Range Up    |
| Infrared Enhancement | Attacks invisible enemies.                               | 2        | Special     |
| Vicious              | Increases damage to tracked targets by 4.                | 3        | Damage Up   |

**Default Mod:** Composite Materials

---

### Ability 3: Tranquilizer Dart

- **Phase:** Prep
- **Cooldown:** 4
- **Free:** Yes
- **Description:** Launch a dart that weakens and reveals an enemy until end of turn. Enemies hit by a dart are tracked for 2 turns.
- **Energy Gained:** Gain 6 energy per target hit.
- **Target Type:** Free aim
- **Target Range:** 7

| **Mod Name**      | **Description**                                                                | **Cost** | **Type**        |
| ----------------- | ------------------------------------------------------------------------------ | -------- | --------------- |
| Energy Feed       | Gain 3 additional energy on hit.                                               | 1        | Energy          |
| Overdose          | Enemies are also slowed.                                                       | 2        | Bad Status      |
| Impaired Judgment | Enemies hit cannot collect power-ups until the end of next turn.               | 2        | Bad Status      |
| Adrenal Overload  | Can now hit allies, granting might and unstoppable until end of turn.          | 3        | Good Status     |
| Double Dart       | Adds an additional dart. Reduces energy gain by 3 per dart and the range by 1. | 3        | Target Increase |

**Default Mod:** Overdose

---

### Ability 4: Slip Away

- **Phase:** Dash
- **Cooldown:** 6
- **Free:** No
- **Description:** Escape to target location adjacent to your drone.
- **Energy Gained:** Gain 10 energy.
- **Target Type:** Grid
- **Target Range:** 12 but only 3x3 square under drone

| **Mod Name**     | **Description**                                               | **Cost** | **Type**    |
| ---------------- | ------------------------------------------------------------- | -------- | ----------- |
| Thrilling Escape | Gain 5 energy when used.                                      | 1        | Energy      |
| Agile Escape     | Increase the size of the landing area by 1.                   | 2        | Effect Size |
| Unseen Huntress  | Become invisible until the beginning of next Resolution Mode. | 2        | Special     |
| Shelter          | Gain 20 shields until end of next turn.                       | 3        | Shield Up   |

**Default Mod:** Agile Escape

---

### Ability 5: Voltaic Cage

- **Phase:** Blast
- **Energy Cost:** 100
- **Description:** Command your drone to target location, where it creates a cage for 2 turns. Enemies that cross a barrier are rooted and take 22 indirect damage.
- **Free:** No
- **Target Type:** Grid
- **Target Range:** 8
- **Area of Effect:** 3x3

| **Mod Name**      | **Description**                                                  | **Cost** | **Type**   |
| ----------------- | ---------------------------------------------------------------- | -------- | ---------- |
| Prison Roster     | Enemies inside the cage are revealed until the end of next turn. | 1        | Bad Status |
| Caught in the Web | Increases the range of Voltaic Cage by 1.                        | 2        | Range Up   |
| Zapper            | Increases damage by 3.                                           | 2        | Damage Up  |
| Relentless        | On cast, resets the cooldown of Hawk Drone.                      | 3        | Cooldown   |

**Default Mod:** Relentless

## Dossier

**SKILLS:** Hunting, tracking, and cape collecting.

**KNOWN FOR:** Using her family fortune to develop the world's deadliest traps and tranqs.

**LIFE GOAL:** Catching "uncatchable" beasts.

As heiress of Hawk Aviation, Grey always commanded the public's attention. Yet, it was when she emerged as the sole survivor of an unidentified monster's attacks, ravaged by wounds that left her reliant on biokinetic prosthesis, that she became the public's champion. She poured her fortune into new weaponry and scoured the Depths, killing monsters "for the safety of Atlas" and more likely, to slake her growing hunger for the hunt.

The reclusive hunter is never seen without her state-of-the-art Hawk Drone, Rio. The device is programmed to destroy anything she finds threatening; to date, that appears to include just about everything in visible range.

## Story

**Friends:**

- **Rio:** Her Hawk Drone.

**Rivals:**

- **Rask:** The Rage Beast is suspected of attacking her family.
- **Nix:** Ongoing competition as to who can kill the most monsters (and each other) first.
- **Phaedra:** A monster Grey failed to kill in the Depths.
