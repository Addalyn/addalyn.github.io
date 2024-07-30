+++
archetype = "home"
title = "Khita"
+++

**Short Description:** Nimble archer with specialized arrows that can heal and shield allies.

| **Role**          | Support     |
| ----------------- | ----------- |
| **Affiliation**   | Helio Corps |
| **Actual Health** | 130         |

| **Stat**   | **Value**                                                 |
| ---------- | --------------------------------------------------------- |
| Health     | {{< stat-bar color="green" percentage="60" value="6" >}}  |
| Damage     | {{< stat-bar color="red" percentage="30" value="3" >}}    |
| Survival   | {{< stat-bar color="blue" percentage="60" value="6" >}}   |
| Difficulty | {{< stat-bar color="orange" percentage="30" value="3" >}} |

## Abilities

### Ability 1: Warped Arrow

- **Phase:** Blast
- **Cooldown:** None
- **Free:** No
- **Description:** Loose a curving arrow that deals 28 direct damage. Click once to start aiming, then a second time to finish.
- **Energy Gained:** Gain 12 energy on hit.
- **Target Type:** Free aim

| **Mod Name**     | **Description**                                                      | **Cost** | **Type**   |
| ---------------- | -------------------------------------------------------------------- | -------- | ---------- |
| To The Knee      | Triggering Take Aim! also slows the target hit.                      | 1        | Bad Status |
| Leaf In The Wind | Increases the maximum curve angle by 20 degrees.                     | 2        | Range Up   |
| Stocked Quiver   | Gain 3 additional energy on hit.                                     | 2        | Energy     |
| Fly True         | Arrow pierces the first target, dealing 8 damage to the next target. | 3        | Special    |

**Default Mod:** Leaf In The Wind

---

### Ability 2: Resonance Burst

- **Phase:** Prep
- **Cooldown:** 3
- **Free:** No
- **Description:** Create an energy fluctuation that grants 30 shields to allies and weakens enemies until end of turn.
- **Energy Gained:** Gain 6 energy for each enemy hit and 4 per ally hit.
- **Target Type:** Grid

| **Mod Name**       | **Description**                                           | **Cost** | **Type**   |
| ------------------ | --------------------------------------------------------- | -------- | ---------- |
| Resonant Capacitor | Gain 2 more energy per target hit.                        | 1        | Energy     |
| Focused Burst      | Shield is strengthened by 6 if only one ally is shielded. | 2        | Shield Up  |
| Jelly Legs         | Enemies hit are also slowed until end of turn.            | 2        | Bad Status |
| Sonic Resonance    | Up to 10 remaining shields can persist for 1 extra turn.  | 3        | Shield Up  |

**Default Mod:** Jelly Legs

---

### Ability 3: Take Aim!

- **Phase:** Prep
- **Cooldown:** 4
- **Free:** Yes
- **Description:** Mark an enemy until end of next turn. The first time an ally deals direct damage to the marked enemy, the ally is healed for 25.
- **Energy Gained:** Gain 4 energy on use and 2 energy each time the target is hit.
- **Target Type:** Grid

| **Mod Name**    | **Description**                                                   | **Cost** | **Type**    |
| --------------- | ----------------------------------------------------------------- | -------- | ----------- |
| Sharpshooter    | Your attack that triggers Take Aim! deals 4 additional damage.    | 1        | Damage Up   |
| Moment of Glory | Allies below 50% health receive 5 additional healing.             | 2        | Heal        |
| RFID Chip       | Targeted enemy is revealed until the end of next decision mode.   | 2        | Bad Status  |
| Aim Assist      | Can be targeted through walls.                                    | 2        | Effect Size |
| Aim Again!      | Allies are healed for 5 the second time they hit a marked target. | 3        | Heal        |

**Default Mod:** Sharpshooter

---

### Ability 4: Vaulting Shot

- **Phase:** Dash
- **Cooldown:** 5
- **Free:** No
- **Description:** Dash to a location then fire an arrow in the opposite direction which deals 20 direct damage and slows until end of turn.
- **Energy Gained:** Gain 8 energy per enemy hit.
- **Target Type:** Grid

| **Mod Name**      | **Description**                                                                    | **Cost** | **Type**    |
| ----------------- | ---------------------------------------------------------------------------------- | -------- | ----------- |
| Ready, Aim, Fire! | Triggering Take Aim! with Vaulting Shot also roots the marked target for one turn. | 1        | Bad Status  |
| Surge of Energy   | Gain 2 more energy per target hit.                                                 | 1        | Energy      |
| Cover the Field   | Increase shot targeting angle by 40 degrees.                                       | 2        | Effect Size |
| Light-Footed      | Gain Haste until end of next turn.                                                 | 2        | Good Status |
| Survivalist       | Increases the damage done by 6                                                     | 3        | Damage Up   |

**Default Mod:** Light-Footed

---

### Ability 5: Rain of Arrows

- **Phase:** Blast
- **Energy Cost:** 100
- **Description:** Rain arrows down in a line, dealing 28 direct damage to enemies and rooting them. Choose two points within range to create the line of effect. Does not require line of sight. Ignores cover.
- **Target Type:** Grid

| **Mod Name**     | **Description**                                                                    | **Cost** | **Type**    |
| ---------------- | ---------------------------------------------------------------------------------- | -------- | ----------- |
| Cloudy Skies     | Gain **energized** until end of next turn.                                         | 1        | Energy      |
| Heavy Rain       | Deals an additional 5 damage to enemies below 50% health.                          | 1        | Damage Up   |
| Crippling Blow   | Enemies hit are Slowed next turn.                                                  | 2        | Bad Status  |
| Pins and Needles | Reduce cooldown of Take Aim! by 1.                                                 | 2        | Cooldown    |
| Deluge of Arrows | Adds an additional segment to the arrow path. The max length of each segment is 3. | 3        | Effect Size |

**Default Mod:** Heavy Rain

## Dossier

**SKILLS:** Mind-bending hook shots. Laughing at you (and herself).

**KNOWN FOR:** Surviving the waste with (some of) her sanity intact.

**FAVORITE THING ABOUT ATLAS:** "The people! And clean water! Both great."

## Story

While no official records of Khita's life before Atlas exist, the lancer herself is candid with tales of her adventures in the Waste. "Titus saved my life out there!" she declared in holo-streams across Atlas. "I couldn't kill anything before he came along. Then, it was like, dead food walking! PING!"

Some insist that her chipper demeanor is a ruse. Witnesses to her skill say that much like her self-proclaimed mentor, Titus, Khita is a fearless, brutal warrior. With her set of specialized arrows, she is able to attack targets and aid allies from near impossible angles. Silent on the hunt, the only thing that lets you know she's coming is the sound of peeling laughter just before her arrow finds its mark.

**Friends:**

- **Titus:** Taught Khita how to survive in the Waste.
