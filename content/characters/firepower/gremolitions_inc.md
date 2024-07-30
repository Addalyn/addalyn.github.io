+++
archetype = "firepower"
title = "Gremolitions Inc."
+++

**Short Description:** Lab-grown Gremunks who live for long-range artillery.

| **Role**          | Firepower |
| ----------------- | --------- |
| **Affiliation**   | Evos      |
| **Actual Health** | 130       |

| **Stat**   | **Value**                                                 |
| ---------- | --------------------------------------------------------- |
| Health     | {{< stat-bar color="green" percentage="20" value="2" >}}  |
| Damage     | {{< stat-bar color="red" percentage="90" value="9" >}}    |
| Survival   | {{< stat-bar color="blue" percentage="40" value="4" >}}   |
| Difficulty | {{< stat-bar color="orange" percentage="30" value="3" >}} |

## Abilities

### Ability 1: Boom Boom

- **Phase:** Blast
- **Cooldown:** None
- **Free:** No
- **Description:** Launch **2** arcing bombs that deal **22** direct damage. If they don't hit a target they leave behind a mine that deals **10** indirect damage and last for **2** turns.
- **Energy Gained:** Gain **7** energy per enemy hit.
- **Target Type:** Grid
- **Target Range:** 3-8

| **Mod Name** | **Description**                                                            | **Cost** | **Type**        |
| ------------ | -------------------------------------------------------------------------- | -------- | --------------- |
| No Downsides | No longer has a minimum range.                                             | 1        | Range Up        |
| Cannoneer    | Increase the arc width for the second bomb.                                | 2        | Range Up        |
| KABOOM Boom  | The first bomb fired deals an additional **4** damage if it hits an enemy. | 2        | Damage Up       |
| Mighty Mines | Increases damage of mines by **3**.                                        | 3        | Damage Up       |
| Triple Fun   | Increases the number of mines to **3**. Direct damage reduced by **5**.    | 3        | Target Increase |

**Default Mod:** Cannoneer

---

### Ability 2: Splort!

- **Phase:** Blast
- **Cooldown:** 4
- **Free:** Yes
- **Description:** Drop mines in all adjacent squares that deal **10** indirect damage and last for **2** turns.
- **Energy Gained:** Gain **7** energy per enemy hit.
- **Target Type:** Self
- **Area of Effect:** 3x3

| **Mod Name**  | **Description**                                                            | **Cost** | **Type**    |
| ------------- | -------------------------------------------------------------------------- | -------- | ----------- |
| Bomb and Run  | Gain **Haste** until the end of the next turn.                             | 1        | Good Status |
| Energy Bank   | Mines give **2** more energy.                                              | 2        | Energy      |
| Long Fuse     | Mines persist for **1** additional turn.                                   | 1        | Duration    |
| Phospho Mines | Enemies hit by mines are **Revealed** until the end of next Decision Mode. | 3        | Bad Status  |
| Longer Fuse   | Mines persist for **2** additional turn.                                   | 2        | Duration    |
| Longest Fuse  | Mines persist for **3** additional turn.                                   | 3        | Duration    |

**Default Mod:** Long Fuse

---

### Ability 3: Big Bang

- **Phase:** Blast
- **Cooldown:** 5
- **Free:** No
- **Description:** Lobs a concussive bomb that deals **25** direct damage and **Knocks Back** enemies.
- **Energy Gained:** Gain **8** energy per enemy hit.
- **Target Type:** Grid
- **Target Range:** 3-7
- **Area of Effect:** 3x3

| **Mod Name**       | **Description**                                                                                                 | **Cost** | **Type**         |
| ------------------ | --------------------------------------------------------------------------------------------------------------- | -------- | ---------------- |
| Bigger Bang        | Increase the size of the explosion to **4x4**. Minimum range is increased by **1**.                             | 1        | Area of Effect   |
| Party Crasher      | Deals **5** more damage for each target hit beyond the first.                                                   | 2        | Damage Up        |
| Got Yer Name On It | If only one target is hit they take **5** additional damage and are **Knocked Back** **2** additional spaces.   | 3        | Damage Up        |
| Blast Force        | **Knockback** distance is increased by **2**.                                                                   | 2        | Special          |
| Recursive Feedback | Deals **5** more damage for each target hit beyond the first. Gain **3** additional energy for each target hit. | 3        | Damage Up&Energy |

**Default Mod:** Blast Force

---

### Ability 4: Bombing Run

- **Phase:** Dash
- **Cooldown:** 7
- **Free:** No
- **Description:** Jump to two locations in quick succession, dealing **20** direct damage to nearby enemies.
- **Energy Gained:** Gain **6** energy per enemy hit.
- **Target Type:** Grid
- **Target Range:** Two sequenced dashes with possible locations placed on a perimeter of a 7x7 square centered around current position.
- **Area of Effect:** 3x3

| **Mod Name**        | **Description**                                         | **Cost** | **Type** |
| ------------------- | ------------------------------------------------------- | -------- | -------- |
| Left You a Present  | Leave **1** mine at each location.                      | 1        | Special  |
| Extra Fuel          | Increase the maximum range of each jump by **1**.       | 2        | Range Up |
| Splortagain         | Resets the cooldown of **Splort!**                      | 2        | Cooldown |
| Explosive Aftermath | Reduce the remaining cooldown of **Big Bang** by **3**. | 3        | Cooldown |

**Default Mod:** Extra Fuel

---

### Ability 5: Maniacal Mayhem

- **Phase:** Blast
- **Energy Cost:** 100 energy
- **Description:** Launches **4** bombs to target locations, dealing **30** direct damage to enemies. Enemies hit by more than one bomb take **8** extra direct damage per bomb. Bombs cannot be placed directly on top of one another.
- **Free:** No
- **Target Type:** Grid
- **Target Range:** 2-8
- **Area of Effect:** 3x3

| **Mod Name**      | **Description**                                                                        | **Cost** | **Type**        |
| ----------------- | -------------------------------------------------------------------------------------- | -------- | --------------- |
| Reloading         | Gain **5** energy for any bomb that deals no damage.                                   | 1        | Energy          |
| Artillery Barrage | Increase range by **3** and widen the arc.                                             | 2        | Range Up        |
| How Many? Six?    | Launch **2** more bombs. Enemies hit by additional bombs only take **5** extra damage. | 2        | Target Increase |
| Minefield         | Leave mines at all bomb locations that don't directly hit an enemy.                    | 3        | Special         |

**Default Mod:** Artillery Barrage

## Dossier

**SKILLS:** Bomb-building, bomb-launching, bomb-bombing.

**KNOWN FOR:** Demolishing a whole wing at EvoS in their release from the lab.

**AGE:** Months past expiration, and counting!

Idd and Odd are vat-grown gremunks who somehow outlived their 30-day expiration date. Despite extensive testing, EvoS found that traditional methods of eliminating gremunculi, like sprays and ointments, were ineffective. Researchers joked that if a disaster destroyed Atlas, Idd and Odd would be the only two left to tell the tale. Eventually, EvoS cut their losses and put the pair's frustratingly persistent health to work instead.

Released from the lab (and their imminent recycle-by date), the gremunks founded Gremolitions, Inc. and proceeded to do what they do best: Blow. Up. Everything.

## Friends

- **Each other**  
  Idd | Odd

## Rivals

- **Each other**  
  Idd | Odd
