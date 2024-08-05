+++
archetype = "home"
title = "Isadora"
+++

**Short Description:** Evil genius protected by a potent forcefield and armed with laser beams of doom.

| **Role**          | Frontline                            |
| ----------------- | ------------------------------------ |
| **Affiliation**   | Evos                                 |
| **Actual Health** | On Foot: 80 - Forceball: 100 shields |

| **Stat**   | **Value**                                                 |
| ---------- | --------------------------------------------------------- |
| Health     | {{< stat-bar color="green" percentage="80" value="8" >}}  |
| Damage     | {{< stat-bar color="red" percentage="50" value="5" >}}    |
| Survival   | {{< stat-bar color="blue" percentage="70" value="7" >}}   |
| Difficulty | {{< stat-bar color="orange" percentage="90" value="9" >}} |

## Abilities

### Ability 1: Doom Ray

- **Phase:** Blast
- **Cooldown:** None
- **Free:** No
- **Description:**
  - **Forceball:** Fire two lasers toward target location, creating an explosion. Enemies hit by a laser take **16** direct damage, while those caught by the explosion take **23** direct damage. The explosion is smaller the farther away it is.
  - **On Foot:** Fire a single laser toward target location, creating an explosion. Enemies hit by the laser take **25** direct damage, while those caught by the explosion take **31** direct damage. The explosion is bigger the farther away it is.
- **Energy Gained:** Gain **7** energy per enemy hit.
- **Target Type:** Free aim
- **Target Range:** **Forceball:** 5.5 & **On Foot:** 7

| **Mod Name**   | **Description**                                                                                                                      | **Cost** | **Type**    |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------ | -------- | ----------- |
| First Resort   | **On Foot**: Deal **6** additional damage and increase the explosion radius by **50%** on your first turn outside the **Forceball**. | 1        | Damage Up   |
| Focused Cortex | Gain **3** additional energy per enemy hit.                                                                                          | 2        | Energy      |
| Volatile       | **Forceball**: Reduce range by **0.5** but increase radius by **20%**.                                                               | 2        | Effect Size |
| Focal Point    | Increase damage of the burst by up to **5** the smaller it is.                                                                       | 3        | Damage Up   |

**Default Mod:** Focused Cortex

---

### Ability 2: Scamper

- **Phase:** Dash
- **Cooldown:** **Forceball**: 5 & **On Foot**: 2
- **Free:** No
- **Description:**
  - **Forceball:** Dash to target location, dealing **23** direct damage in an area. Cooldown: **5** turns.
  - **On Foot:** Dash to target location. Can move after dashing. Cooldown: **2** turns.

- **Energy Gained:** Gain **6** energy and an additional **4** per enemy hit.
- **Target Type:** Grid
- **Target Range:** **Forceball:** 4 & **On Foot:** 2
- **Area of Effect:** damage radius of 1.5

| **Mod Name**   | **Description**                                                                          | **Cost** | **Type**  |
| -------------- | ---------------------------------------------------------------------------------------- | -------- | --------- |
| Pellet Hunter  | **On Foot**: If you dash onto an **Energy Crystal**, gain an additional **10** energy.   | 1        | Energy    |
| Wily           | **On Foot**: No cooldown if health is below **30**.                                      | 1        | Cooldown  |
| Boosted Animal | Reduce the cooldown of this ability by **2** when **Suit Up** is used while **On Foot**. | 2        | Cooldown  |
| Scurry         | **On Foot**: Increase range by **1**.                                                    | 2        | Range Up  |
| Cannon Ball    | **Forceball**: Increase damage by **8**, but take **8** shield damage.                   | 3        | Damage Up |

**Default Mod:** Boosted Animal

---

### Ability 3: Reactive Chains

- **Phase:** Prep
- **Cooldown:** 4
- **Free:** Yes
- **Description:** Tether to all nearby enemies until the end of Dash Phase. If you or a tethered enemy dashes farther than **2.5** spaces away, the chains will react, **Pulling** the enemy up to **3** squares towards you during Blast Phase.
- **Energy Gained:** Gain **5** energy per target hit, and **5** per tether broken.
- **Target Type:** Self
- **Target Range:** 1.5

| **Mod Name**   | **Description**                                                                                      | **Cost** | **Type** |
| -------------- | ---------------------------------------------------------------------------------------------------- | -------- | -------- |
| Yank the Chain | Increase **Pull** distance by up to **3** more.                                                      | 1        | Range Up |
| Full Stop      | Now a **Full Action**, increase the radius by **1**. Enemies hit are **Weakened** until end of turn. | 2        | Special  |
| Zippy Line     | Reduce the cooldown by **2** if no targets break the tether.                                         | 2        | Cooldown |
| Energy Suction | Gain **2** additional energy per enemy hit and tether broken.                                        | 3        | Energy   |

**Default Mod:** Zippy Line

---

### Ability 4: Going Ball-Istic

- **Phase:** Blast
- **Cooldown:** 2
- **Free:** Yes
- **Description:** Overcharge yourself, creating a vortex that will explode around you next turn dealing **10** direct damage. This damage is increased by **1** per **10** missing shields, dealing up to **20** damage with no shields remaining. **Slows** enemies hit.
- **Energy Gained:** Gain **5** energy per enemy hit.
- **Target Type:** Self
- **Area of Effect:** Circle of radius 1.5

| **Mod Name**    | **Description**                                                                          | **Cost** | **Type**    |
| --------------- | ---------------------------------------------------------------------------------------- | -------- | ----------- |
| Furry Fury      | If you are **On Foot** when the explosion is set off, increase the damage done by **5**. | 1        | Damage Up   |
| Battle Ball     | Gain **Haste** for the turn, but normal free action mobility no longer applies.          | 2        | Good Status |
| Static Cling    | Enemies directly adjacent to you are **Rooted**.                                         | 2        | Bad Status  |
| Over-Overcharge | The explosion always deals the maximum damage of **20**.                                 | 3        | Special     |

**Default Mod:** Static Cling

---

### Ability 5: Suit Up

- **Phase:** Prep
- **Cooldown:** 3
- **Free:** No
- **Description:** Convert all of your energy into shields. Cannot exceed **100** shields. If **On Foot**, using this ability reconstitutes the **Forceball**.
  **Passive:** If your shields are depleted,this ability goes on a **3** turn cooldown and the **Forceball** shatters into 5 **Energy Crystals**. Collect these to gain **10** energy per **Crystal**. Remaining **Crystals** are removed upon **Suit Up** or death. 
               When the **Forceball** is destroyed you are considered **On Foot**, which changes the functionality of **Doom Ray** and **Scamper**, and disables **Reactive Chains** and **Going Ball-Istic**.
			   You do not generate energy naturally and lose all energy upon death.
- **Energy Gained:** None
- **Target Type:** Self

| **Mod Name**           | **Description**                                                         | **Cost** | **Type**    |
| ---------------------- | ----------------------------------------------------------------------- | -------- | ----------- |
| Killinator, Assemble!  | **Suit Up** cooldown when the **Forceball** has been destroyed is reduced by **1**. | 1        | Cooldown    |
| Ball Wall              | Gain **Unstoppable** for the turn.                                                  | 2        | Good Status |
| Pile o'Pellets         | Create **3** additional **Energy Crystals** when knocked out of the **Forceball**.  | 2        | Special     |
| Hungry, Hungry, Rodent | When the **Forceball** is destroyed, gain **Energized** for **2** turns next turn.  | 3        | Energy      |
| World Domination       | After you enter the **Forceball**, gain **Might** for **2** turns next turn.        | 3        | Good Status |

**Default Mod:** Ball Wall

## Dossier

**SKILLS:** Forcefield management. Laser targeting. Overcharging.

**KNOWN FOR:** Being a mad genius who developed the Forceball to amplify her destructive potential.

**FAVORITE SAYING:** “They called me crazy. Who's laughing now?”

Isadora's early experiments with forcefields and energy manipulation earned her both accolades and enemies. When her work was deemed too dangerous, she took matters into her own hands, creating the Forceball to protect herself and wreak havoc on her foes. Now a Freelancer, Isadora seeks to prove her genius on the battlefield, with the Forceball acting as both her shield and her weapon.

## Story

**Friends:**

- **Helio:** Respects his technological prowess.
- **Zuki:** Shares a passion for explosions.

**Rivals:**

- **Celeste:** Disagrees with her moral compass.
