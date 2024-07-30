+++
archetype = "home"
title = "Kaigin"
+++

**Short Description:** Deadly, elusive assassin armed with daggers, shuriken, and smoke bombs.

| **Role**          | Firepower |
| ----------------- | --------- |
| **Affiliation**   | Wildcard  |
| **Actual Health** | 130       |

| **Stat**   | **Value**                                                 |
| ---------- | --------------------------------------------------------- |
| Health     | {{< stat-bar color="green" percentage="20" value="4" >}}  |
| Damage     | {{< stat-bar color="red" percentage="70" value="7" >}}    |
| Survival   | {{< stat-bar color="blue" percentage="40" value="3" >}}   |
| Difficulty | {{< stat-bar color="orange" percentage="80" value="8" >}} |

## Abilities

### Ability 1: Twisting Blades

- **Phase:** Blast
- **Cooldown:** None
- **Free:** No
- **Description:** Deal **35** direct damage to enemies in the front arc and **25** direct damage to enemies in the side arcs.
- **Energy Gained:** Gain **12** energy for the first enemy hit and **4** for each subsequent enemy.
- **Target Type:** Arc
- **Target Range:** 2

| **Mod Name**        | **Description**                                                                              | **Cost** | **Type**        |
| ------------------- | -------------------------------------------------------------------------------------------- | -------- | --------------- |
| Essence Drain       | Gain **3** additional energy when hitting a **Void Marked** target.                          | **1**    | Energy          |
| Fury of the Void    | Increase the size of the frontal cone by **100%**.                                           | **2**    | Target Increase |
| Balanced Aggression | Increase the damage done to side targets by **5**.                                           | **2**    | Damage Up       |
| Focused Assault     | Deal **2** additional damage to enemies in the center but **5** less to enemies on the side. | **3**    | Damage Up       |
| Feed on Fear        | Gain **5** health when hitting a **Void Marked** target.                                     | **3**    | Heal            |

**Default Mod:** Fury of the Void

---

### Ability 2: Razor Tempest

- **Phase:** Blast
- **Cooldown:** 1
- **Free:** No
- **Description:** Throw **3** shurikens, each dealing **20** direct damage. Deals **5** additional damage for each shuriken that hits the same target.
- **Energy Gained:** Gain **8** energy for the first enemy hit and **2** for each subsequent enemy.
- **Target Type:** Projectile
- **Target Range:** 7

| **Mod Name**     | **Description**                                                                                                                                                      | **Cost**   | **Type**   |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ---------- |
| Unyielding       | Gain **12** energy on hit but no longer gain additional energy for hitting more targets.                                                                             | **1**      | Energy     |
| Flurry of Knives | Reduce the cooldown by **1** if no targets are hit.                                                                                                                  | **2**      | Cooldown   |
| Stalker's Mark   | Hitting a target with all of the shurikens **Reveals** them until end of next decision phase.                                                                        | **2**      | Bad Status |
| Honed Edge       | Ignores cover when hitting **Void Marked** targets.                                                                                                                  | **3**      | Damage Up  |
| Void Empowered   | Deals **5** additional damage but can no longer increase in damage when hitting with multiple shurikens.                                                             | **3**      | Damage Up  |
| Wave of Steel    | Increases number of shurikens by **1**. Reduces additional damage for each subsequent shiriken by **2**. Reduces energy gain for each subsequent enemy hit by **1**. | **1**      | Special    |

**Default Mod:** Flurry of Knives

---

### Ability 3: Void Strike

- **Phase:** Dash
- **Cooldown:** 4
- **Free:** No
- **Description:** Teleport to an enemy and slash them, dealing **33** direct damage. You can move after dashing.
- **Energy Gained:** Gain **12** energy on hit.
- **Target Type:** Single
- **Target Range:** 6.5

| **Mod Name**     | **Description**                                                                                              | **Cost** | **Type**    |
| ---------------- | ------------------------------------------------------------------------------------------------------------ | -------- | ----------- |
| Through the Void | Increase the range by **1** when dashing to **Void Marked** targets.                                         | **1**    | Range Up    |
| Crippling Stab   | Hitting a **Void Marked** target with this ability applies **Weak** to the target at the start of next turn. | **2**    | Bad Status  |
| Elusive          | Gain **Haste** for the turn.                                                                                 | **2**    | Good Status |
| Deathmark        | Deal **4** additional damage when hitting a **Void Marked** target.                                          | **3**    | Damage Up   |

**Default Mod:** Elusive

---

### Ability 4: Shadowstalker

- **Phase:** Blast
- **Cooldown:** 5
- **Free:** Yes
- **Description:** Drop a smoke bomb at your location that obscures enemy vision until the end of next turn. Gain **Invisibility** until the end of next decision phase.
- **Energy Gained:** Gain **8** energy on cast.
- **Target Type:** Area
- **Target Range:** 3

| **Mod Name**     | **Description**                                                                    | **Cost**   | **Type**    |
| ---------------- | ---------------------------------------------------------------------------------- | ---------- | ----------- |
| Cover of Night   | If no other abilities are used reduce the cooldown by **1**.                       | **1**      | Cooldown    |
| Soothing Shadows | If you are inside the smoke bomb at the beginning of next turn gain **10** health. | **1**      | Heal        |
| Suffocation      | **Slow** adjacent enemies until end of the turn.                                   | **2**      | Bad Status  |
| Thick Smoke      | Increase the duration of the smoke by **1** turn.                                  | **2**      | Special     |
| Preparation      | Gain **Energized** next turn.                                                      | **3**      | Good Status |

**Default Mod:** Suffocation

---

### Ability 5: Spectre of Death

- **Phase:** Dash
- **Energy Cost:** **100**
- **Description:** Teleport to a location, dealing **50** direct damage if there is only one target in the area. If there is more than one target in the area, the damage dealt to all the targets is reduced by **8** for each target after the first. Ignores Covers. **Passive:** Whenever damage is dealt to an enemy they are **Void Marked**. If an enemy is already **Void Marked** deal an additional **10** damage to them.
- **Free:** No
- **Target Type:** Area
- **Target Range:** 6.5

| **Mod Name**        | **Description**                                                                                                                   | **Cost**   | **Type**   |
| ------------------- | --------------------------------------------------------------------------------------------------------------------------------- | ---------- | ---------- |
| Fueled by Vengeance | Gain **10** energy when hitting a **Void Marked** target.                                                                         | **1**      | Energy     |
| Phantasmal Fury     | The damage penalty for multiple targets is reduced from **10** to **5**.                                                          | **2**      | Damage Up  |
| Master Assassin     | If only one target is hit they are **Slow** until end of turn and **Revealed** until end of next decision phase.                  | **2**      | Bad Status |
| Night Hunter        | Gain **15** health when hitting a **Void Marked** target. No longer deal additional damage when hitting a **Void Marked** target. | **3**      | Heal       |
| Eclipse             | Resets the cooldown on **Shadowstalker**.                                                                                         | **3**      | Cooldown   |
| Vengeance Seeker    | Range increased by **2**.                                                                                                         | **2**      | Range Up   |

**Default Mod:** Phantasmal Fury

## Dossier

**SKILLS:** Assassination, stealth, and space-time warping.

**KNOWN FOR:** Eliminating an A.I. created by GAIA and living to tell the tale.

**GUIDING MANTRA:** Nothing opens a mind like a plasma gun.

Like Asana, Kaigin is believed to have been a subject of "Project Nidus," an Omni initiative focused on producing warriors capable of wielding weapons created by GAIA, the A.I. who built and maintained the Reactors. The nanite infusion he received from Nidus gave him the unique ability to warp through the Reactor's energy fields; however, it is also said to have rendered him sightless. Still, his deadly accuracy with both daggers and shuriken indicate that his lack of eyesight has not hindered him.

It should be noted that his unexpected emergence as a "self-funded" Freelancer was met with heavily upgraded security in both the Reactor and at Omni-Plex. In particular, new devices were placed around the Reactor specifically to deter teleportation. While correlation does not imply causation, this "coincidence" has many citizens wondering why.

## Story

**Friends:**

- **Asana:** Known to be childhood friends, though their current status is unclear.

**Rivals:**

- **Su-Ren:** "She knows why."
- **Tol-Ren:** Documents suggest the two may be enemies. Their repeated attempts to kill each other suggest that too.
