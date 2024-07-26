+++
archetype = "home"
title = "Rampart"
+++

**Short Description:** Heavy duty warbot with a massive, unbreachable shield.

| **Role**          | Frontline   |
| ----------------- | ----------- |
| **Affiliation**   | Helio Corps |
| **Actual Health** | 200         |

| **Stat**   | **Value**                                                  |
| ---------- | ---------------------------------------------------------- |
| Health     | {{< stat-bar color="green" percentage="100" value="10" >}} |
| Damage     | {{< stat-bar color="red" percentage="30" value="3" >}}     |
| Survival   | {{< stat-bar color="blue" percentage="80" value="8" >}}    |
| Difficulty | {{< stat-bar color="orange" percentage="80" value="8" >}}  |

## Abilities

### Ability 1: Radamantium Flurry

- **Phase:** Blast
- **Cooldown:** None
- **Free:** No
- **Description:** Stab in a line dealing 30 direct damage, then spin dealing 25 direct damage to adjacent enemies.
- **Energy Gained:** Gain 8 energy per enemy hit.
- **Target Type:** Free aim
- **Target Range:** 5
- **Area of Effect:** Line

| **Mod Name**     | **Description**                                                    | **Cost** | **Type**    |
| ---------------- | ------------------------------------------------------------------ | -------- | ----------- |
| Battle Rush      | Increase energy gain per enemy hit by 2.                           | 1        | Energy      |
| Area Suppression | Increases damage done to adjacent enemies by 3.                    | 2        | Damage Up   |
| Danger Zone      | Deal 4 additional damage to enemies hit by both the stab and spin. | 3        | Damage Up   |
| Deadly Stab      | Increases the width of the initial stab by 50%.                    | 3        | Effect Size |

**Default Mod:** Area Suppression

---

### Ability 2: Bulwark

- **Phase:** Prep
- **Cooldown:** 3
- **Free:** No
- **Description:** Place your shield during the Prep Phase, blocking attacks. Blast enemies during the Blast Phase, inflicting 28 direct damage and Slow.
- **Energy Gained:** Gain 6 energy per enemy hit and 6 energy for each ability blocked.
- **Details:**
  - Bulwark will always be the first ability to execute during the Prep Phase, allowing it to block other abilities that happen during that phase.

| **Mod Name**       | **Description**                                      | **Cost** | **Type**   |
| ------------------ | ---------------------------------------------------- | -------- | ---------- |
| Kinetic Absorption | Gain 8 energy for each attack blocked.               | 1        | Energy     |
| Bunker             | Gain 10 health for each attack blocked.              | 2        | Heal       |
| Defensive Posture  | On use, gain 25 shields until end of next turn.      | 2        | Shield     |
| Bullrush           | Enemies are Rooted instead of Slowed.                | 3        | Bad Status |
| Reflective Shield  | Deal 10 damage to enemies whose attacks are blocked. | 3        | Damage Up  |

**Default Mod:** Defensive Posture

---

### Ability 3: Fusion Lance

- **Phase:** Blast
- **Cooldown:** 3
- **Free:** No
- **Description:** Impale the enemy dealing 28 direct damage and pulling the target to you.
- **Energy Gained:** Gain 10 energy if you hit an enemy.
- **Target Type:** Grid
- **Target Range:** 4

| **Mod Name**             | **Description**                                                              | **Cost** | **Type**  |
| ------------------------ | ---------------------------------------------------------------------------- | -------- | --------- |
| Plasma Lance             | Increases damage by 4.                                                       | 1        | Damage Up |
| Rocket Lance             | Range increased by 2.                                                        | 2        | Range Up  |
| Gone Fishin              | You can now select the square the enemy is knocked back to.                  | 3        | Special   |
| Radamantium Tipped Blade | Pierce through the first enemy hit. Deal 12 damage to the second target hit. | 3        | Special   |

**Default Mod:** Rocket Lance

---

### Ability 4: Unstoppable Force

- **Phase:** Prep
- **Cooldown:** 3
- **Free:** Yes
- **Description:** Gain Unstoppable and Haste for the turn.
- **Energy Gained:** Gain 5 energy.
- **Target Type:** Self

| **Mod Name**        | **Description**                                   | **Cost** | **Type**    |
| ------------------- | ------------------------------------------------- | -------- | ----------- |
| Special Forces      | Nearby allies also gain Unstoppable for the turn. | 1        | Effect Size |
| Invincible          | On use, gain 15 shields for the turn.             | 2        | Shield      |
| Show of Force       | You also gain Might for the turn.                 | 3        | Good Status |
| Terrifying Presence | Nearby enemies are Slowed for the turn.           | 3        | Bad Status  |

**Default Mod:** Invincible

---

### Ability 5: Aegis Protocol

- **Phase:** Dash
- **Energy Cost:** None
- **Description:** Dash to a target location and place your shield, blocking attacks. Enemies you trample over take 35 direct damage and are Slowed. Ignores Cover.
- **Free:** No
- **Target Type:** Grid
- **Target Range:** 6

| **Mod Name**    | **Description**                                                        | **Cost** | **Type**  |
| --------------- | ---------------------------------------------------------------------- | -------- | --------- |
| Protective Wake | Allies crossed over or hit by the charge gain 20 shields for the turn. | 1        | Heal      |
| Live to Fight   | Increases damage by 5.                                                 | 2        | Damage Up |
| Rocket Boosters | Increases the maximum distance of the charge by 2.                     | 2        | Range Up  |
| Engine of War   | Root all targets trampled over.                                        | 3        | Special   |

**Default Mod:** Rocket Boosters

## Dossier

**SKILLS:** Intimidation. Indomitable optimism.

**KNOWN FOR:** Being Warbotics’ oldest active-duty product.

**CHILDHOOD DREAM:** To become a rocket.

## Story

Rampart was never supposed to be built. With the AI Sentience Ban still in place after GAIA's desertion, his conception was a rebel effort in the midst of civil unrest and desperation. Though Warbotics kept his AI primitive to prevent him from uprising like GAIA, he still exhibits a surprising intellect and empathy toward both humans and his fellow bots. The full extent of his sentience is unknown.

He is programmed to shield allies from harm, no matter the cost. His indestructible shield can deflect any amount of damage (as long as his allies remember to stand behind it).

## Friends:

- **Garrison:** Longtime war buddies.
- **PuP:** Fought alongside PuP in the war. Collects PuP-toys with his employee discount.
- **Oz:** Seen taking turns giving piggyback rides to each other across Flyway Freighter.
- **Brynn:** An old friend of Brynn’s family.

## Rivals:

None
