+++
archetype = "home"
title = "Su-Ren"
+++

**Short Description:** A highly trained martial artist with a special gift for healing.

| **Role**          | Support |
| ----------------- | ------- |
| **Affiliation**   | Omni    |
| **Actual Health** | 140     |

| **Stat**   | **Value**                                                 |
| ---------- | --------------------------------------------------------- |
| Health     | {{< stat-bar color="green" percentage="50" value="5" >}}  |
| Damage     | {{< stat-bar color="red" percentage="20" value="2" >}}    |
| Survival   | {{< stat-bar color="blue" percentage="80" value="8" >}}   |
| Difficulty | {{< stat-bar color="orange" percentage="60" value="6" >}} |

## Abilities

### Ability 1: Martial Master

- **Phase:** Blast
- **Cooldown:** None
- **Free:** No
- **Description:** Strike targets down a line for 26 direct damage or in a circle for 22 direct damage.
- **Energy Gained:** Gain 6 energy per enemy hit.
- **Target Type:** Free aim
- **Target Range:** 7
- **Area of Effect:** Line or Circle

| **Mod Name**    | **Description**                                                        | **Cost** | **Type**  |
| --------------- | ---------------------------------------------------------------------- | -------- | --------- |
| Bo Staff Skills | Gain 2 additional energy per enemy hit.                                | 1        | Energy    |
| Forceful Strike | Deal 4 additional damage to enemies on the edge of the targeter.       | 2        | Damage Up |
| Spirit Cycles   | If 2 or more enemies are hit, reduce the cooldown of Spirit Bend by 1. | 2        | Cooldown  |
| Zen State       | Heal for 3 health per enemy you hit with Martial Master.               | 3        | Damage Up |

**Default Mod:** Forceful Strike

---

### Ability 2: Serenity

- **Phase:** Blast
- **Cooldown:** 3
- **Free:** Yes
- **Description:** Heal yourself for 18 health and allies for 24 health.
- **Energy Gained:** Gain 4 energy per target hit.
- **Target Type:** Grid
- **Target Range:** 1

| **Mod Name**       | **Description**                                                                                      | **Cost** | **Type** |
| ------------------ | ---------------------------------------------------------------------------------------------------- | -------- | -------- |
| Surge of Light     | If only one ally is healed, they gain an additional 4 health.                                        | 1        | Heal     |
| Close to Greatness | Heal an additional 3 health to adjacent targets, reduced by 1 for each square further away they are. | 2        | Heal     |
| Energizing Burst   | Allies now gain 4 energy on hit.                                                                     | 2        | Energy   |
| Gaia's Blessing    | Restores an additional 6 health to an ally if they are under 50% health.                             | 3        | Special  |

**Default Mod:** Close to Greatness

---

### Ability 3: Shifting Winds

- **Phase:** Dash
- **Cooldown:** 5
- **Free:** No
- **Description:** Dash to an enemy, dealing 20 direct damage or to an ally, healing for 20 health. Can be used 2 turns in a row but must target an enemy if an ally was targeted first and vice versa.
- **Energy Gained:** Gain 12 energy on hit.
- **Target Type:** Grid
- **Target Range:** 7

| **Mod Name**           | **Description**                                          | **Cost** | **Type**  |
| ---------------------- | -------------------------------------------------------- | -------- | --------- |
| Protector              | Allies below 50% health heal for an additional 8 health. | 1        | Heal      |
| Strong as the Mountain | Gain 10 shields until end of turn.                       | 2        | Shield Up |
| Swift as the Wind      | If the second dash isn't used, reduce the cooldown by 1. | 2        | Cooldown  |
| Momentum               | Increases the effectiveness of the second dash by 50%.   | 3        | Special   |

**Default Mod:** Swift as the Wind

---

### Ability 4: Spirit-Bend

- **Phase:** Prep
- **Cooldown:** 4
- **Free:** No
- **Description:** Grants Might to target ally or Weaken to target enemy until their next attack within 2 turns. If that target attacks, anyone hit by the attack gains the opposite status effect.
- **Energy Gained:** Gain 10 energy on hit.
- **Target Type:** Grid
- **Target Range:** 7

| **Mod Name**      | **Description**                                                                            | **Cost** | **Type**    |
| ----------------- | ------------------------------------------------------------------------------------------ | -------- | ----------- |
| Chi Overflow      | Grant 5 energy to the ally target or grant 3 energy to all allies hit by the enemy target. | 1        | Energy      |
| Resonant Spirit   | Can be targeted through walls.                                                             | 2        | Special     |
| Spiritual Echoes  | Spirit Bend lasts 3 turns but still fades after a buff or debuff is transferred.           | 2        | Special     |
| Spiritual Journey | Additionally grants Haste to ally targets and Slow to enemy targets.                       | 3        | Good Status |

**Default Mod:** Resonant Spirit

---

### Ability 5: Karmic Justice

- **Phase:** Prep
- **Energy Cost:** 100
- **Description:** Grant a target 100 shields until end of turn. Next turn a Chi explosion originates from the target dealing up to 50 indirect damage, starting at 25 damage and increasing by 1 for every 4 damage taken during the first turn.
- **Free:** No
- **Target Type:** Grid
- **Target Range:** 7

| **Mod Name**       | **Description**                                                                                                  | **Cost** | **Type**    |
| ------------------ | ---------------------------------------------------------------------------------------------------------------- | -------- | ----------- |
| Fleet of Foot      | Target gains Haste until end of next turn.                                                                       | 1        | Good Status |
| Gaia's Chosen      | Converts 25% of the remaining shields into healing.                                                              | 2        | Heal        |
| Avatar of Gaian    | Target gains Might until end of the next turn.                                                                   | 3        | Good Status |
| Karmic Aftershocks | The Chi explosion happens again on the turn after the first explosion, dealing 50% damage of the initial damage. | 3        | Damage Up   |

**Default Mod:** Gaia's Chosen

## Dossier

**SKILLS:** Cultivating talent.

**KNOWN FOR:** Training some of the finest warriors in Atlas.

**AGE:** Old, in human terms, but brand new, with tech and A.I.-updates.

As a direct descendant of GAIA (though several generations removed from GAIA's original A.I.), Su-Ren understands more than anyone the acute loss the world suffered when GAIA left. In the centuries since the Desertion, Su-Ren has dedicated herself to making the world once again worthy of GAIA, atoning for the ingratitude and carelessness that drove her away.

Most recently, she was known to be the guardian of Omni's "Project Nidus," raising and training an elite contingent of warriors, including Asana, in the Waste just beyond the megacity limits.

**Friends:**

- **Asana:** It is believed that Su-Ren trained and raised Asana since birth. So... 50% "friends" and 50% “arch rival” may be most accurate.
- **Tol-Ren:** Spotted sharing the same charge station at Omni.

**Rivals:**

- **Kaigin:** "He knows why."
