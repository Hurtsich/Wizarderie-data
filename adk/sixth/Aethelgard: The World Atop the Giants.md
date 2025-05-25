```json
{
  "ruleset_name": "Aethelgard: Fate of the Titans",
  "system_basis": "FATE Core",
  "campaign_setting_overview": "Civilization thrives on the colossal, wandering backs of Titans. Sky-ships connect these living lands, while factions like the Aerie Syndicate and Silent Wardens vie over resources and the Titans' fate.",
  "core_mechanics": {
    "introduction": "These rules adapt the FATE Core system to the world of Aethelgard. Actions are resolved by rolling four Fate Dice (dF), adding a relevant skill rating, and comparing to a difficulty or an opponent's roll. The Ladder describes the quality of success or failure.",
    "the_ladder": [
      {
        "value": 8,
        "descriptor": "Legendary"
      },
      {
        "value": 7,
        "descriptor": "Epic"
      },
      {
        "value": 6,
        "descriptor": "Fantastic"
      },
      {
        "value": 5,
        "descriptor": "Superb"
      },
      {
        "value": 4,
        "descriptor": "Great"
      },
      {
        "value": 3,
        "descriptor": "Good"
      },
      {
        "value": 2,
        "descriptor": "Fair"
      },
      {
        "value": 1,
        "descriptor": "Average"
      },
      {
        "value": 0,
        "descriptor": "Mediocre"
      },
      {
        "value": -1,
        "descriptor": "Poor"
      },
      {
        "value": -2,
        "descriptor": "Terrible"
      }
    ],
    "four_actions": {
      "overcome": "Used to surmount obstacles, like navigating a treacherous Titan pass with Pilot (Sky-Ship) or enduring a Titan's tremor with Physique.",
      "create_an_advantage": "Used to change the situation to your benefit by creating or discovering aspects. Examples include 'Spotting a Weak Point in the Titan-Beast's Armor' with Notice, or 'Calming the Agitated Sky-Currents' with Titan Ken.",
      "attack": "Used to harm opponents in conflicts, whether firing a sky-ship's cannon with Shoot or engaging in a duel on a shifting platform with Fight.",
      "defend": "Used to avoid attacks or the negative effects of someone else Creating an Advantage against you."
    },
    "outcomes": {
      "success_with_style": "Succeed by 3 or more shifts. Gain a boost in addition to normal success.",
      "success": "Beat the difficulty. Achieve your goal.",
      "tie": "Meet the difficulty. Achieve your goal but at a minor cost, or succeed with a minor concession.",
      "failure": "Miss the difficulty. You do not achieve your goal, and there may be consequences.",
      "failure_with_a_cost": "Miss by 3 or more shifts. The GM may offer success at a major cost."
    },
    "fate_points": {
      "purpose": "Fate Points give characters influence over the narrative, reflecting luck, determination, or the subtle currents of destiny in Aethelgard.",
      "earning": [
        "Accepting a compel on one of your aspects (character, situation, Titan-related).",
        "Having one of your character aspects compelled by the GM.",
        "Conceding a conflict before being taken out.",
        "GM awards for excellent roleplaying or clever solutions that embrace the setting's themes (e.g., using Titan knowledge creatively)."
      ],
      "spending": [
        "Invoke an Aspect: Add +2 to a roll or re-roll all four dice. The aspect must be relevant (e.g., invoking 'Aerie Nexus Native' when navigating its complex skyways).",
        "Power a Stunt: Some stunts require a Fate Point to activate their powerful effects.",
        "Refuse a Compel: Avoid the negative consequences of a compel, though this often means forgoing the Fate Point.",
        "Declare a Story Detail: Introduce a plausible fact into the narrative that benefits your character (e.g., 'Of course there's an old smuggler's cache hidden in this Titan crevice!')."
      ],
      "narrative_emphasis": "In Aethelgard, Fate Points can dramatically shift fortunes during perilous sky-voyages, influence the unpredictable behavior of Titans (perhaps calming a minor tremor by declaring a detail about its current state), or sway crucial negotiations between factions."
    }
  },
  "character_creation": {
    "concept": "Characters in Aethelgard are defined by their relationship to the Titans, the skies, and the unique societies built upon them.",
    "aspects": {
      "high_concept": "A phrase describing your character's core identity, often tied to their role or origin (e.g., 'Dashing Sky-Corsair of the Azure Clouds,' 'Titan-Maw Scavenger,' 'Warden Scholar of Aethelgard's Roots').",
      "trouble": "A personal complication or an external problem that consistently makes life interesting (e.g., 'Hunted by Syndicate Enforcers,' 'Uncontrollable Titan-Sense,' 'Crippling Fear of the Below-Lands').",
      "phase_aspects_guide": "Develop three more aspects. Consider these prompts tailored to Aethelgard:",
      "phase_one_titan_connection": "An aspect reflecting your character's origin or significant past experience related to a specific Titan or the general nature of living on them (e.g., 'Born on the Shifting Back of Gorok,' 'Whispers of the Storm-Caller in My Blood,' 'I Understand Terra-Mundi's Groans').",
      "phase_two_skyfaring_allegiance_or_role": "An aspect describing your character's profession, loyalties, or primary function within the world's sky-faring society (e.g., 'Resourceful Independent Sky-Trader,' 'Ace Pilot for the Aerie Syndicate,' 'Guardian of the Ancient Titan Glyphs').",
      "phase_three_defining_relationship_or_ambition": "An aspect about a significant connection to another character, faction, or a driving personal goal in Aethelgard (e.g., 'My Loyalty to Captain Elara is Unshakeable,' 'Must Discover the Secret of the Sky-Fall Prophecy,' 'Will Avenge My Crew Against the Crimson Sky-Pirates')."
    },
    "skills": {
      "list": [
        {"name": "Athletics", "description": "Climbing Titan carapaces, balancing on lurching ground, traversing treacherous sky-ship rigging."},
        {"name": "Burglary", "description": "Infiltrating secure sky-ports, scavenging derelict sky-ships, bypassing Titan-settlement defenses."},
        {"name": "Contacts", "description": "Networking across various sky-ports, knowing key figures within factions, gathering information from the Titan-dwelling communities."},
        {"name": "Crafts", "description": "Repairing sky-ships, fabricating tools from Titan-bone, brewing alchemical concoctions from Titan-flora, understanding Titan-tech."},
        {"name": "Deceive", "description": "Bluffing past Aerie Syndicate patrols, misdirecting rival explorers, spreading rumors in the markets of Aerie Nexus."},
        {"name": "Empathy", "description": "Sensing the subtle 'moods' of a Titan, understanding the diverse cultures of Titan-dwellers, discerning motives in tense negotiations."},
        {"name": "Fight", "description": "Close-quarters combat on unstable Titan terrain or the deck of a sky-ship, defending against Titan-Touched Beasts."},
        {"name": "Investigate", "description": "Tracking Titan migration patterns, uncovering Syndicate plots, searching for lost Titan lore."},
        {"name": "Lore", "description": "Knowledge of Titan biology and behavior, ancient histories of the Great Sundering, faction secrets, sky-navigation principles."},
        {"name": "Notice", "description": "Spotting subtle shifts in Titan terrain, detecting approaching sky-pirates, eavesdropping in crowded sky-taverns."},
        {"name": "Physique", "description": "Enduring the harsh climates atop Titans, hauling heavy cargo, resisting the disorienting effects of Titan movements."},
        {"name": "Pilot (Sky-Ship)", "description": "Maneuvering all forms of aerial transport, from small gliders to massive cargo haulers, through treacherous air currents and around Titan obstacles."},
        {"name": "Provoke", "description": "Intimidating sky-pirates into backing down, goading a rival merchant into a reckless decision, unnerving Titan-Touched creatures."},
        {"name": "Rapport", "description": "Negotiating favorable trade deals, forging alliances between disparate Titan communities, inspiring loyalty in your crew."},
        {"name": "Resources", "description": "Access to wealth, valuable Titan-derived materials, well-equipped sky-ships, or influential backers."},
        {"name": "Shoot", "description": "Operating sky-ship mounted weaponry, personal ranged combat against aerial threats or hostile denizens."},
        {"name": "Stealth", "description": "Moving unseen across a Titan's back, avoiding notice in bustling sky-ports, tailing targets through cloud cover."},
        {"name": "Titan Ken", "description": "NEW SKILL: Understanding specific Titan behaviors and ecosystems, identifying unique Titan-flora and fauna, navigating dangerous Titan-specific terrain, sensing subtle Titan 'moods' or imminent hazards like tremors or gas vents. Can be used to Create Advantages like 'Anticipated the Titan's Lurch' or Overcome challenges like 'Finding Safe Passage Through the Spore Jungle'."},
        {"name": "Will", "description": "Resisting fear induced by colossal Titan events, maintaining focus during perilous sky-maneuvers, enduring psychological pressure from factions."}
      ],
      "distribution": "Typically, one skill at Great (+4), two at Good (+3), three at Fair (+2), and four at Average (+1). All others are Mediocre (+0)."
    },
    "stunts": {
      "description": "Stunts are special abilities that let your character bend or break the rules in specific ways, often tied to their skills or aspects. Each character typically starts with three stunts.",
      "examples": [
        {"name": "Daring Sky-Maneuver (Pilot)", "effect": "Once per session, when piloting a sky-ship, you can spend a Fate Point to automatically succeed with style on an Overcome roll to evade an immediate hazard or navigate a particularly treacherous section of airspace."},
        {"name": "Titan-Sense Empathy (Titan Ken)", "effect": "+2 to Empathy rolls specifically when trying to understand or predict the immediate behavior of a Titan or a Titan-Touched Beast directly influenced by its host Titan's current state."},
        {"name": "Syndicate Insider (Contacts)", "effect": "When dealing with members of the Aerie Syndicate or navigating their controlled territories (like The Shifting Market of Aeridor), you gain +2 to Create Advantages related to leveraging internal knowledge or unofficial channels."},
        {"name": "Warden's Resilience (Will)", "effect": "You gain an additional mild consequence slot that can only be used to absorb stress from Titan-related environmental hazards (e.g., tremors, spore clouds, psychic emanations)."},
        {"name": "Master Scavenger (Crafts)", "effect": "When you succeed with style on a Crafts roll to scavenge or repurpose materials from Titan remains or derelict sky-ships, you gain an additional free invoke on any situation aspects created related to the quality or uniqueness of the salvaged items."},
        {"name": "Sky-Cannon Ace (Shoot)", "effect": "When attacking with a sky-ship's weapon system you are personally operating, gain +1 to your Shoot roll if you Created an Advantage with Pilot on your previous turn related to positioning your vessel."}
      ]
    },
    "refresh": {
      "initial": "Typically starts at 3. Each stunt chosen reduces Refresh by one. Fate Points reset to Refresh at the start of each session."
    },
    "stress_and_consequences": {
      "stress_tracks": "Characters have a Physical stress track and a Mental stress track. Most characters start with 2 stress boxes in each.",
      "consequences": {
        "description": "When stress is absorbed beyond available boxes, characters take consequences. These are aspects representing injury, fatigue, or other hindrances.",
        "types": ["Mild (-2)", "Moderate (-4)", "Severe (-6)"],
        "aethelgard_examples": [
          "Mild: 'Wind-Chapped and Weary,' 'Sprained Ankle from Titan Lurch,' 'Lost a Pouch of Sky-Credits.'",
          "Moderate: 'Damaged Sky-Rigging (Personal Gear),' 'Syndicate Warning,' 'Haunted by the Maw's Echoes.'",
          "Severe: 'Broken Limb,' 'Ship Impounded,' 'Exiled from Aerie Nexus.'"
        ]
      }
    }
  },
  "titan_mechanics": {
    "titan_presence_as_aspects": {
      "description": "The Titan upon which a scene occurs, or those nearby, are always a significant environmental factor. GMs should establish one or more Titan-related situation aspects at the start of scenes set on or near them. Players can also use Create an Advantage with skills like Titan Ken or Notice to identify or leverage these.",
      "examples": [
        "'Terra-Mundi's Ponderous Stability' (Aerie Nexus)",
        "'Quake-Beast's Erratic Tremors' (Shifting Maw)",
        "'Storm-Caller's Crackling Aura'",
        "'Azure Leviathan's Humid Mists'",
        "'Aethelgard's Ancient Stillness'",
        "'Argent Vein's Resonant Hum'"
      ],
      "invocation": "These aspects can be invoked or compelled to affect actions: 'Quake-Beast's Erratic Tremors' might be compelled to cause a character to stumble during a chase, or invoked by a player to make a ranged attack harder for an opponent."
    },
    "titan_events_and_hazards": {
      "description": "Titans are not static. Their movements, biological processes, or environmental interactions create dynamic hazards.",
      "types": [
        {"name": "Sudden Lurch/Tremor", "effect": "Requires Athletics or Pilot rolls to maintain footing/control; can damage structures or create new obstacles."},
        {"name": "Geyser/Vent Eruption (Magma, Gas, Spores)", "effect": "Creates dangerous zones, inflicts stress, or applies temporary negative aspects like 'Blinded by Spores' or 'Noxious Fumes'."},
        {"name": "Shifting Terrain", "effect": "Paths may open or close, structures can become unstable. Titan Ken or Investigate might be needed to find new routes."},
        {"name": "Localized Storms/Wind Shears", "effect": "Specific to Titans like the Storm-Caller or high-altitude regions; hazards for sky-ships and exposed individuals."},
        {"name": "Titan-Touched Beast Activity", "effect": "A Titan's agitation might trigger swarms, awaken dormant creatures, or make local fauna more aggressive."},
        {"name": "Resource Bloom/Scarcity", "effect": "A Titan's cycle might suddenly make a rare resource available or cause a common one to vanish, driving conflict or opportunity."}
      ],
      "resolution": "These are often resolved as Overcome challenges against a set difficulty, or they create new hazardous situation aspects that characters must contend with."
    },
    "titan_mood_or_state_optional": {
      "concept": "For story-critical Titans, the GM can introduce a simple track (e.g., Calm -> Restless -> Agitated -> Disturbed -> Enraged). Player actions, faction activities (like large-scale mining by the Syndicate), or story events can shift this state.",
      "effects": "A Titan's state can influence the frequency and intensity of Titan Events and Hazards, the behavior of its Titan-Touched Beasts, the availability of specific resources, or even create unique atmospheric or psychic phenomena.",
      "example_influence": "A 'Disturbed' Quake-Beast might experience more frequent and violent tremors, making travel across its back significantly more perilous and altering known pathways within the Shifting Maw."
    },
    "titan_ecosystems_and_resources": {
      "resource_gathering": "Characters can use Crafts, Titan Ken, or sometimes Lore to find and harvest unique materials from Titans (e.g., 'Sky-Shards' from Argent Vein, 'Sunpetal Pollen' from Terra-Mundi's high gardens, 'Quake-Crystals' from the Shifting Maw). Success might yield valuable goods; failure or a cost could trigger local hazards or attract protective Titan-Touched Beasts.",
      "titan_touched_beasts": "These creatures are an integral part of Titan ecosystems. Treat them as NPCs or adversaries with their own aspects, skills, and stress/consequences. Their behavior and abilities are often tied to their host Titan (e.g., 'Rock-Hunters' adapted to tremors, 'Sky-Mantises' riding wind currents).",
      "navigating_titan_terrain": "Beyond normal movement, specific Titan features might require unique approaches: Athletics to climb sheer crystalline formations on the Storm-Caller, Pilot (Sky-Ship) to navigate the updrafts around the Azure Leviathan, or Titan Ken to find safe paths through Aethelgard's overgrown, root-choked caverns."
    }
  },
  "sky_ship_rules": {
    "sky_ships_as_entities": {
      "introduction": "Sky-ships are vital to life in Aethelgard and can be treated as significant entities in the game, sometimes akin to characters themselves, especially when they are central to the story.",
      "aspects": "Sky-ships should have at least a High Concept (e.g., 'The Swift Wind,' 'Battered Syndicate Hauler') and a Trouble (e.g., 'Temperamental Starboard Engine,' 'Known Pirate Target'). Additional aspects can describe key features or history ('Reinforced Cargo Hold,' 'Whispers of a Ghost Crew').",
      "ratings_or_skills": "Instead of full skill lists, sky-ships can have ratings (e.g., Speed, Maneuverability, Hull Integrity, Armaments, Sensors, Cargo Capacity) from Average (+1) to Great (+4). Alternatively, the skills of the crew (Pilot, Shoot, Crafts) are used when operating the ship.",
      "stress_and_consequences": "Sky-ships have their own stress tracks (e.g., 'Hull Stress,' 'Rigging Stress,' 'Engine Strain'). Consequences represent damage or systemic issues ('Damaged Rudder -1 Maneuverability,' 'Breached Hull - Constant Leaks,' 'Main Cannon Offline')."
    },
    "sky_ship_operations_and_roles": {
      "pilot": "Uses Pilot (Sky-Ship) for maneuvering, navigating hazards, and positioning in combat.",
      "navigator": "Uses Lore (Sky-Navigation) or Investigate to plot courses between Titans, accounting for their movements, sky-currents, and known hazards. Charts are vital.",
      "engineer": "Uses Crafts to manage ship systems, conduct repairs, and coax extra performance from engines.",
      "gunner(s)": "Uses Shoot to operate the ship's weaponry.",
      "captain": "Uses Rapport or Provoke for command, Empathy for crew morale, and makes strategic decisions."
    },
    "sky_ship_travel": {
      "journeys": "Travel between Titans is an undertaking. Duration depends on distance (which changes as Titans wander), sky-ship speed, prevailing sky-currents, and unforeseen hazards.",
      "hazards_of_the_sky": [
        {"name": "Titan-Storms", "description": "Vast, dangerous weather phenomena, often linked to Titan activity. Navigating them is a significant challenge, potentially a series of Overcome rolls using Pilot, with failures leading to damage (stress/consequences for the ship) or being blown off course."},
        {"name": "Sky-Pirates", "description": "Hostile sky-ships seeking plunder. Leads to sky-ship conflicts or tense negotiations."},
        {"name": "Treacherous Sky-Currents/Anomalies", "description": "Unpredictable air flows, gravity distortions near large Titans, or strange atmospheric phenomena. Requires skilled piloting (Pilot) to navigate safely."},
        {"name": "Titan Proximity Hazards", "description": "Flying too close to an active Titan can expose a ship to direct threats like falling debris, energy discharges (from Storm-Caller), or even physical contact if a Titan moves unexpectedly."},
        {"name": "Resource Depletion", "description": "Running low on fuel ('Sky-Shards' or refined oils), repair parts, or crew supplies can become a pressing issue on long voyages, creating compel-worthy aspects like 'Fuel Tanks Nearly Empty'."}
      ]
    },
    "sky_ship_combat": {
      "zones": "Abstract zones (e.g., Close, Medium, Long Range; Above, Below) are used to manage relative positions.",
      "initiative": "Often determined by Pilot (Sky-Ship) or Notice, depending on who spots whom first.",
      "actions_in_combat": [
        "Maneuver: Pilot (Sky-Ship) to Create an Advantage (e.g., 'Optimal Firing Position,' 'Evasive Cloud Cover') or Overcome obstacles.",
        "Attack: Shoot to fire ship armaments. Damage inflicts stress on the target ship's relevant track.",
        "Repair/System Management: Crafts to make emergency repairs (Overcome to remove a consequence or clear stress) or divert power (Create an Advantage like 'Engines at Full Burn!').",
        "Boarding Actions: If ships are close enough, this becomes a contest (e.g., Pilot to align, Athletics to board) leading to a standard conflict between crews on deck."
      ],
      "scale_and_damage": "Sky-ship weapons are generally more potent than personal arms. Attacks might inflict multiple stress on a hit or have inherent abilities (e.g., a harpoon gun creating 'Snagged and Slowed' aspect on a target)."
    }
  },
  "game_elements": {
    "challenges_contests_conflicts_in_aethelgard": {
      "challenges_examples": [
        "Navigating the Shifting Maw during a Titan-Spasm (series of Pilot, Titan Ken, Notice rolls).",
        "Harvesting rare Lumina Crystals from a deep fissure in Terra-Mundi before a rival crew arrives (Crafts vs. time pressure/environmental hazards).",
        "Deciphering ancient Titan-Warden glyphs to find a safe passage through Aethelgard's petrified heart (Lore challenge)."
      ],
      "contests_examples": [
        "A sky-ship race through the Argent Vein's crystalline spires to claim a newly discovered Sky-Shard deposit (Pilot vs. Pilot contest).",
        "Out-negotiating a shrewd Aerie Syndicate merchant for vital supplies in Aerie Nexus (Rapport or Deceive contest).",
        "A climbing competition up the sheer flank of a dormant Titan, sponsored by a thrill-seeking noble (Athletics contest)."
      ],
      "conflicts_examples": [
        "Defending a fledgling sky-settlement from a squadron of desperate sky-pirates (sky-ship combat followed by personal combat).",
        "A daring raid on an Aerie Syndicate refinery built precariously on the Storm-Caller (Stealth, Burglary, followed by Fight/Shoot).",
        "Confronting a colossal, enraged Titan-Touched Beast threatening a vital trade route (group effort using various skills to attack, create advantages, and defend).",
        "An ideological showdown with Silent Wardens attempting to halt your 'desecration' of a sacred Titan site, potentially escalating to violence."
      ]
    },
    "factions_and_reputation": {
      "introduction": "Allegiances and enmities shape a character's journey in Aethelgard.",
      "major_factions_overview": [
        {"name": "The Aerie Syndicate", "goal": "Profit, resource exploitation, expansion of trade networks. Values skill and opportunism."},
        {"name": "The Silent Wardens", "goal": "Protection of Titans, preservation of balance, understanding ancient Titan lore. Values reverence and wisdom."},
        {"name": "Aerie Nexus Governance", "goal": "Maintaining Aerie Nexus as the primary trade hub, balancing guild interests."},
        {"name": "Maw-Walkers", "goal": "Survival within the Shifting Maw, opportunistic scavenging, upholding tribal traditions."},
        {"name": "Independent Sky-Crews/Settlements", "goal": "Varies widely, from simple survival to carving out their own niche."}
      ],
      "gaining_and_losing_favor": "Actions speak louder than words. Completing tasks for a faction, upholding their values, or damaging their rivals will improve standing. Betrayal, working against their interests, or associating with their enemies will worsen it.",
      "faction_aspects_and_compels": "Significant positive or negative standing can manifest as a situation aspect (e.g., 'Trusted Agent of the Syndicate,' 'Hunted by Warden Zealots'). These can be invoked for benefits or compelled for complications (and Fate Points).",
      "benefits_of_good_standing": "Access to restricted areas (e.g., Syndicate markets, Warden archives), unique faction-specific gear or sky-ship upgrades, safe passage, allies, lucrative missions.",
      "drawbacks_of_poor_standing": "Hostility, being targeted by faction agents, restricted access to settlements or resources, bounties, sabotage."
    },
    "equipment_and_resources_of_aethelgard": {
      "common_gear": "Sky-suits (insulated against cold/wind), climbing harnesses, grappling hooks, personal chronometers, multi-tools, basic weaponry, survival kits.",
      "titan_derived_materials_and_artifacts": {
        "description": "The unique biology and geology of Titans provide rare and valuable resources.",
        "examples": [
          "'Sky-Shards' (Argent Vein): Crystalline energy sources, fuel, currency.",
          "'Resonant Metals' (Argent Vein): Used in advanced sky-ship construction and specialized tools.",
          "'Petrified Titan-Bone' (Aethelgard/Terra-Mundi): Extremely durable building material, carved into art or weapons.",
          "'Azure Leviathan Scales': Lightweight, water-resistant material for clothing or light armor.",
          "'Storm-Caller Crystals': Can store and discharge electrical energy.",
          "'Quake-Gems' (Shifting Maw): Unstable but potent energy sources, alchemical reagents."
        ],
        "acquisition": "Often through dangerous harvesting (Crafts, Titan Ken), trade, or discovery."
      },
      "currency_and_trade": "While barter is common, the Aerie Syndicate promotes the use of 'Syndicate Scrip' or standardized units of valuable Titan resources (like Sky-Shards) as currency in major trade hubs like Aerie Nexus and The Shifting Market of Aeridor. Essential resources like clean water, fresh food, and fuel are always in demand.",
      "sky_ship_upgrades_and_customization": "Improved engines (for speed/efficiency), reinforced hulls (more stress boxes), advanced sensor arrays (better Notice for navigation/detection), specialized weaponry (harpoon launchers, static dischargers), cargo bay expansions, stealth plating."
    }
  },
  "advancement": {
    "milestones": {
      "description": "Characters grow and change by achieving milestones through play.",
      "minor_milestone": "End of a session or a minor plot point resolved. Reward: Swap ratings of two skills, rename one aspect, purchase a new stunt by spending 1 Refresh.",
      "significant_milestone": "Conclusion of a major scenario or plot arc. Reward: Gain a skill point, gain 1 Refresh (up to starting max).",
      "major_milestone": "End of a major campaign arc or truly transformative event. Reward: Gain a skill point, gain 1 Refresh (potentially exceeding starting max), rewrite one aspect, gain an additional stunt slot."
    }
  },
  "game_mastering_aethelgard": {
    "emphasize_the_titans": "Make the Titans active participants. Describe their sounds, their movements, the feel of living on them. Use Titan Events and Hazards to create dynamic scenes. Let players interact with Titan ecosystems in meaningful ways.",
    "sky_high_adventure": "Sky-ship travel should be more than just a transition. Introduce navigational challenges, weather, strange phenomena, and encounters in the vast skies between Titans.",
    "faction_play": "The conflict between the Aerie Syndicate's exploitation and the Silent Wardens' preservation is a core theme. Present players with choices that have consequences for their standing with these and other factions.",
    "discovery_and_mystery": "Aethelgard is full of secrets: lost Titan lore, hidden locations on the Titans' vast bodies, the truth behind historical events like The Great Sundering. Encourage exploration and investigation.",
    "balance_scale": "Juxtapose the immense scale of the Titans with the personal stories of the characters. How do individuals find meaning and make a difference in a world dominated by such colossal forces?"
  }
}
```

