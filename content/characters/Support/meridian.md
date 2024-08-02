+++
archetype = "home"
title = "Meridian"
+++

**Short Description:** Hammer-wielding automaton built to defend his allies with the light of Hyperion.

| **Role**          | Support     |
| ----------------- | ----------- |
| **Affiliation**   | Hyperbotics |
| **Actual Health** | 180         |

| **Stat**   | **Value**                                                 |
| ---------- | --------------------------------------------------------- |
| Health     | {{< stat-bar color="green" percentage="60" value="6" >}}  |
| Damage     | {{< stat-bar color="red" percentage="70" value="7" >}}    |
| Survival   | {{< stat-bar color="blue" percentage="50" value="5" >}}   |
| Difficulty | {{< stat-bar color="orange" percentage="30" value="3" >}} |

## Abilities

### Ability 1: Dawnhammer

- **Phase:** Blast
- **Cooldown:** None
- **Free:** No
- **Description:** Smash the ground in front of you, dealing **27** direct damage.
- **Energy Gained:** Gain **8** energy per enemy hit.
- **Target Type:** Free aim
- **Target Range:** 3.5
- **Area of Effect:** Circle

| **Mod Name**  | **Description**                                                     | **Cost** | **Type**    |
| ------------- | ------------------------------------------------------------------- | -------- | ----------- |
| Daybreak      | Gain **4** additional energy per hit while **Zenith** is active.    | 1        | Energy      |
| Blunt Force   | Reduce the effects of cover by half.                                | 2        | Damage Up   |
| Bludgeon      | Deal **4** additional damage in the circle portion of the template. | 3        | Damage Up   |
| Path of Glory | Gain **Haste** until the end of turn.                               | 3        | Good Status |

**Default Mod:** Blunt Force

---

### Ability 2: Reforge

- **Phase:** Prep
- **Cooldown:** 3
- **Free:** No
- **Description:** Heal target ally and yourself for **10** to **32**, based on their missing health. Enemies around the target are made **Weak**. You can target yourself if no ally is in range, but you will not receive twice the healing.
- **Energy Gained:** Gain **10** energy.
- **Target Type:** Self/Ally
- **Target Range:** 8

| **Mod Name**        | **Description**                                                                                  | **Cost** | **Type**    |
| ------------------- | ------------------------------------------------------------------------------------------------ | -------- | ----------- |
| Kinetic Charger     | Gain **5** energy each time you take direct damage on the turn you cast this ability.            | 1        | Energy      |
| Local Anesthetic    | Heal you and your target for an additional **5**, reduced by **1** for each square away you are. | 2        | Heal Up     |
| Field Medic         | You gain **Haste** until end of turn.                                                            | 2        | Good Status |
| Back From The Brink | Increasing the heal amount to your targets by up to **10** more based on missing health.         | 3        | Heal Up     |
| Guiding Light       | Can target through walls.                                                                        | 2        | Range Up    |
| Crusader            | Range of **Reforge** reduced by **2**. **Passive**: Base movement increased by **1**.            | 3        | Special     |

**Default Mod:** Guiding Light

---

### Ability 3: Boneshatter

- **Phase:** Blast
- **Cooldown:** 3
- **Free:** No
- **Description:** Slam enemies for **28** damage. All enemies hit are **Slowed** until end of turn.
- **Energy Gained:** Gain **8** energy per target hit.
- **Target Type:** Free aim
- **Target Range:** 3
- **Area of Effect:** 1/2 of a circle with radius of **3**

| **Mod Name**      | **Description**                                                               | **Cost** | **Type**       |
| ----------------- | ----------------------------------------------------------------------------- | -------- | -------------- |
| Whirling Dynamo   | Gain **4** additional energy per hit while **Zenith** is active.              | 1        | Energy         |
| Kneecapper        | Enemies that dashed this turn are hit for an additional **8** damage.         | 2        | Damage Up      |
| Wallshatter       | Reduce the effects of cover by half.                                          | 2        | Damage Up      |
| Compound Fracture | Hit enemies are also **Weakened** until next turn.                            | 3        | Bad Status     |
| Zealous           | Cooldown of **Boneshatter** is reduced by **1** per enemy hit past the first. | 3        | Cooldown       |
| Conqueror         | Angle of attack increased by **90** degree.                                   | 1        | Area of Effect |

**Default Mod:** Wallshatter

---

### Ability 4: Solar Strike

- **Phase:** Blast
- **Cooldown:** 4
- **Free:** No
- **Description:** Call down your hammer on target location, dealing **24** direct damage and **Revealing** targets in the central ring,and dealing **20** direct damage to targets in the outer ring. Ignores cover.
- **Energy Gained:** Gain **8** energy per enemy hit.
- **Target Type:** Free aim
- **Target Range:** 7
- **Area of Effect:** Circle of radius of **2**

| **Mod Name**    | **Description**                                                        | **Cost** | **Type**   |
| --------------- | ---------------------------------------------------------------------- | -------- | ---------- |
| Heave Ho        | Increase range by **1**.                                               | 1        | Range Up   |
| Shining Justice | Gain **4** additional energy per hit while **Zenith** is active.       | 1        | Energy     |
| Flashpoint      | Increase central damage by **3** for each enemy hit in the outer ring. | 2        | Damage Up  |
| Heavy Justice   | If no target is hit in the center, all targets are **Slowed**.         | 3        | Bad Status |

**Default Mod:** Flashpoint

---

### Ability 5: Zenith

- **Phase:** Prep
- **Cooldown:** 0
- **Free:** Yes
- **Description:** Summon a fusion orb that shields you and your allies for **15** each turn. While active, you are **Unstoppable**. Lasts until deactivated or until the energy cost cannot be paid. Goes on a **2** turn cooldown when disabled.
- **Energy Cost:** Requires **20** energy to cast, but the cost increases by **20** per turn until deactivated.
- **Target Type:** Self
- **Area of Effect:** circle with radius of **3**

| **Mod Name**   | **Description**                                                                   | **Cost** | **Type**  |
| -------------- | --------------------------------------------------------------------------------- | -------- | --------- |
| Sunbathing     | Allies in the aura gain **2** energy, increasing by **2** each turn it is active. | 1        | Energy      |
| Sunblock       | Gain **3** extra self shields per enemy in the aura.                              | 2        | Shield Up   |
| Sunburst       | Allies affected by **Zenith** gain **5** extra healing from **Reforge**.          | 2        | Heal        |
| Praise the Sun | Shielding amount increases by **3** each turn it is active.                       | 3        | Shield Up   |
| Sunstoppable   | Allies also gain **Unstoppable** the first turn it is active.                     | 3        | Good status |

**Default Mod:** Sunblock

## Dossier

**SKILLS:** Killing you with kindness (and also a giant hammer).

**KNOWN FOR:** Keeping the Hyperion Stronghold safe for over a century.

**DEEPEST FEARS:** Failing to restore Hyperion. Being melted by his own hammer. Bugs.

## Story

Whispers of the "miracle maker from Hyperion" preceded Meridian's arrival in Atlas. The paint was dry on his new Trust, Hyperbotics before he'd taken one step into the city. Some say he bribed the Trusts with such incredible wealth, they could rebuild all of Atlas in pure radamantium. As of yet, the city's only major change has been the blue rise of Hyperbotics across the skyline, leaving many to wonder how the ancient automaton marshalled such power so quickly.

His presence inspired immediate loyalty from a number of Freelancer - Brynn in particular. He's also been seen frequently at Zuki's Flying Junkyard, which has created much gossip over whether or not he's had any work done. (For the record, when asked, the prideful automaton insists he's 100% original).

**Friends:**

- **Brynn:** It is widely believed that Meridian (repeatedly) saved the lives of Brynn’s forefathers.

**Rivals:**

- **Rampart:** Meridian reportedly called Rampart a “stripped-screwed punk who wouldn’t know a nut from his head,” much to Rampart's delight.
