The final answer is ```markdown
# Gameplay Rules

## I. Core Gameplay Mechanics

### Dice Pool
When attempting a challenging action, assemble a pool of six-sided dice (d6). The base pool equals the relevant **Attribute** (Grit, Finesse, Acumen, Resolve, Influence; rated 1-5). Add dice equal to your rating in a relevant **Skill** (rated 0-4).

### Successes
Roll the dice pool. Each die showing a **6** is a **Success**.

### Difficulty
The GM sets the **Difficulty** for the task, which is the number of Successes needed (typically 1-5).
*   **Routine (0):** Automatic success (no roll needed unless stressed or hindered).
*   **Easy (1):** Simple task under pressure.
*   **Standard (2):** Requires competence.
*   **Hard (3):** Demands skill and focus.
*   **Challenging (4):** Pushing limits.
*   **Extreme (5+):** Near-impossible feat.

### Pushing Rolls
If you fail a roll (insufficient Successes), you can choose to **Push** it *once*. Reroll any dice that did *not* show a 6. You *must* accept the new result. Pushing a roll inflicts **1 Stress**. You cannot Push a roll that included Stress Dice where a '1' was rolled on any Stress Die (See **Stress Dice** below).

### Stress
Represents accumulated physical and mental strain. Your **Max Stress** equals 5 + Resolve. Track current Stress points.

### Stress Dice
For every point of **Stress** you currently have, add one **Stress Die** (use a different color d6) to *all* future dice pools you roll.
*   Stress Dice generate Successes on a **6**, just like regular dice.
*   If *any* Stress Die rolls a **1**, you suffer a **Panic Effect** *after* resolving the action's success or failure. The GM determines the Panic Effect based on the situation (e.g., freeze, lash out, drop item, hallucinate, gain temporary negative trait, suffer 1 damage bypassing armor). Rolling multiple 1s on Stress Dice might worsen the Panic Effect. (See **Example Panic Effect** in Section VIII).

### Reducing Stress
Stress reduces naturally with rest in a safe Hab-Cluster (1 point per day), or through specific actions, abilities, or successful Resolve checks during downtime.

## II. Combat System

### Initiative
At the start of combat, all participants roll a **Finesse + Alertness** check (Difficulty 1). Order is determined by number of Successes (highest first). Ties are broken by Finesse score, then player choice. NPCs can act on shared initiative slots.

### Combat Rounds
Combat proceeds in rounds. On your turn, you can take **one Standard Action** and **one Move Action**. You can also take **Reactions** when triggered (e.g., dodging).
*   **Standard Actions:** Attack, Use complex tech, Administer first aid, Use certain Skills/Abilities, Aim (+1 die to next attack), Go Defensive (+1 Defense until next turn).
*   **Move Actions:** Move up to your Speed (typically 10m), Stand up, Take cover, Draw/Stow weapon, Simple interaction.
*   **Reactions:** Dodge (Spend reaction to impose -1 die on an incoming attack targeting you). Some abilities grant other reactions. You get one Reaction per round, refreshing at the start of your turn.

### Attacks
*   **Melee:** Roll **Grit + Melee Combat** vs. target's **Defense**.
*   **Ranged:** Roll **Finesse + Ranged Combat** vs. target's **Defense**. Range increments may impose penalties (-1 die per increment beyond optimal).
*   **Defense:** Base Defense is 1 (representing basic evasion). Cover adds to Defense (Light Cover +1, Heavy Cover +2). Some gear or abilities may modify Defense. NPCs have Defense values set by the GM.
*   **Success:** If your Attack Successes equal or exceed the target's Defense, you hit.

### Damage
*   Weapons deal fixed damage (e.g., Knife 2, Pistol 3, Harpoon Gun 4, Ripper Saw 5).
*   Subtract the target's **Armor** value from the damage. Apply remaining damage to **Vitality**.
*   **Vitality:** Your health (5 + Grit). Reaching 0 Vitality incapacitates you (bleeding out, unconscious). Further damage can cause death (GM discretion or specific critical injury rules).
*   **Critical Hit:** If you score 3+ more Successes than needed to hit, you score a Critical Hit. Add +2 damage or inflict a relevant Condition (e.g., Bleeding, Stunned, Impaired Limb).

### Healing
*   **First Aid:** Acumen + Medicine check (Difficulty based on injury severity) stabilizes a dying character or restores 1d3 Vitality. Requires a Medkit charge.
*   **Natural Healing:** Resting in a safe Hab-Cluster restores Vitality (Grit score per day).
*   **Medical Bay:** Advanced facilities restore full Vitality quickly.

### Vehicle Combat (Submersibles/Exosuits)
*   **Stats:** Vehicles have Hull (Vitality), Systems (key functions like Life Support, Sonar, Weapons, Engine), Armor, Speed, and Pressure Depth rating. Exosuits function similarly but are smaller scale. (See also **Submersibles & Exosuits** in Section III).
*   **Actions:** Piloting uses Finesse + Piloting. Gunnery uses Acumen + Gunnery. Damage Control uses Acumen + Mechanics.
*   **Damage:** Attacks target the vehicle. Damage reduces Hull. Critical Hits can damage specific **Systems**, imposing penalties or disabling functions until repaired (Acumen + Mechanics check, requires Parts - See **Resource Management** in Section III).
*   **Scale:** Attacks between characters and vehicles may be ineffective unless using anti-vehicle weapons or targeting weak points (GM call).

## III. Exploration Rules

### Navigation
Traversing the depths requires **Acumen + Navigation** checks. Difficulty depends on visibility, currents, known charts, and sonar quality. Failure can mean getting lost (requiring further checks, consuming resources), encountering hazards, or stumbling into hostile territory.

### Resource Management
Track crucial resources:
*   **Air Supply:** Measured in hours, based on suit/submersible tanks and scrubbers. Consumed over time. Strenuous activity or damaged life support increases consumption. Running out leads to suffocation (Grit checks to resist passing out, then Vitality loss).
*   **Power Cells:** Used by high-tech gear, exosuits, submersibles. Measured in charges or operational hours. Depletion renders tech useless.
*   **Repair Parts:** Generic units used for field repairs (Mechanics checks) and crafting (See **Crafting** in Section VII). Scarcity is common.

### Salvage
Finding resources or useful items requires searching wrecks, ruins, or resource nodes. Roll **Acumen + Perception** (to spot) or **Acumen + Mechanics/Salvage** (to extract). Difficulty based on location and item obscurity/condition. Success yields Parts, Power Cells, data, tech fragments, or other valuables. Failure might trigger hazards or yield nothing.

### Submersibles & Exosuits
Provide life support, pressure resistance, movement, and potentially mounted equipment. Use vehicle stats (Hull, Systems, Armor, Speed, Depth - See **Vehicle Combat** in Section II). Require Power Cells. Damage can compromise life support or mobility. Upgrades (better sonar, manipulator arms, armor plating) may be available via crafting or purchase. Exosuits enhance character Strength (Grit for lifting/melee) and provide limited Air/Power. (See also **Pressure** in Section VI).

## IV. Social Interaction

### Influence Skills
Use **Influence + relevant Skill** (e.g., Persuasion, Intimidation, Deception, Etiquette) to sway NPCs. Opposed by the target's **Resolve + Insight** or a fixed Difficulty based on their disposition and the request's nature. Success grants desired outcome (information, favor, access); failure may worsen disposition or trigger negative consequences.

### Bonds
Represent significant relationships with NPCs, Factions, or even specific locations/ideals. Established through roleplaying and key story moments.
*   **Benefit:** Once per session per Bond, you can invoke it to gain Advantage (reroll 1-2 dice) on a relevant check, gain crucial information, or call in a minor favor.
*   **Risk:** Bonds can be threatened or used against the character, creating story complications.

### Faction Reputation
Track your standing (e.g., -3 Hated to +3 Allied) with key factions (MMC, Veridian, Guild, Wardens, Cultists, etc.). Reputation affects interaction difficulties, access to resources/missions, and potential aid or hostility. Actions taken during missions impact relevant Faction Reputations.

## V. Technology & Chorus Effects

### Using Technology
Basic tech use is automatic. Complex or unfamiliar tech requires an **Acumen + relevant Skill** (Computers, Mechanics, Operate) check. Difficulty based on tech complexity and condition.

### Malfunctions
Pushing rolls involving tech, using damaged tech, or rolling a '1' on a Stress Die during tech use can cause Malfunctions. Effects range from temporary glitches (-1 die on next use) to system shutdowns, power drains, or dangerous feedback (damage, Stress).

### Abyssal Chorus
Psychic/subspace contamination.
*   **Resisting:** Entering Chorus Zones or being targeted by Chorus-affected entities/phenomena requires a **Resolve + Composure** check. Difficulty based on Chorus intensity (1-5+). Failure inflicts Stress, imposes temporary mental Conditions (Confusion, Fear, Paranoia), or causes disturbing hallucinations. Critical failure might lead to temporary madness or lasting psychological scars (new negative Traits). (See also **Chorus Zones** in Section VI).
*   **Interacting:** Some tech might detect or analyze Chorus effects (Acumen + Science/Chorus Lore). Attempting to manipulate Chorus phenomena is extremely dangerous, requiring high Difficulty checks and risking severe consequences (mutation, madness, attracting hostile entities).
*   **Mutations:** Prolonged/intense exposure can cause physical mutations (GM discretion, potentially offering strange benefits alongside drawbacks).

## VI. Environmental Hazards

### Pressure
The deep sea exerts immense pressure. Exceeding a suit/submersible's **Pressure Depth** rating risks hull breaches/suit rupture.
*   **Minor Breach:** Gradual Vitality/Hull loss, increased Air consumption. Requires Grit/Mechanics check to patch.
*   **Major Breach:** Rapid Vitality/Hull loss, potential instant death/destruction. Requires immediate action (sealing breach, reaching shallower depth).
*   Characters outside protection take massive, likely lethal, damage instantly unless possessing extreme biological/technological adaptation. Base **Pressure Tolerance** (1+Grit) offers minimal protection outside suits in emergencies.

### Toxins & Miasma Pockets
Industrial waste, volcanic vents, or pockets of surface Miasma can create toxic zones. Entering requires **Grit + Resilience** checks (Difficulty based on toxicity) each minute/round to avoid taking damage, suffering Conditions (Nausea, Impaired), or suffocating. Proper filtration systems negate this.

### Dangerous Fauna
Mutated megafauna and aggressive deep-sea life. Use standard combat rules (See Section II). Many possess unique attacks (bioluminescence, toxins, sonic bursts, crushing jaws) or high Armor/Vitality. Some may be Chorus-affected, exhibiting unnatural abilities or psychic influence.

### Chorus Zones
Areas of high Chorus concentration. Cause passive Stress gain, require frequent Resolve checks to avoid Panic/Conditions (See **Abyssal Chorus** in Section V), and may feature reality distortions, hostile psychic entities, or environmental anomalies. Tech often malfunctions within these zones (See **Malfunctions** in Section V).

## VII. Optional Systems

### Crafting
Use **Repair Parts** (See **Resource Management** in Section III) and potentially salvaged components to create/repair/upgrade gear. Requires appropriate tools and an **Acumen + Mechanics** check. Difficulty based on item complexity. Schematics or successful Research may be needed for advanced items.

### Research
Analyze salvaged data, biological samples, or Chorus phenomena. Requires time, potentially a lab, and **Acumen + relevant Skill** (Science, Lore, Medicine) checks. Success yields information, insights, potential crafting recipes, or understanding of weaknesses/patterns.

## VIII. Edge Cases & Examples

### Contested Checks
When two characters act against each other directly (e.g., grappling, sneaking past a guard), both roll their relevant pool. The character with more Successes wins.

### Assisting
Another character can Help on a task, granting +1 die to the primary character's pool, if they can reasonably contribute. Requires using their action if in combat.

### Group Checks
When the whole group attempts something (e.g., sneaking, navigating), the GM might call for a Group Check. If at least half the group succeeds on their individual checks, the group succeeds. Failure might mean only the failing characters suffer consequences, or the whole group faces a setback.

### Example Panic Effect (Stress Die '1')
During combat, a character Pushes an attack roll. They succeed but roll a '1' on a Stress Die. GM decides the Panic Effect: "You succeed, hitting the creature, but the recoil and stress make you drop your weapon!" (See **Stress Dice** in Section I).

## IX. Improvisation Guidelines (GM)

### "Yes, and..." / "No, but..."
Encourage player creativity. If a plan is plausible, allow a roll. If it fails, introduce a complication rather than a dead end.

### Attribute + Skill
If no specific Skill fits perfectly, choose the closest one or allow a roll using only the relevant Attribute (potentially at higher Difficulty).

### Setting Difficulty
Use the 1-5 scale as a guideline (See **Difficulty** in Section I). Consider environmental factors, time pressure, and consequences of failure. Standard is 2.

### Consequences
Failure shouldn't always mean damage. Consider lost time, resource depletion, increased Stress, alerted enemies, damaged gear, or negative social reactions.

### Chorus Effects
Be descriptive and unsettling. Use sensory details, psychological manipulation, and temporary rule shifts (e.g., reversed controls, communication static, phantoms).

## X. Balance Considerations

### Resource Scarcity
Ensure Air, Power, and Parts remain valuable. Adjust salvage rates and consumption as needed to maintain tension.

### Stress Economy
Monitor Stress gain and recovery. It should be a threat, but not cripplingly so. Ensure ways to reduce Stress exist but aren't trivial.

### Combat Difficulty
Adjust enemy stats (Vitality, Armor, Damage, Defense) and numbers based on party capabilities and gear. Use environmental hazards to vary encounters.

### Tech Power
Advanced tech should be powerful but come with costs (Power Cells, potential Malfunctions, acquisition difficulty). Avoid trivializing core challenges.

### Chorus Impact
Chorus effects should be impactful and thematic, but allow players chances to resist or overcome them through Resolve, ingenuity, or specific countermeasures.

## XI. Quick Reference Rules

*   **Action Check:** Roll (Attribute + Skill) d6. Need Successes (6s) >= Difficulty.
*   **Pushing:** Reroll non-6s once on a failed roll. Gain 1 Stress. Cannot Push if a Stress Die rolled '1'.
*   **Stress:** Gain Stress from Pushing, Hazards, Chorus. Max Stress = 5 + Resolve.
*   **Stress Dice:** Add 1 die (different color) per Stress point to ALL pools. 6 = Success, 1 = Panic Effect (GM discretion).
*   **Combat Turn:** 1 Standard Action + 1 Move Action + 1 Reaction.
*   **Attack:** (Grit/Finesse + Combat Skill) d6 vs. Target Defense. Hit if Successes >= Defense.
*   **Damage:** Weapon Damage - Armor = Vitality loss. 0 Vitality = Incapacitated.
*   **Resources:** Track Air (hours), Power Cells (charges), Repair Parts (units).
*   **Chorus:** Resist with Resolve + Composure vs. Difficulty. Failure = Stress, Conditions, Hallucinations.
```