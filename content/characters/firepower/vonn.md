+++
archetype = "home"
title = "Vonn"
+++

**Short Description:** Advanced cyborg who weaponizes supercooled water into shields and projectiles.

| **Role**          | Firepower   |
| ----------------- | ----------- |
| **Affiliation**   | Hyperbotics |
| **Actual Health** | 135         |

| **Stat**   | **Value**                                                 |
| ---------- | --------------------------------------------------------- |
| Health     | {{< stat-bar color="green" percentage="40" value="4" >}}  |
| Damage     | {{< stat-bar color="red" percentage="80" value="8" >}}    |
| Survival   | {{< stat-bar color="blue" percentage="60" value="6" >}}   |
| Difficulty | {{< stat-bar color="orange" percentage="40" value="4" >}} |

## Abilities

### Ability 1: Icebreaker

- **Phase:** Blast
- **Cooldown:** None
- **Free:** No
- **Description:** Launch an icy spike, dealing **30** direct damage and afflicting your target with a **Cryo Core**. **Cryo Core** lasts one turn and is detonated by direct damage to the target, dealing **7** indirect damage to the target and adjacent enemies. Detonated **Cryo Core** grants **2** energy.
- **Energy Gained:** Gain **10** energy if you hit an enemy.
- **Target Type:** Free aim
- **Target Range:** 7

| **Mod Name**  | **Description**                                                                                    | **Cost** | **Type**    |
| ------------- | -------------------------------------------------------------------------------------------------- | -------- | ----------- |
| Heat Sink     | Gain an additional **3** energy if you hit an enemy that started the turn with a **Cryo Core**.    | 1        | Energy      |
| Rangefinder   | Gain **0.5** additional range.                                                                     | 2        | Range Up    |
| Piercing Cold | Pierce the first enemy hit. If another enemy is hit, it gains a **Cryo Core** but takes no damage. | 2        | Effect Size |
| ColdHearted   | Deal an additional **3** damage if you hit an enemy that started the turn with **Cryo Core**.      | 3        | Damage Up   |
| Ice Flow      | Gain **Haste** next turn.                                                                          | 3        | Good Status |

**Default Mod:** Rangefinder

---

### Ability 2: Cold Snap

- **Phase:** Prep
- **Cooldown:** 2
- **Free:** Yes
- **Description:** Grant a freezing aura to Vonn or an ally. If the target is hit with direct damage, the enemy that attacked them takes **5** indirect damage and is afflicted with a **Cryo Core**.
- **Energy Gained:** Gain **3** energy per enemy hit.
- **Target Type:** Grid
- **Target Range:** 8

| **Mod Name**         | **Description**                                                                                 | **Cost** | **Type**    |
| -------------------- | ----------------------------------------------------------------------------------------------- | -------- | ----------- |
| Lingering Chill      | If not triggered by an enemy, the aura lasts **1** additional turn.                             | 1        | Duration    |
| Thermodynamo         | Gain **2** additional energy per **Cryo Core** detonated.                                       | 2        | Energy      |
| Heat Seeking         | Can be targeted through walls.                                                                  | 2        | Range Up    |
| Ice-X                | Grants the **Cold Snap** aura to both Vonn and target Ally, but cooldown is increased by **1**. | 3        | Effect Size |
| Zero Point Generator | The target gains **3** energy each time the effect triggers.                                    | 3        | Energy      |
| Rimescale            | Target also gains **8** shields.                                                                | 2        | Shield      |

**Default Mod:** Heat Seeking

---

### Ability 3: Arctic Blast

- **Phase:** Blast
- **Cooldown:** 3
- **Free:** No
- **Description:** Fire a gale of ice shards, dealing **25** direct damage and **Slowing** enemies.
- **Energy Gained:** Gain **6** energy per target hit.
- **Target Type:** Free aim
- **Target Range:** 7

| **Mod Name** | **Description**                                                                            | **Cost** | **Type**    |
| ------------ | ------------------------------------------------------------------------------------------ | -------- | ----------- |
| Storm Surge  | Gain an additional **3** energy per target hit.                                            | 1        | Energy      |
| Storm Force  | Deal up to **5** more damage to enemies the nearer they are to the center of the targeter. | 2        | Damage Up   |
| North Wind   | Increase arc by **30** degrees.                                                            | 2        | Effect Size |
| Unrelenting  | Cooldown reduced by **1** for each enemy hit that started the turn with a **Cryo Core**.   | 3        | Cooldown    |
| Biting Winds | Reduce cover mitigation by half.                                                           | 3        | Damage Up   |

**Default Mod:** North Wind

---

### Ability 4: Ice Aegis

- **Phase:** Prep
- **Cooldown:** 4
- **Free:** No
- **Description:** Create an icy shell that grants **60** shields and **Slows** nearby enemies. The shields last until end of next turn. This ability allows full movement.
- **Energy Gained:** Gain **5** energy on use.
- **Target Type:** Self
- **Area of Effect:** Radius of **2**

| **Mod Name**  | **Description**                                                                                | **Cost** | **Type**    |
| ------------- | ---------------------------------------------------------------------------------------------- | -------- | ----------- |
| Frozen Solid  | If you are below **60** health, enemy targets are **Rooted**.                                  | 2        | Bad Status  |
| Sub Zero      | If all the shields are destroyed on the first turn, gain **20** shields on the following turn. | 1        | Shield Up   |
| Flashfreeze   | Gain **Haste** for the turn.                                                                   | 2        | Good Status |
| Cold Shoulder | If you are below **60** health, gain **Unstoppable** for the turn.                             | 3        | Good Status |
| Permafrost    | Shields last **1** additional turn.                                                            | 3        | Duration    |

**Default Mod:** Flashfreeze

---

### Ability 5: Polar Vortex

- **Phase:** Blast
- **Energy Cost:** Activation Cost: 100 energy
- **Description:** Summon a raging blizzard that deals **30** direct damage. The blizzard lasts **2** turns, but deals **15** indirect damage on the second turn. Enemies that take damage from the blizzard are **Slowed** until the end of the turn.<br><br>The blizzard can be moved on the second turn as a **Free Action**, causing direct damage instead. Enemies that move through the blizzard will take indirect damage.
- **Free:** No
- **Target Type:** Grid
- **Target Range:** 4
- **Area of Effect:** Cone

| **Mod Name**     | **Description**                                                                                           | **Cost** | **Type**   |
| ---------------- | --------------------------------------------------------------------------------------------------------- | -------- | ---------- |
| Snowed In        | If an enemy is hit by the vortex two turns in a row, they are **Slowed** at the start of their next turn. | 1        | Bad Status |
| Bonechilling     | If an enemy is hit by the vortex two turns in a row, they gain a **Cryo Core**.                           | 2        | Special    |
| Winter Winds     | Increase cast range and second turn movement range by **1**.                                              | 2        | Range Up   |
| Arctic Assault   | Increases the damage of each turn by **3**.                                                               | 3        | Damage Up  |
| Climate Engineer | Lasts **1** additional turn. deals **10** damage on final turn.                                           | 3        | Duration   |

**Default Mod:** Winter Winds

## Dossier

**SKILLS:** Icing enemies. Maintaining his cool in the heat of battle. Keeping produce fresh.

**KNOWN FOR:** Being one of two humans selected for Hyperion's first (official) cybernetic enhancement program.

**LITTLE KNOWN FACT:** "I'm shy. Bookish, even. Takes a surprising effort for me to break the ice."

**BIRTHDAY:** October 23

## Story

A few years prior to the Hyperion Reactor's failure, Vonn (and his twin sister) were selected to be the first true cybernetic soldiers of the city. At a young age, he and his sister were trained to withstand the enormous physical strain that cybernetic enhancement required. After their transformation, they were given advanced upgrades that allowed them to manipulate and weaponize elements. However, due to the Hyperion Reactor's impending failure and their still-unstable condition, their creator, Meridian, put them into an indefinite cryosleep until the day he could restart the Reactor.

Now, with the Hyperion Reactor back online, Vonn has awoken. With his cybernetic enhancements, he can supercool water into projectiles and shields.

## Friends

- **Meridian:** Meridian chose Vonn and his sister to become Hyperion's first element-enhanced cyborgs.

## Rivals

- _(None specified)_
