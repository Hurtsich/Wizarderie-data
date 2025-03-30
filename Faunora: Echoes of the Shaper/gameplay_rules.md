# Faunora RPG - Gameplay Rules

## Core Gameplay Mechanics

### Dice System
Faunora uses a **d10 dice pool system**. When a character attempts an action where the outcome is uncertain, they roll a number of ten-sided dice (**d10s**) equal to their relevant Core Attribute score plus their applicable Skill Rank. Any bonus dice (e.g., from Specializations, situational advantages, Evolved Traits) are added to this pool, while penalty dice (from Wounds, situational disadvantages) are subtracted (minimum 1 die rolled).

### Target Number (TN)
The standard **Target Number (TN)** for success is **7**. Each die that rolls a 7 or higher is counted as one **Success**.

### Degrees of Success
The number of Successes determines the quality of the outcome:
- **0 Successes:** Failure. The action does not succeed, and there might be negative consequences.
- **1 Success:** Marginal Success. The action succeeds, but just barely, possibly with a minor complication or reduced effect.
- **2 Successes:** Full Success. The action succeeds as intended.
- **3+ Successes:** Critical Success. The action succeeds exceptionally well, potentially providing additional benefits, information, or a more significant effect.

### Opposed Checks
When two characters are directly competing (e.g., Stealth vs Perception, Grapple vs Escape), both roll their relevant dice pools. The character with more Successes wins the contest. Ties usually mean the situation remains unchanged or the acting character fails to overcome the resisting character.

### Untrained Skill Checks
If attempting a task using a Skill in which the character has 0 Ranks, they roll only their relevant Attribute dice pool, and the **TN increases to 8**. Some complex skills (like advanced Technology or specific Lore) cannot be attempted untrained.

### Taking Time
For non-stressful situations where time is not a critical factor, a character can 'Take Time' on a task they are trained in. Instead of rolling, they automatically achieve 1 Success per die they would normally roll (Attribute + Skill Rank), up to a maximum number of successes equal to their Skill Rank. This represents careful, methodical work but takes significantly longer (GM discretion, typically 10x-100x the normal time).

### Resolve Points
Characters start each session with 1 **Resolve Point** (or gain one per major story arc). Spending a Resolve Point allows a player to:
- Reroll all dice of a single check.
- Add 3 automatic Successes to a check after rolling.
- Temporarily ignore the penalties from one Wound Level for one round.
- Gain a narrative advantage (e.g., suddenly remembering a crucial detail, finding a minor useful item, having a contact show up unexpectedly - GM approval required).

## Combat System

### Initiative
At the start of combat, all participants roll **1d10 + INS Attribute**. Results are ranked from highest to lowest to determine the turn order. Ties are broken by the highest INS score, then the highest AGL score.

### Combat Rounds
Combat proceeds in rounds, approximately 6 seconds of in-game time. Each character takes one turn per round in initiative order.

### Action Economy
On their turn, a character can perform:
- 1 **Standard Action** (e.g., Attack, Activate most Evolved Traits, Use complex Skill)
- 1 **Minor Action** (e.g., Move up to half speed, Aim, Draw weapon, Quick interaction)
- Any number of **Reactions** (e.g., Dodge, Parry - if available, specific Trait activations) until their next turn, limited by specific ability rules.

### Movement
Characters can use a **Minor Action** to move up to half their relevant Movement Speed (Walk, Fly, Swim, etc.) or a **Standard Action** to move up to their full Movement Speed. Difficult terrain (rubble, dense foliage, deep water/mud) halves movement speed.

### Attacks
To attack, roll (**Relevant Attribute + Combat Skill Rank**) **d10s**. MGT for most melee, AGL for ranged/finesse melee. Compare the number of Successes to the target's **Defense** value.
- Successes < Defense: Miss.
- Successes >= Defense: Hit. The attack deals damage.

### Defense
Base **Defense** = **5 + AGL + Size Modifier**. Cover grants bonus dice to the defender's effective Defense pool (+1d10 light, +2d10 medium, +4d10 heavy) or increases the Successes needed to hit.

### Damage
Weapon damage is listed as a number of **d10s** (e.g., 3d10). On a hit, roll the weapon's damage dice. Add Melee Damage Bonus (MGT/2, rounded up) to melee damage rolls. Subtract the target's **Soak** value (from armor/natural hide) from the total damage rolled. The remaining damage reduces the target's **Wound Levels**.

### Soak
Armor and natural toughness provide **Soak**, directly reducing incoming damage. Heavy armor might impose penalties on AGL-based skills or movement.

### Wound Levels
Characters have **Wound Levels** instead of hit points. Threshold = **VIT + Size Modifier** (min 1). Damage taken accumulates. When accumulated damage exceeds a threshold, the character moves to the next Wound Level:
- **Healthy** (0 damage)
- **Grazed** (Threshold 1): **-1d10 penalty** to all actions.
- **Hurt** (Threshold 2): **-2d10 penalty** to all actions.
- **Mauled** (Threshold 3): **-4d10 penalty** to all actions. Must make VIT check (TN 7) each round to take any action other than basic movement.
- **Incapacitated** (Threshold 4): Unconscious or otherwise helpless. Further damage may be lethal.

### Healing
Natural healing is slow. Medicine skill checks or specific traits/tech can restore characters up the Wound track. Resting typically recovers SP faster than Wounds.

### Stamina Points (SP) in Combat
Activating Evolved Traits costs **SP**. Managing SP is crucial for characters relying on powers. (See *Magic and Technology* for more on SP).

### Conditions
Various effects can impose conditions: Blinded, Deafened, Grappled, Prone, Slowed, Stunned, Poisoned, Fatigued, etc. Each condition applies specific penalties or limitations (GM details effects).

### Tactical Options
- **Aim** (Minor Action): +1d10 bonus die to next attack roll this turn.
- **All-Out Attack** (Standard Action): +2d10 bonus dice to attack roll, but Defense becomes 5 until next turn.
- **Defend** (Standard Action): Increase Defense by +2 until next turn.
- **Aid Another** (Standard Action): Make a relevant skill check (TN 7). If successful, grant +1d10 bonus die to an ally's next check for the same task.
- **Cover**: Use terrain to increase Defense.
- **Flanking**: If two attackers are on opposite sides of a target, they each gain +1d10 bonus die on melee attacks.
- **Called Shots**: Target specific body parts for effects beyond damage (e.g., disarm, trip). Increases difficulty (GM sets penalty dice or higher TN).

## Exploration Rules

### Travel
Movement speed depends on species and mode (Walk, Fly, Swim, Climb, Burrow). Overland travel speed is affected by terrain type (Plains, Forest, Urban, Mountains, Swamp, etc.). GM determines travel time based on distance, speed, and terrain.

### Navigation
**Survival** skill checks (TN varies by terrain familiarity and conditions) are required for navigating unfamiliar territory, avoiding getting lost, and finding efficient routes. Failure can lead to lost time, encountering hazards, or ending up in the wrong place.

### Perception
Characters use **Perception** skill checks (often opposed by Stealth or against a static DC set by the GM) to notice details, detect hidden objects, spot ambushes, or identify tracks. Specific sense specializations (Sight, Hearing, Scent) grant bonus dice when applicable.

### Investigation
Characters use **Investigation** skill checks to search areas thoroughly, gather clues, analyze evidence, decipher information, or research topics using available resources (libraries, databases, contacts). Success yields information relevant to mysteries or objectives.

### Resource Management
During extended exploration, tracking resources like food, water, ammunition, power sources for tech, and **Stamina Points (SP)** may be necessary. Survival checks can find food/water. SP recovers with rest (e.g., 1 SP per 10 minutes of rest, full recovery after a long rest - 6-8 hours).

### Discoveries and Mysteries
Exploration often leads to discovering new locations, encountering unknown creatures or factions, finding precursor artifacts, or uncovering clues related to the campaign's mysteries. The GM provides descriptions and challenges associated with these discoveries.

### Environmental Interaction
Characters can interact with the environment using skills like Athletics (climbing, swimming, forcing obstacles), Crafting (building shelter, repairing gear), or Technology (interfacing with systems). Species traits (like burrowing, web-spinning, camouflage) offer unique interaction options.

## Social Interaction

### Social Skills
Key skills include **Persuasion** (convincing, negotiating), **Deception** (lying, bluffing), **Intimidation** (threatening, coercing), **Insight** (reading motives, detecting lies), **Etiquette** (navigating social protocols), and **Performance** (influencing through entertainment/speech).

### Social Checks
Attempts to influence NPCs typically involve rolling (**Relevant Attribute + Social Skill Rank**) **d10s**. The TN might be static (based on NPC disposition and request difficulty) or opposed by the NPC's Willpower or Insight check.

### Relationship System
NPC relationships are tracked on a scale (-3 to +3). This score provides bonus or penalty dice (+/- 1d10 per point of relationship) to relevant social checks with that NPC. High positive scores grant access and favors, while negative scores lead to obstruction or hostility.

### Gathering Information
Use **Investigation** (searching records), **Persuasion** (asking nicely), **Intimidation** (demanding answers), **Deception** (tricking info out), or Streetwise/Etiquette (knowing who to ask and how) to gather rumors, facts, and leads.

### Negotiation
Often involves opposed Persuasion or Insight checks. Successes determine how favorable the outcome is. Resources, information, or favors can be bartered.

### Influencing Groups
Leadership skill can be used to coordinate allies, boost morale, or sway crowds. Performance can influence group mood. Large-scale influence may require multiple checks or extended efforts.

### Species and Faction Considerations
Social interactions are heavily influenced by species stereotypes, cultural norms, and faction affiliations. Etiquette specializations are crucial for navigating specific social circles (e.g., Avian Flock Protocols, Corporate Hierarchy). Using the wrong approach can impose penalty dice or automatically fail interactions.

## Magic and Technology

*(**Note:** In Faunora, 'Magic' is represented by Evolved Traits - biological superpowers. This section covers both Evolved Traits and conventional/advanced Technology.)*

### Evolved Traits (Powers)

#### Nature
Biologically-based mutations or evolutionary divergences granting extraordinary abilities (superpowers). Common among Vanguards (heroes) and Marauders (villains).

#### Activation
Most traits require spending **Stamina Points (SP)** and using a specific action type (**Standard, Minor, Reaction**). Some may be passive. Maximum SP = VIT + INS (+Level via Advancement). SP recovers with rest (see *Exploration Rules*).

#### Mechanics
Targeted traits often require a check (Relevant Attribute + Evolved Trait Control Skill - if applicable, or base Attribute) vs target's Defense or a static DC. Successes determine effect intensity. Self-buffs grant bonuses or temporary stats. Area effects usually allow targets a resistance check (e.g., AGL or VIT) for reduced/negated effect.

#### Tiers
Traits are categorized into Tiers (1-3) indicating power level and SP cost. Higher tiers require prerequisite lower tiers and are gained through advancement.

#### Control & Drawbacks
Some powerful traits might require concentration, have limited uses per day, cause fatigue (temporary VIT reduction), or have narrative consequences (attracting attention, environmental damage).

### Technology

#### Scope
Ranges from scavenged pre-human tech to modern animal-adapted devices, advanced **cybernetics**, **bio-tech**, and specialized gear.

#### Usage
Operating complex tech requires the **Technology** skill. Simple devices (like a basic PCD - Personal Communication Device) may not require checks. Repairing, modifying, or bypassing tech uses Crafting (specialization) or Technology checks.

#### Cybernetics
Mechanical or bio-tech augmentations enhancing abilities (e.g., strength limb, enhanced senses, internal tools). Provide passive bonuses or activated abilities, may have integration challenges or power needs.

#### Bio-Technology
Genetic modifications, tailored organisms, symbiotic gear. Often requires Lore (Biology) or Crafting (Bio-Engineering) skills.

#### Interfacing & Hacking
**Technology** skill checks are used to access systems, bypass security, or extract data. Opposed by system security ratings (represented as a TN or opposing dice pool).

#### Crafting Tech
Requires Crafting skill, appropriate tools, materials/components, and potentially schematics or high INT/Lore checks for invention.

### Interaction
Evolved Traits and Technology can interact. Some traits might affect tech (Technopathy, EMP bursts), while some tech might detect or dampen powers. Characters might combine tech gear with their natural or evolved abilities for unique effects (GM adjudication needed).

## Environmental Hazards

### Types
Hazards can be natural or artificial, posing threats during exploration or combat.

### Examples
- **Extreme Weather:** Blizzards, sandstorms, acid rain, hurricanes. Impose penalties on Perception/Ranged Attacks, cause damage (**VIT check** to resist), impede movement. Mitigation: Survival checks for shelter, appropriate gear, Endurance checks.
- **Difficult Terrain:** Rubble, deep snow/mud, thick jungle, zero-gravity. Halves movement speed, may require Athletics checks to traverse. Mitigation: Species traits (flight, climbing), specialized gear (grapples, vehicles).
- **Toxic Zones:** Poison gas, chemical spills, irradiated areas. Cause ongoing damage or conditions (**VIT check** to resist). Mitigation: Respirators, protective suits, Antitoxins, Endurance checks.
- **Extreme Temperatures:** Intense heat or cold. Cause fatigue, damage (**VIT check** to resist). Mitigation: Insulated gear, shelter, Endurance checks.
- **Falling/Collapse:** Unstable structures, pitfalls, rockslides. Cause falling damage (typically 1d10 per 3 meters), may trap characters (Athletics/MGT to escape). Mitigation: Perception checks to spot, **AGL checks** to avoid, Athletics checks to grab hold.
- **Traps:** Mechanical (pressure plates, snares) or technological (laser grids, alarms). Cause damage, restrain, alert enemies. Mitigation: Perception checks to spot, Legerdemain or Technology checks to disarm.
- **Aquatic Hazards:** Strong currents, crushing depths, lack of air. Require Athletics (Swimming) checks, specialized gear (rebreathers, submersibles). Mitigation: Species adaptations, gear, Survival (Aquatic) skill.
- **Electrical Hazards:** Exposed wiring, energy fields. Cause electrical damage, may stun or disable tech. Mitigation: Perception/Technology checks to spot, insulated gear, careful movement (**AGL checks**).

### Detection and Resistance
**Perception** checks often spot hazards. Resisting effects usually involves **VIT** (for poisons, temperature, fatigue), **AGL** (dodging traps/falling objects), or Endurance checks. Specific skills like Survival or Technology might mitigate certain hazards.

## Optional Systems

- **Detailed Crafting & Invention:** Rules for gathering specific materials, requiring schematics or invention rolls (INT + Crafting/Lore), and time investment to create custom gear, gadgets, or bio-mods.
- **Faction Reputation:** A numerical system tracking standing with major factions (Vanguards, City Corps, Marauder Cells, Guilds, Species Groups). Actions grant/lose reputation, affecting access, prices, quests, and NPC reactions on a larger scale than individual relationships.
- **Vehicle Combat:** Expanded rules for chases and combat involving vehicles (land, air, sea). Includes vehicle stats (Speed, Handling, Armor, Weapons), Piloting skill checks for maneuvers, targeting systems, and damage effects specific to vehicles.
- **Detailed Downtime:** Structured rules for activities between adventures: training skills, crafting, researching, networking (improving Relationships/Faction Standing), recuperating from long-term injuries, or pursuing personal goals.
- **Morale System:** Rules for NPC groups (allies or enemies) potentially breaking and fleeing combat based on casualties, facing fearsome foes (Intimidation), or leadership presence.
- **Advanced Social Maneuvering:** More complex social encounters using multiple checks over time to sway opinions, build arguments, or conduct intricate deceptions, potentially involving social 'hit points' or influence tracks.
- **Environmental Storytelling:** Mechanics encouraging players to use Investigation or Perception on the environment itself to piece together past events or gain clues, potentially granting bonus dice or narrative insights.

## Edge Cases and Examples

- **Combining Evolved Traits:** GM determines if two traits can be used simultaneously. If synergistic (e.g., Flight + Ranged Attack), usually allowed. If requiring conflicting actions or focus, may require higher SP cost, concentration check (INS), or be disallowed. Example: Using [Tier 2] Chameleon Skin while making a loud [Tier 2] Cryo Blast attack would likely negate the stealth benefit.
- **Unconventional Skill Use:** Players propose using skills creatively (e.g., Intimidation via Performance, Athletics to create distractions). GM sets TN based on plausibility and effectiveness. Example: Using Crafting (Weaving) to quickly create a net trap during combat might require a high TN (9+) and take a Standard Action.
- **Species Trait vs. Environment:** How does a Bat's Echolocation work in a sound-dampened room? (Likely ineffective or heavily penalized). Can a Fish character operate complex machinery designed for paws? (May require AGL checks with penalty dice unless adapted tech exists). GM makes rulings based on logic and narrative.
- **Ambiguous Power Effects:** A player uses [Tier 3] Dominate Mind to order an enemy to 'stop fighting'. Does this mean drop weapons, run away, or just stand still? GM interprets based on successes and NPC's personality, potentially allowing an Insight/Willpower check to interpret vaguely.
- **Technology vs. Nature:** Can a character with Technopathy interface with purely biological systems enhanced by bio-tech? (GM decision: maybe simple commands, but not complex reprogramming). Can natural EMP pulses (like from an Electric Eel trait) disable advanced cybernetics? (Likely yes, possibly requiring a VIT check from the cybered individual to resist system shock).
- **Damage Types and Resistances:** If a character with fire resistance (Evolved Trait) is hit by an explosion, do they resist all damage or just the fire part? (GM decides based on trait description; likely resists fire portion, takes physical impact damage unless specified otherwise).
- **Social Edge Cases:** Using Deception to impersonate someone well-known might require Performance checks in addition to Deception, and face higher scrutiny (Insight checks from observers). Trying to Persuade a hostile creature that doesn't share a language might be impossible or require unique approaches (Performance, gestures, species-specific displays).

## Improvisation Guidelines (GM Guidance)

### Setting Target Numbers (TNs) / Difficulty Classes (DCs)
Use this scale as a baseline:
- **Easy (TN 6 / DC 1 Success):** Routine task, favorable conditions.
- **Moderate (TN 7 / DC 2 Successes):** Standard difficulty, requires competence.
- **Hard (TN 8 / DC 3 Successes):** Challenging task, requires skill and focus.
- **Very Hard (TN 9 / DC 4 Successes):** Requires expertise, luck, or resources.
- **Nearly Impossible (TN 10 / DC 5+ Successes):** Pushing the limits of capability.
Adjust based on circumstances, tools, assistance, and opposition.

### Handling Unexpected Player Actions
Embrace creativity. Ask 'What are you trying to achieve?'. Determine the relevant Attribute/Skill (or Attribute if untrained). Set a **TN** based on difficulty and risk. Don't shut down ideas outright unless truly impossible; instead, outline potential consequences or require multiple checks.

### Adjudicating Unique Trait/Skill Uses
If a player uses an ability in a way not explicitly covered, assess the intent and compare it to existing effects. Is it similar to another trait/skill? Does it make narrative sense? Assign an **SP cost** or **TN** appropriate to its power level and complexity. Prioritize consistency and fun.

### Managing Narrative Flow
Use descriptions to set the scene and convey consequences. If rules checks slow things down too much during non-critical moments, opt for narrative resolution or a single representative check. Keep the story moving, but use mechanics to highlight moments of tension and uncertainty.

### Failing Forward
When players fail a check, especially for crucial tasks (like finding a clue), consider **'failing forward'**. They don't get what they wanted, but the story still progresses, perhaps with a complication, delay, partial success, or discovery of a different, related problem. Example: Failing an Investigation check doesn't mean no clues exist, but maybe they find a misleading clue, alert security, or take too long.

### When to Bend the Rules
The rules serve the story and fun. If a strict ruling feels anticlimactic, illogical in context, or hinders enjoyment significantly, the GM can bend or override it. Explain the reasoning if necessary. Consistency is good, but adaptability is key for a dynamic campaign.

### Leveraging Species Differences
Constantly consider how different species perceive, interact with, and are affected by the world. A scent-based clue is useless to most birds but vital to canids. A tight crawlspace is easy for a rat but impossible for a rhino. Use these differences to create unique challenges and opportunities.

## Balance Considerations (GM Guidance)

### Encounter Design
Balance combat encounters by considering:
- Number of opponents vs PCs.
- NPC Stats & Skills: Adjust dice pools relative to PCs.
- NPC Evolved Traits/Special Abilities: Use sparingly for rank-and-file, reserve powerful abilities for leaders/bosses.
- Environment: Use terrain, hazards, and cover to modify difficulty.
- Action Economy: Ensure NPCs don't overwhelm PC actions, or vice-versa, unless intended.
- Synergy: Consider how NPC abilities work together.

### Player Power Levels
Monitor the impact of Evolved Traits and high-end gear. Ensure challenges remain relevant as PCs advance. Milestone progression helps keep the party relatively balanced. If one PC vastly outshines others, consider tailored challenges or spotlight opportunities for less powerful characters.

### Evolved Trait Costs & Effects
Ensure **SP costs** reflect the power and utility of traits. Tier 3 traits should feel impactful but costly. Review traits that seem overly dominant or weak and consider minor adjustments (SP cost, duration, dice bonus/penalty) via Evolution Points or narrative events.

### Resource Management
**SP**, ammo, and consumables should matter. Encounters that drain resources without easy replenishment increase tension. Adjust recovery rates based on campaign pace and style.

### Skill Viability
Ensure a range of skills are useful. Provide opportunities for social, exploration, and knowledge skills to be as impactful as combat skills in achieving objectives. Avoid situations where only combat prowess matters.

### Species Balance
While species have unique advantages, ensure these don't make some choices inherently superior in all situations. Highlight scenarios where different species traits shine. Attribute modifiers should balance out.

### Gear Progression
Control access to powerful weapons, armor, and cybernetics. Link significant upgrades to major milestones, difficult quests, or high costs.

### Narrative vs. Mechanics
Balance mechanical power with narrative consequences. Using devastating powers might attract unwanted attention or cause collateral damage, creating new problems.

## Quick Reference Rules

- **Core Mechanic:** Roll (**Attribute + Skill Rank + Bonus Dice - Penalty Dice**) **d10s**. Each **7+** = 1 Success.
- **Target Numbers (TN):** Standard **TN 7**. Untrained **TN 8**.
- **Success Levels:** 0=Fail, 1=Marginal, 2=Full, 3+=Critical.
- **Combat Turn:** 1 **Standard Action**, 1 **Minor Action**, **Reactions**.
- **Common Actions:**
    - **Attack** (Standard): (Att + Skill) d10s vs Defense.
    - **Move** (Minor): Half speed.
    - **Move** (Standard): Full speed.
    - **Activate Trait** (Varies): Costs SP, action type varies.
    - **Aim** (Minor): +1d10 to next attack this turn.
    - **Defend** (Standard): +2 Defense until next turn.
    - **Aid Another** (Standard): Skill check (TN 7) to grant ally +1d10.
- **Defense:** Base **5 + AGL + Size Mod**. Cover adds bonus dice.
- **Damage:** Roll Weapon d10s + MGT Bonus (melee) - **Soak**.
- **Wound Penalties:** Grazed **-1d10**, Hurt **-2d10**, Mauled **-4d10** & VIT check to act.
- **Wound Threshold:** **VIT + Size Mod** per level.
- **Stamina Points (SP):** Max = **VIT + INS** (+Level via Advancement). Used for Evolved Traits. Recover with rest.
- **Resolve Point:** 1 per session/arc. Reroll check, +3 Successes, Ignore Wound penalty (1 round), Narrative Edit (GM OK).