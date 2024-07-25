+++
archetype = "home"
title = "Elle"
+++

**Short Description:** Ice-cold agent who deals damage to enemies near and far.

| **Role**          | Firepower |
| ----------------- | --------- |
| **Affiliation**   | Omni      |
| **Actual Health** | `150`     |

| **Stat**   | **Value**                                                 |
| ---------- | --------------------------------------------------------- |
| Health     | {{< stat-bar color="green" percentage="20" value="4" >}}  |
| Damage     | {{< stat-bar color="red" percentage="90" value="9" >}}    |
| Survival   | {{< stat-bar color="blue" percentage="40" value="4" >}}   |
| Difficulty | {{< stat-bar color="orange" percentage="70" value="5" >}} |

## Abilities

### Ability 1: Plasma Volley

- **Phase:** Blast
- **Cooldown:** None
- **Free:** No
- **Description:** Blast your enemies, dealing `27` direct damage to each enemy hit. Mods to this ability apply to shots from **Combat Reflexes** as well.
- **Energy Gained:** Gain `8` energy per enemy hit.
- **Target Type:** Free aim
- **Target Range:** `7`
- **Area of Effect:** Cone

| **Mod Name**     | **Description**                                                                        | **Cost** | **Type**        |
| ---------------- | -------------------------------------------------------------------------------------- | -------- | --------------- |
| Prey on the Meek | If only one target is hit, they are **revealed** until end of the next decision phase. | `1`      | Bad Status      |
| Focused Fury     | If only one target is hit, increase the damage by `5`.                                 | `2`      | Damage Up       |
| Wide Barrel      | Increases the size of the arc by **10** degrees at maximum range.                      | `2`      | Damage Up       |
| Killing Field    | Increases damage by up to `4` as the range becomes shorter.                            | `3`      | Target Increase |

**Default Mod:** Killing Field

---

### Ability 2: Combat Reflexes

- **Phase:** Dash
- **Cooldown:** 4
- **Free:** No
- **Description:** Dash a short distance then fire your plasma gun, dealing `27` direct damage. Has **2** charges.
- **Energy Gained:** Gain `8` energy per enemy hit.
- **Target Type:** Grid
- **Target Range:** 1

| **Mod Name**   | **Description**                                            | **Cost** | **Type**    |
| -------------- | ---------------------------------------------------------- | -------- | ----------- |
| Close Call     | Gain `5` shields until the end of this turn.               | `1`      | Shield Up   |
| Dance of Death | Gain a third charge of **Combat Reflexes**.                | `2`      | Special     |
| Follow Through | Gain **haste** until end of next turn.                     | `2`      | Good Status |
| Action Roll    | Can now dash up to **2** spaces but no longer has charges. | `3`      | Range Up    |

**Default Mod:** Action Roll

---

### Ability 3: Overcharge

- **Phase:** Prep
- **Cooldown:** None
- **Free:** No
- **Description:** Your next attack will deal `10` additional direct damage. Excludes **Lurker Drone**. Allows full movement.
- **Energy Gained:** Gain `5` energy on use.
- **Target Type:** Self

| **Mod Name**     | **Description**                                                                                        | **Cost** | **Type**    |
| ---------------- | ------------------------------------------------------------------------------------------------------ | -------- | ----------- |
| Double Charge    | Can be used again to increase the damage bonus by an additional `4`.                                   | `1`      | Damage Up   |
| Block 'N Load    | Gain `15` shields until end of turn.                                                                   | `2`      | Shield Up   |
| Leg Shot         | While **Overcharge** is active, **Combat Reflexes** **slows** all enemies hit.                         | `2`      | Bad Status  |
| On the Chase     | Gain **haste** for the turn.                                                                           | `2`      | Good Status |
| Brutal Precision | While **Overcharge** is active, **Plasma Volley** causes all enemies hit to be **weakened** next turn. | `3`      | Bad Status  |

**Default Mod:** Brutal Precision

---

### Ability 4: Lurker Drone

- **Phase:** Prep
- **Cooldown:** `5`
- **Free:** Yes
- **Description:** Place a Lurker Drone. Can be freely triggered on a subsequent turn, exploding for `20` indirect damage and **slowing** targets hit until end of that turn. Not affected by **Overcharge**. Fires automatically after **3** turns.
- **Energy Gained:** Gain `8` energy per enemy hit.
- **Target Type:** Free aim
- **Target Range:** `7`

| **Mod Name**     | **Description**                                             | **Cost** | **Type**    |
| ---------------- | ----------------------------------------------------------- | -------- | ----------- |
| Bodyguard        | **Lurker Drone** changes its facing towards Elle each turn. | `1`      | Special     |
| Rapid Deployment | Reduce the cooldown by `1` turn.                            | `1`      | Cooldown    |
| Bunker Buster    | **Cover** damage reduction is halved.                       | `2`      | Damage Up   |
| Point Blank      | Targets within `2` spaces take an additional `8` damage.    | `2`      | Damage Up   |
| Larger Lurker    | Increase the width by **30%**.                              | `3`      | Effect Size |

**Default Mod:** Larger Lurker

---

### Ability 5: Oblivion Shell

- **Phase:** Blast
- **Energy Cost:** `100`
- **Description:** Deals `40` direct damage and **knocks back** enemies in a cone. The **knockback** also affects you.
- **Free:** No
- **Target Type:** Free aim
- **Target Range:** `7`
- **Area of Effect:** 90° cone

| **Mod Name**  | **Description**                                                                               | **Cost** | **Type**    |
| ------------- | --------------------------------------------------------------------------------------------- | -------- | ----------- |
| Crowd Control | **Knockback** distance is increased by `2`.                                                   | `1`      | Special     |
| Warpath       | Gain **unstoppable** for the turn.                                                            | `1`      | Good Status |
| Art of Murder | **Cover** damage reduction is halved.                                                         | `2`      | Damage Up   |
| Killing Spree | The next time you use **Overcharge** after using **Oblivion Shell**, it is a **free action**. | `3`      | Special     |

**Default Mod:** Killing Spree

## Dossier

**SKILLS:** Making a mess. Sending a message.

**KNOWN FOR:** Active aggression. A low tolerance for... anyone.

**GUIDING MANTRA:** Nothing opens a mind like a plasma gun.

Elle is rumored to be Agent L, Omni's highest-ranking enforcer. Known as the whispered "wolf" of Omni, Elle ensures that all trust directives are obeyed and all debts repaid. She handles any problem, no matter how big, small, or talkative, with her custom-built plasma gun. If Omni wants it done, Elle delivers. The messier the message, the better. No one can confirm this rumor, but Elle herself admits her favorite pastime is murder. It might be best to keep your distance.

## Story

**Friends:**

- **Maid Mary:** Her plasma gun.

**Rivals:**

- **Celeste:** Elle hunted an Omni thief, suspected to be Celeste.
- **Zuki:** Elle is rumored to have "questioned" Zuki regarding an Omni theft.
