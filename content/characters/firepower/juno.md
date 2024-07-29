+++
archetype = "home"
title = "Juno"
+++

**Short Description:** A twin cannon-wielding warrior who stands her ground no matter the odds.

| **Role**          | Firepower |
| ----------------- | --------- |
| **Affiliation**   | Omni      |
| **Actual Health** | 150       |

| **Stat**   | **Value**                                                 |
| ---------- | --------------------------------------------------------- |
| Health     | {{< stat-bar color="green" percentage="50" value="5" >}}  |
| Damage     | {{< stat-bar color="red" percentage="80" value="8" >}}    |
| Survival   | {{< stat-bar color="blue" percentage="60" value="5" >}}   |
| Difficulty | {{< stat-bar color="orange" percentage="30" value="3" >}} |

## Abilities

### Ability 1: Laser Barrage

- **Phase:** Blast
- **Cooldown:** None
- **Free:** No
- **Description:** Fire a barrage of lasers from each cannon. Targets take 24 direct damage, or 32 if hit by both laser barrages.
- **Energy Gained:** Gain 6 energy per enemy hit.
- **Target Type:** Free aim
- **Target Range:** 7.5
- **Area of Effect:** Cone

| **Mod Name**      | **Description**                                                                      | **Cost** | **Type**    |
| ----------------- | ------------------------------------------------------------------------------------ | -------- | ----------- |
| Minigun Mayhem    | Enemies hit by one barrage take an additional 4 damage.                              | 1        | Damage Up   |
| Concentrated Fire | Enemies hit by overlapping barrages take an additional 4 damage.                     | 2        | Damage Up   |
| Fire At Will      | Increase the size of the barrage by 40%.                                             | 2        | Effect Size |
| Spinning Up       | Using Laser Barrage increases the energy gain of Laser Barrage next turn by 4.       | 3        | Energy      |

**Default Mod:** Concentrated Fire

---

### Ability 2: Lockdown

- **Phase:** Prep
- **Cooldown:** 3
- **Free:** No
- **Description:** Tether a target to their current position for the turn; if they move further than 2 spaces away, they take 30 indirect damage.
- **Energy Gained:** Gain 12 energy if damage is dealt.
- **Target Type:** Grid
- **Target Range:** 7

| **Mod Name**     | **Description**                                                    | **Cost** | **Type**   |
| ---------------- | ------------------------------------------------------------------ | -------- | ---------- |
| Maximum Security | Cooldown is reduced by 1 turn if Lockdown doesn't trigger.         | 1        | Cooldown   |
| Floodlights      | Reveal the target until the end of next Decision Mode.             | 2        | Bad Status |
| Watch Your Step  | Increase damage by 1 per square traveled.                          | 2        | Damage Up  |
| Watchful Eye     | Pierce the first target hit. Reduces damage by 10.                 | 2        | Special    |
| Stockades        | If Lockdown is triggered, the target is scrambled next turn.       | 3        | Bad Status |

**Default Mod:** Watch Your Step

---

### Ability 3: Off Limits

- **Phase:** Blast
- **Cooldown:** 4
- **Free:** No
- **Description:** Create a shockwave dealing 25 direct damage. Knockback enemies hit by up to 2 squares.
- **Energy Gained:** Gain 8 energy per enemy hit.
- **Target Type:** Free aim
- **Target Range:** 4
- **Area of Effect:** Cone

| **Mod Name** | **Description**                                     | **Cost** | **Type**    |
| ------------ | --------------------------------------------------- | -------- | ----------- |
| Shockwave    | Increases the damage of Off Limits by 3.            | 1        | Damage Up   |
| Knockout     | Increase the distance of the knockback by 2.        | 2        | Special     |
| Seeing Stars | Adjacent enemies are additionally Slow next turn.   | 2        | Bad Status  |
| Showstopper  | Increase the size of the arc by 33%.                | 3        | Effect Size |

**Default Mod:** Knockout

---

### Ability 4: Riot Shield

- **Phase:** Prep
- **Cooldown:** 3
- **Free:** Yes
- **Description:** Create an electrical barrier, generating 40 shields.
- **Energy Gained:** Gain 5 energy on use.
- **Target Type:** Self

| **Mod Name**   | **Description**                                                          | **Cost** | **Type**  |
| -------------- | ------------------------------------------------------------------------ | -------- | --------- |
| Reboot         | Reduce the cooldown by 1 if the shield takes no damage.                  | 1        | Cooldown  |
| Fortification  | Grant 10 shields to adjacent allies.                                     | 1        | Cooldown  |
| Hold the Line  | Gain 10 additional shields if used while Lay Down the Law is active.     | 2        | Shield Up |
| Overcharge     | Gain 1 energy per 5 damage that the shield absorbs.                      | 2        | Energy    |
| Shield Battery | Lasts until end of next turn.                                            | 3        | Special   |

**Default Mod:** Overcharge

---

### Ability 5: Lay Down the Law

- **Phase:** Blast
- **Energy Cost:** Activation Cost: 50 energy<br>Sweep Cost: 20 energy
- **Description:** Anchor to the ground and unleash a superheated beam in a direction. Deals 38 direct damage and any enemies that move through the beam take 38 indirect damage. Can be used again on subsequent turns to sweep the beam. You cannot move and are Unstoppable while using this ability.
- **Free:** No
- **Target Type:** Free aim
- **Target Range:** 7
- **Area of Effect:** 90° cone

| **Mod Name**               | **Description**                                                                                      | **Cost** | **Type**    |
| -------------------------- | ---------------------------------------------------------------------------------------------------- | -------- | ----------- |
| Dancing Shoes              | Gain Haste when de-anchoring.                                                                        | 1        | Good Status |
| Indiscriminate Destruction | Increase the arc of the sweep by 33%.                                                                | 1        | Effect Size |
| Efficient Extermination    | Reduce initial energy cost by 10.                                                                    | 2        | Energy      |
| High Intensity             | Deal up to 7 extra damage to nearby targets, reduced by 1 for each square further away they are.     | 2        | Damage Up   |
| Heating Up                 | Increase the damage by 5 each turn you are anchored, capping at 15 additional damage.                | 3        | Damage Up   |

**Default Mod:** Efficient Extermination

## Dossier

**SKILLS:** Captivating any audience.

**KNOWN FOR:** Being Omni's Head of Security.

**BIGGEST DREAM:** She's already living it!

## Story

**Friends:**

- **Asana:** Seen having lunch at Omni-Plex.

**Rivals:**

- **Celeste:** Juno has some strong suspicions about Celeste’s involvement in Omni break-ins.

**Trivia:**

- Voiced By: [Mara Junot](http://www.imdb.com/name/nm5235708/?ref_=ttfc_fc_cl_t2)
