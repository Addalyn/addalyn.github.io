+++
archetype = "home"
title = "Magnus"
+++

**Short Description:** Leader of EvoS, capable of controlling any crowd with an iron fist.

| **Role**          | Frontline |
| ----------------- | --------- |
| **Affiliation**   | EvoS      |
| **Actual Health** | 200       |

| **Stat**   | **Value**                                                  |
| ---------- | ---------------------------------------------------------- |
| Health     | {{< stat-bar color="green" percentage="100" value="10" >}} |
| Damage     | {{< stat-bar color="red" percentage="50" value="5" >}}     |
| Survival   | {{< stat-bar color="blue" percentage="70" value="7" >}}    |
| Difficulty | {{< stat-bar color="orange" percentage="50" value="5" >}}  |

## Abilities

### Ability 1: Power Drive

- **Phase:** Blast
- **Cooldown:** None
- **Free:** No
- **Description:** Throw a punch dealing **30** direct damage. This ability gains **1** additional arc range each turn it isn't used, up to a max of **2**. The second range arc deals **25** direct damage and the third range arc deals **20** direct damage.
- **Energy Gained:** Gain **7** energy per target hit.
- **Target Type:** Free aim
- **Target Range:** 1.5/2.5/3.5

| **Mod Name**    | **Description**                                                                                  | **Cost** | **Type**    |
| --------------- | ------------------------------------------------------------------------------------------------ | -------- | ----------- |
| Bonecrusher     | Increase the damage in the second arc by **4** and the third arc by **6**.                       | 3        | Damage Up   |
| Kiss the Ring   | Increase the inner arc damage by **6** if Power Drive is fully charged.                          | 2        | Damage Up   |
| Force Capacitor | Gain **Haste** until end of turn.                                                                | 2        | Good Status |
| Power-Up Glove  | Gain **2** additional energy per enemy hit.                                                      | 1        | Energy      |
| Shatter         | Enemies in the outer two arcs are **Slowed** until end of turn.                                  | 3        | Bad Status  |
| Clobbering Time | If only hitting enemies in the second or third arc, **Power Drive** only loses one arc of range. | 2        | Special     |

**Default Mod:** Force Capacitor

---

### Ability 2: Extinction Event

- **Phase:** Prep
- **Cooldown:** 4
- **Free:** No
- **Description:** Target enemies in an area for assassination. During the next Decision Mode, orbital lasers will lock on to the locations of the targets, and then fire during the subsequent Blast Phase. Deals **24** indirect damage to enemies in the target locations, and **16** to adjacent enemies. Ignores cover.
- **Energy Gained:** Gain **4** energy per enemy targeted and **4** energy per enemy damaged.
- **Target Type:** Grid
- **Target Range:** 6
- **Area of Effect:** Lock: radius of 1.5 & Damage: 3x3

| **Mod Name**      | **Description**                                                                                          | **Cost** | **Type**    |
| ----------------- | -------------------------------------------------------------------------------------------------------- | -------- | ----------- |
| Single Out        | If only one target is selected, damage is increased by **6**.                                            | 2        | Damage Up   |
| Tag Team          | Allies gain **5** energy when dealing direct damage to targets marked by this ability on the first turn. | 1        | Energy      |
| Nowhere to Run    | Increase targeting range by **3**.                                                                       | 3        | Range Up    |
| Protection Racket | Increase the size of the targeter by **33%**.                                                            | 2        | Effect Size |
| Spotter           | Can be targeted through walls.                                                                           | 3        | Range Up    |

**Default Mod:** Protection Racket

---

### Ability 3: Horns Up

- **Phase:** Prep
- **Cooldown:** 2
- **Free:** Yes
- **Description:** Enter a ready stance and gain **20** shields until end of turn. During the next Decision Mode, you can activate this ability to charge in the Dash Phase, dealing **30** direct damage to all enemies hit. Gain 10 shields per enemy hit. This charge will stop if it hits an enemy, but will **Root** that enemy.
If you do not activate this ability again, you will instead gain **20** shields during the Prep Phase that lasts until the end of turn.
- **Energy Gained:** Gain **5** energy on use and **8** energy per enemy hit by the charge.
- **Target Type:** Self/Free Aim
- **Target Range:** 6
- **Area of Effect:** Triple triangles, length 3

| **Mod Name**   | **Description**                                                      | **Cost** | **Type**   |
| -------------- | -------------------------------------------------------------------- | -------- | ---------- |
| Dynomite       | Fully charge **Power Drive** on use.                                 | 2        | Special    |
| Fake Out       | If you don't dash, the cooldown of this ability is reduced by **1**. | 3        | Cooldown   |
| Trample        | **Root** all enemies hit.                                            | 3        | Bad Status |
| Monstrous      | If you dash, gain **5** additional shields per enemy hit.            | 2        | Shield Up  |
| Hardened Frill | Gain **5** additional shields when first activated.                  | 1        | Shield Up  |
| Adaptation     | If you don't dash, gain **20** healing instead of shields.           | 2        | Heal       |

**Default Mod:** Dynomite

---

### Ability 4: Deal Breaker

- **Phase:** Blast
- **Cooldown:** 3
- **Free:** No
- **Description:** Deliver an uppercut that deals **30** direct damage to enemies and **Knocks Back** them to the selected location.
- **Energy Gained:** Gain **10** energy per enemy hit.
- **Target Type:** Free aim
- **Target Range:** 2

| **Mod Name**  | **Description**                                                                                                         | **Cost** | **Type**   |
| ------------- | ----------------------------------------------------------------------------------------------------------------------- | -------- | ---------- |
| Knock Over    | Limits the targeting area to behind you. Increase **Knockback** range by **2**.                                         | 2        | Range Up   |
| Concussion    | Targets hit are **Slowed** until end of next turn.                                                                      | 2        | Bad Status |
| Haymaker      | Deal **6** extra damage if **Power Glove** is fully charged.                                                            | 1        | Damage Up  |
| Suction Punch | Gain **10** shields per target hit until end of next turn.                                                              | 3        | Shield Up  |
| Pinball       | Enemies adjacent to the landing location of an enemy **Knocked Back** by this ability are **Rooted** until end of turn. | 3        | Bad Status |

**Default Mod:** Concussion

---

### Ability 5: Boss Around

- **Phase:** Blast
- **Cooldown:** None
- **Free:** No
- **Description:** Bellow an undeniable command, dealing **33** damage to enemies and forcing them to **Follow** you this turn.
- **Energy Cost:** 100
- **Target Type:** Free aim
- **Target Range:** 6
- **Area of Effect:** Cone

| **Mod Name** | **Description**                                                                                    | **Cost** | **Type**    |
| ------------ | -------------------------------------------------------------------------------------------------- | -------- | ----------- |
| Sonic Boom   | Deal **6** extra damage to nearby targets, reduced by **1** for each square further away they are. | 2        | Damage Up   |
| Big Boss     | Gain **Haste** and **Unstoppable** until end of turn.                                              | 3        | Good Status |
| Follow Up    | Reduce the cooldown on **Deal Breaker** by **1**.                                                  | 1        | Cooldown    |
| Lower Morale | Enemies are made **Weak** until end of next turn.                                                  | 2        | Bad Status  |
| Overtime     | Gain **20** energy per target under the effects of **Unstoppable**.                                | 1        | Energy      |

**Default Mod:** Lower Morale

## Dossier

**SKILLS:** Captivating any audience.

**KNOWN FOR:** Being EvoS' CEO.

**BIGGEST DREAM:** He's already living it!

## Story

**Story:**

Oceanus, the now-fallen megacity, was once home to billions of genetically modified marvels, all loosely allied in the advancement of science and evolutionary variety. According to legend, a young Magnus Pretorius was the first to successfully advocate for stronger leadership, corralling thousands of diverse communities together to form Oceanus' first centralized government. His dedication to city unification was Oceanus' salvation when its Reactor failed, and under his leadership, they secured a new seat of power in Atlas as "Evolution Solutions."

As CEO of EvoS, Magnus earned a reputation as a strict, yet adaptable, leader. As comfortable as he is delegating tasks to others, he's also more than willing to take matters into his own, highly armored hands – evidenced now by his entry into Freelancing, despite a lack of financial or resurrectional need.

"I do what I want," Magnus said, to reporters at HNN when asked about the freelancing bid. "The more interesting question is, does anyone have the bones to stop me?"

**Friends:**

- **Unknown**

**Rivals:**

- **Unknown**

**Trivia:**

- None
