+++
archetype = "home"
title = "Phaedra"
+++

**Short Description:** Aggressive, terrain-manipulating hybrid beast powered by an experimental plasma.

| **Role**          | Frontline |
| ----------------- | --------- |
| **Affiliation**   | Evos      |
| **Actual Health** | 180       |

| **Stat**   | **Value**                                                 |
| ---------- | --------------------------------------------------------- |
| Health     | {{< stat-bar color="green" percentage="80" value="8" >}}  |
| Damage     | {{< stat-bar color="red" percentage="40" value="4" >}}    |
| Survival   | {{< stat-bar color="blue" percentage="80" value="8" >}}   |
| Difficulty | {{< stat-bar color="orange" percentage="30" value="3" >}} |

## Abilities

### Ability 1: Seismic Slam

- **Phase:** Blast
- **Cooldown:** None
- **Free:** No
- **Description:** Deal 28 damage to nearby enemies and create a 12 damage shockwave that goes through walls and ignores cover.
- **Energy Gained:** Gain 6 energy per enemy hit.
- **Target Type:** Free aim
- **Target Range:** Melee
- **Area of Effect:** Circle

| **Mod Name** | **Description**                                                     | **Cost** | **Type**   |
| ------------ | ------------------------------------------------------------------- | -------- | ---------- |
| Tremors      | Targets not in line of sight take an additional 5 damage.           | 1        | Damage Up  |
| Caustic Good | When destroying bugs created by Putrid Spray, the target is slowed. | 1        | Bad Status |
| Wind Up      | Increase near damage by 2 and far by 1.                             | 2        | Damage Up  |
| Predator     | Hitting Camo spaces will disable that region.                       | 2        | Special    |
| Stagger      | Adjacent enemies are weakened next turn.                            | 3        | Bad Status |

**Default Mod:** Wind Up

---

### Ability 2: Putrid Spray

- **Phase:** Prep
- **Cooldown:** 4
- **Free:** No
- **Description:** Spray a swarm of bugs, slowing targets. If you hit any of these targets affected by bugs, the insects burst, dealing an additional 12 damage. Bugs last 2 turns.
- **Energy Gained:** Gain 6 energy per enemy hit.
- **Target Type:** Free aim
- **Target Range:** 7
- **Area of Effect:** Line

| **Mod Name**  | **Description**                                                                        | **Cost** | **Type**   |
| ------------- | -------------------------------------------------------------------------------------- | -------- | ---------- |
| Brood         | Reduce the cooldown by 1.                                                              | 1        | Cooldown   |
| Lighting Bugs | If the bugs aren't triggered, the target is revealed until end of next decision phase. | 1        | Bad Status |
| Big Bugs      | Increase the damage done by 3.                                                         | 2        | Damage Up  |
| Juicy Morsels | Gain 5 energy when bugs burst.                                                         | 3        | Energy     |

**Default Mod:** Lighting Bugs

---

### Ability 3: Mending Swarm

- **Phase:** Prep
- **Cooldown:** 4
- **Free:** Yes
- **Description:** 100% of damage taken this turn is recovered over the next 2 turns, up to 80 health.
- **Energy Gained:** Gain 5 energy on use.
- **Target Type:** Self

| **Mod Name**   | **Description**                                                   | **Cost** | **Type**    |
| -------------- | ----------------------------------------------------------------- | -------- | ----------- |
| Taste of Blood | Recover 80% health the turn after but only gain health that turn. | 1        | Heal        |
| Re-Generate    | Reduce the cooldown by 1 if you aren't hit this turn.             | 1        | Cooldown    |
| Chitinous      | Gain 10 shields until end of turn.                                | 2        | Shield Up   |
| Uncontrollable | Gain Unstoppable until end of turn.                               | 2        | Good Status |
| Leech          | Each time you are hit this turn gain 4 energy.                    | 3        | Energy      |

**Default Mod:** Chitinous

---

### Ability 4: Juggernaut

- **Phase:** Dash
- **Cooldown:** 4
- **Free:** No
- **Description:** Charge Forward! When you hit an enemy or travel your maximum range, create a tremor that causes 22 direct damage and slows all enemies hit. Can dash through walls.
- **Energy Gained:** Gain 8 energy per enemy hit.
- **Target Type:** Line
- **Target Range:** 8

| **Mod Name**         | **Description**                                                     | **Cost** | **Type**   |
| -------------------- | ------------------------------------------------------------------- | -------- | ---------- |
| Paralyzing Parasites | When destroying bugs created by Putrid Spray, the target is rooted. | 1        | Bad Status |
| Relentless           | If no enemies are hit, reduce the cooldown of Juggernaut by 1.      | 1        | Cooldown   |
| Ravage               | When directly hitting a target, deal 6 additional damage to them.   | 2        | Damage Up  |
| Battering Ram        | Bursting through walls deals an additional 8 damage to all targets. | 3        | Damage Up  |

**Default Mod:** Ravage

---

### Ability 5: Lair

- **Phase:** Blast
- **Energy Cost:** 100
- **Free:** No
- **Description:** Create a large earthquake around you dealing 30 direct damage. The edges of the lair prevent enemies from moving out of it until the end of next turn.
- **Target Type:** Circle
- **Target Range:** 7
- **Area of Effect:** Circle

| **Mod Name**    | **Description**                            | **Cost** | **Type**    |
| --------------- | ------------------------------------------ | -------- | ----------- |
| Ensnare         | Increase the targeting range by 1.         | 1        | Range Up    |
| Hide and Seek   | Gain vision of the area inside the lair.   | 1        | Special     |
| Earthen Barrier | Allies in the lair gain 15 shields.        | 2        | Shield Up   |
| Aftershock      | Gain Might until the end of next turn.     | 2        | Good Status |
| Broodmother     | Reduce the cooldown on Mending Swarm by 2. | 3        | Cooldown    |

**Default Mod:** Earthen Barrier

## Dossier

**SKILLS:** Terrain manipulation. Terrifying foes… and friends.

**KNOWN FOR:** Turning the Depths into a labyrinth of terror.

**FAVORITE FOOD:** She’ll tell you after she’s eaten you.

Evolution Solutions doesn’t believe in waste. When an experiment goes wrong, they pour old resources into something new. After all, who knows what creature might benefit from an extra set of chitinous legs or toxic fangs?

Thus, Phaedra came into existence. The powerful creature is capable of smashing the ground with such force, she disrupts the terrain around her. The emergence of constantly evolving lairs and labyrinths throughout the Depths suggests that Phaedra has escaped from EvoS repeatedly over the course of her lifetime – most recently during a chaotic break-in at the Trust.

Some terrified citizens claim that Phaedra is the notorious “terror of the Depths,” thought to feast upon the colonies of Gremunks that EvoS has discarded, though others dismiss those tales as myth. However, one only need point to the infamous Grey family massacre to know that some myths do have claws.

## Story

**Friends:**

- **Rask:** Rask’s plasma was a forefather of Phaedra’s. There may be a familial bond… or not?

**Rivals:**

- **Grey:** Phaedra has been witnessed staring at Grey and salivating.

**Trivia:**

- Voiced By: [Lani Minella](http://www.imdb.com/name/nm0591115/?ref_=ttfc_fc_cl_t4)
