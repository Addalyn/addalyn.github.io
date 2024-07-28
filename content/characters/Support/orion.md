+++
archetype = "support"
title = "Orion"
+++

**Short Description:** Atom manipulator with a suit specialized to control his power.

| **Role**          | Support |
| ----------------- | ------- |
| **Affiliation**   | Omni    |
| **Actual Health** | 170     |

| **Stat**   | **Value**                                                 |
| ---------- | --------------------------------------------------------- |
| Health     | {{< stat-bar color="green" percentage="60" value="6" >}}  |
| Damage     | {{< stat-bar color="red" percentage="50" value="5" >}}    |
| Survival   | {{< stat-bar color="blue" percentage="50" value="5" >}}   |
| Difficulty | {{< stat-bar color="orange" percentage="80" value="8" >}} |

## Abilities

### Ability 1: Empyreal Ruin

- **Phase:** Blast
- **Cooldown:** None
- **Free:** No
- **Description:** Blast enemies with empyrean energy, dealing 22 direct damage to targets in the center and 16 direct damage to others. Ignores cover.<br><br>**Shards:** Increase outer explosion radius by 10% per shard.
- **Energy Gained:** None
- **Target Type:** Free aim
- **Target Range:** 7
- **Area of Effect:** Cone

| **Mod Name**         | **Description**                                    | **Cost** | **Type**    |
| -------------------- | -------------------------------------------------- | -------- | ----------- |
| Focused Flames       | Deal 3 additional damage if only one enemy is hit. | 1        | Damage Up   |
| Amplified Eruption   | Deal 1 additional damage per shard.                | 2        | Damage Up   |
| Devour Energy        | Gain 3 energy for each enemy hit.                  | 2        | Energy      |
| Empyreal Destruction | The base radius is increased by 20%.               | 3        | Effect Size |
| **Default Mod:**     | Amplified Eruption                                 |          |             |

---

### Ability 2: Fate Transfer

- **Phase:** Prep
- **Cooldown:** 3
- **Free:** No
- **Description:** Grant yourself 15 shields, then redirect 75% of the damage the ally takes this turn. 75% of the damage taken from this ability converts directly into energy.<br><br>**Shards:** You gain additional 3 shields per shard.
- **Energy Gained:** None  
- **Target Type:** Grid
- **Target Range:** 1

| **Mod Name**     | **Description**                                                             | **Cost** | **Type**    |
| ---------------- | --------------------------------------------------------------------------- | -------- | ----------- |
| Shared Agony     | Only take 50% of damage from your ally. They gain 15 shields.               | 1        | Special     |
| Augment Barrier  | Gain an additional 2 shields per shard.                                     | 2        | Shield Up   |
| Rebuild          | Next turn heal 20% of damage redirected through Fate Transfer.              | 2        | Heal        |
| Divine Purpose   | Both you and your target become unstoppable for the turn.                   | 3        | Good Status |
| Energy Leech     | Gain an additional 25% energy from damage redirected through Fate Transfer. | 3        | Energy      |
| **Default Mod:** | Rebuild                                                                     |          |             |

---

### Ability 3: Quantum Core

- **Phase:** Prep
- **Cooldown:** 3
- **Free:** Yes
- **Description:** Target an ally as a focal point of pure energy. When they are hit with a damaging ability, an explosion erupts for 15 indirect damage.
- **Energy Gained:** None
- **Target Type:** Grid
- **Target Range:** 1

| **Mod Name**        | **Description**                                                  | **Cost** | **Type**   |
| ------------------- | ---------------------------------------------------------------- | -------- | ---------- |
| Punish the cowardly | If Quantum Core is not triggered, reduce the cooldown by 1 turn. | 1        | Cooldown   |
| Benevolent          | Target gains 2 shields per shard.                                | 2        | Shield Up  |
| Pain and Gain       | Gain 5 energy per enemy hit.                                     | 2        | Energy     |
| Vengeful            | Deal 2 additional damage per shard.                              | 2        | Damage Up  |
| Bow Down            | Slow enemies hit until end of turn.                              | 3        | Bad Status |
| **Default Mod:**    | Benevolent                                                       |          |            |

---

### Ability 4: Astral Fusion

- **Phase:** Prep
- **Cooldown:** 4
- **Free:** No
- **Description:** Heal your target for 10 health a turn for 2 turns. Heals himself for the first turn's amount if used on an ally.<br><br>**Shards:** Target gains an additional 2 health per turn per shard.
- **Energy Gained:** None
- **Target Type:** Grid
- **Target Range:** 1

| **Mod Name**            | **Description**                                                                 | **Cost** | **Type**  |
| ----------------------- | ------------------------------------------------------------------------------- | -------- | --------- |
| Innate Potency          | Increase healing by 7 per turn. No longer gains any bonus from shards.          | 1        | Heal      |
| Intervention            | Heal an additional 10 health if the target is under the effect of Quantum Core. | 1        | Heal      |
| Enhanced Reconstruction | Increase healing by 1 per shard.                                                | 2        | Heal      |
| Omnipotent              | Can be targeted through walls.                                                  | 2        | Special   |
| Mend the Broken         | If used on an ally below 50% health, they gain 15 shields for the turn.         | 3        | Shield Up |
| **Default Mod:**        | Enhanced Reconstruction                                                         |          |           |

---

### Ability 5: Cosmic Flare

- **Phase:** Blast
- **Energy Cost:** Activation Cost: 100
- **Description:** Consume all shards to gain 30 health and deal 30 direct damage in an area. Gain unstoppable for the turn.<br><br>**Passive:** Gain a shard for every 20 energy held. Half of the damage taken converts into energy. Lose 75% of energy on death. Energize does not affect energy gained through taking damage.
- **Free:** No
- **Target Type:** Free aim
- **Target Range:** 7
- **Area of Effect:** Cone

| **Mod Name**          | **Description**                                                                    | **Cost** | **Type** |
| --------------------- | ---------------------------------------------------------------------------------- | -------- | -------- |
| Almighty              | Gain 3 additional health per enemy hit.                                            | 1        | Heal     |
| Closer to the Conduit | Gain 20 energy on use.                                                             | 2        | Energy   |
| Energy Accumulation   | Each turn you are at maximum energy, increase the healing by 3 to a maximum of 15. | 2        | Heal     |
| Refresh the Source    | Reduce all active cooldowns by 1.                                                  | 3        | Cooldown |
| **Default Mod:**      | Energy Accumulation                                                                |          |          |

## Dossier

**SKILLS:** Cellular conflagration. Self-flagellation.

**KNOWN FOR:** Taking one (or 10) for the team. Without permission.

**HOBBY:** Researching cosmological events, and creating them.

## Story

After witnessing the rematerialization of Aurora in the Reactor, Dr. Orion Strand saw a new future for the Warbotics Experimental Augmentation Division. He theorized that reinforcing the subject’s physical form could allow for even greater energy absorption. Acquiring a black market sample of the regenerative plasma from Project Rask (for a small fee), Orion created a cybernetic suit that would allow a user to withstand the Reactor’s energies. Seeing no reason to give that power to anyone else, Orion strapped on the suit and flipped the switch.

Few would call the resulting implosion a success, and certainly Warbotics isn’t pleased with the equipment and personnel of an entire division being absorbed in the creation of a megalomaniacal demigod. But on the other hand, at least he’s their megalomaniacal demigod.

Now calling himself "The Empyrean," Orion’s existence as a Freelancer provides him with a means to absorb enough energy to survive. But many believe that he has his sights set on the Reactor’s energy in the hopes that absorbing all of it will stabilize his form. Ideally, before it kills him.

## Friends

- **Aurora:** An Aurora poster was found in his Warbotics locker.

## Rivals

- **Quark:** Overheard mumbling something about absorbing Quark's energy.
