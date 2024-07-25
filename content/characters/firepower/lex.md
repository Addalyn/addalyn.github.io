+++
archetype = "home"
title = "Lex"
+++

**Short Description:** A fiery warrior wielding twin flamethrowers, capable of incinerating foes and igniting the battlefield.

| **Role**          | Firepower   |
| ----------------- | ----------- |
| **Affiliation**   | Hyperbotics |
| **Actual Health** | 145         |

| **Stat**   | **Value**                                                 |
| ---------- | --------------------------------------------------------- |
| Health     | {{< stat-bar color="green" percentage="40" value="4" >}}  |
| Damage     | {{< stat-bar color="red" percentage="70" value="7" >}}    |
| Survival   | {{< stat-bar color="blue" percentage="50" value="5" >}}   |
| Difficulty | {{< stat-bar color="orange" percentage="60" value="6" >}} |

## Abilities

### Ability 1: Firestarter

- **Phase:** Blast
- **Cooldown:** None
- **Free:** No
- **Description:** Unleash twin flamethrowers, torching enemies for 28 direct damage. Spaces hit by both templates are set on fire until end of turn, dealing 5 indirect damage to enemies that touch them.
- **Energy Gained:** Gain 6 energy per enemy hit. Ground fire hits do not grant energy.
- **Target Type:** Free aim
- **Target Range:** 7
- **Area of Effect:** Cone

| **Mod Name**    | **Description**                                                  | **Cost** | **Type**    |
| --------------- | ---------------------------------------------------------------- | -------- | ----------- |
| Heating Up      | Gain 2 more energy per enemy hit.                                | 1        | Energy      |
| Hotfoot         | Grants Haste next turn.                                          | 2        | Good Status |
| Heat Signature  | Enemies are Revealed until end of turn if hit by both templates. | 2        | Bad Status  |
| Inferno         | Deal 2 more damage to enemies hit by both templates.             | 3        | Damage Up   |
| Bathed in Flame | Increase template arcs from 30 to 45 degrees.                    | 3        | Effect Size |

**Default Mod:** Heat Signature

---

### Ability 2: Flash Point

- **Phase:** Prep
- **Cooldown:** 4
- **Free:** Yes
- **Description:** Imbue yourself, an ally, or an enemy with an explosive charge until end of turn. This charge detonates during Blast Phase dealing 10 indirect damage to nearby enemies, but not the target.
- **Energy Gained:** Gain 4 energy per enemy hit.
- **Target Type:** Grid
- **Target Range:** 1

| **Mod Name**     | **Description**                                                                                           | **Cost** | **Type**   |
| ---------------- | --------------------------------------------------------------------------------------------------------- | -------- | ---------- |
| Ignition         | The cooldown of this ability is increased by 1, but resets whenever the Superheated ability is activated. | 1        | Cooldown   |
| Infrared         | Can target through walls.                                                                                 | 2        | Range Up   |
| Heat Shield      | Target gains 10 shields until end of turn.                                                                | 2        | Shield Up  |
| Concussive Blast | Enemies hit by the explosion are Slowed.                                                                  | 2        | Bad Status |
| On Fire          | If you are superheated, the duration of this ability is increased by 1 turn.                              | 3        | Special    |

**Default Mod:** On Fire

---

### Ability 3: Afterburners

- **Phase:** Dash
- **Cooldown:** 3
- **Free:** No
- **Description:** Launch yourself toward a target space, dealing 23 direct damage to enemies around the destination. This dash will stop short at the first enemy in your path. Spaces covered by this template are set on fire until the end of the turn, dealing 5 indirect damage to enemies that touch them. Damage from this ability ignores cover.
- **Energy Gained:** Gain 5 energy per enemy hit. Ground fire hits do not grant energy.
- **Target Type:** Free aim
- **Target Range:** 7
- **Area of Effect:** Cone

| **Mod Name**   | **Description**                                                         | **Cost** | **Type**   |
| -------------- | ----------------------------------------------------------------------- | -------- | ---------- |
| Scorched Earth | If superheated, ground fire from this ability lasts an additional turn. | 1        | Special    |
| Aftershock     | Enemies hit by the explosion are Slowed.                                | 2        | Bad Status |
| Rocket Fuel    | Increase range by 1.                                                    | 2        | Range Up   |
| Ground Zero    | Increase damage by 3.                                                   | 2        | Damage Up  |
| Forged         | Gain 8 shields per enemy hit.                                           | 3        | Shield Up  |

**Default Mod:** Ground Zero

---

### Ability 4: Backdraft

- **Phase:** Prep
- **Cooldown:** 4
- **Free:** No
- **Description:** Gain 20 shields during Prep Phase. During Blast Phase, hurl a fireball that deals 15 direct damage to enemies it passes through. If you are hit by a direct damage attack, you will throw a second fireball in the same direction, dealing 15 additional indirect damage and setting the ground on fire until end of turn. Enemies that touch the fire take 5 indirect damage.
- **Energy Gained:** Gain 8 energy if you hit an enemy, and 2 energy for each enemy hit per blast. Ground fire hits do not grant energy.
- **Target Type:** Free aim
- **Target Range:** 7
- **Area of Effect:** Cone

| **Mod Name**   | **Description**                                                                 | **Cost** | **Type**    |
| -------------- | ------------------------------------------------------------------------------- | -------- | ----------- |
| Thermal Dynamo | Gain 5 shields next turn for each direct damage attack that hits you this turn. | 1        | Shield Up   |
| Fuel Reserves  | Shields last until the end of next turn.                                        | 1        | Special     |
| Burning Rage   | The damage of the second fireball is increased by 5.                            | 1        | Damage Up   |
| Last Stand     | Gain 20 more shields if health is below 60.                                     | 2        | Shield Up   |
| Uncontrollable | Gain Unstoppable until end of turn.                                             | 3        | Good Status |

**Default Mod:** Thermal Dynamo

---

### Ability 5: Superheated

- **Phase:** Prep
- **Energy Cost:** Activation Cost: 50 energy
- **Description:** Unleash your inner flame, becoming superheated until end of next turn. While superheated, dealing damage to enemies with your abilities or ground fire will ignite them, dealing 5 indirect damage during the next turn and showing their location. Ignite damage will trigger Cryo Cores.
- **Free:** Yes
- **Target Type:** Self

| **Mod Name**   | **Description**                                                                     | **Cost** | **Type**    |
| -------------- | ----------------------------------------------------------------------------------- | -------- | ----------- |
| Fallout        | Slow adjacent enemies on cast.                                                      | 1        | Bad Status  |
| Burnout        | Grants Haste until end of turn.                                                     | 2        | Good Status |
| Wildfire       | Grants Energized until end of turn.                                                 | 2        | Energy      |
| Boil Over      | Grants Might until end of turn, but increases the energy cost of Superheated to 75. | 3        | Good Status |
| Phoenix Rising | Heal 10 on cast.                                                                    | 3        | Heal        |

**Default Mod:** Wildfire

## Dossier

**SKILLS:** Keeping the heat on her enemies. Heavy fire. Pro flamer.

**KNOWN FOR:** Always looking for a great match.

**PERSONAL MANTRA:** It only takes one ember to start a blaze.

**BIRTHDAY:** October 24

**Story:**

According to Lex, before the fall of Hyperion, she was slated to be the first true cybernetic soldier of Hyperion. (Her brother was second). She took easily to the training required for cybernetic enhancement, unlike some others in her class, and purportedly "burnt her competition to a crisp" while they were "still learning how to make icicles."

Due to the failure of the Hyperion reactor, Lex was put into a prolonged and unexpected cryosleep. When the Hyperion Reactor was restarted decades later, her unusual body chemistry caused her to awaken from sleep weeks early. She then vanished for an undisclosed period of time. (Curiously, during this time, it was also reported that sudden wildfires flared up all over frozen Hyperion subzones, thawing some, and burning down others. Connections to Lex are still purely conjecture).

Hyperion records state that Lex can manipulate fire, superheating the air around her and creating explosions at will.

**Friends:**

- **N/A**

**Rivals:**

- **N/A**
