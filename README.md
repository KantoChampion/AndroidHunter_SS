# Android Hunter Game Design Document (GDD)

## Table of Contents
1. Game Overview
2. Gameplay Mechanics
3. User Interface Elements
4. Gameplay Goals
5. Exposition and Narrative
6. Technical Details for Unreal Engine 5 Implementation

## 1. Game Overview
**Title:** Android Hunter  
**Genre:** Third-Person Shooter, Action-Adventure  
**Setting:** Dystopian World, Post-Apocalyptic Earth  
**Visual Style:** Dark, Gritty, with a blend of dystopian mechanical and organic elements.  
**Engine:** Unreal Engine 5  
**Target Platform:** PC, Consoles  
**Player Character:** Amber, a resilient and skilled fighter with green hair, known for her agility and sharpshooting skills.  
**Antagonists:** Androids/Husks, mechanically mutated humans seeking to consume blood for energy.  

## 2. Gameplay Mechanics
### 2.1 Movement and Combat
- **Over-the-Shoulder Camera:** Provides immersive gameplay, enhancing shooting accuracy and environmental awareness.
- **Traversal:** Incorporates parkour elements for navigating the sewer system and ruins, including wall-running, vaulting, and climbing.
- **Combat:** Utilizes a mix of ranged and melee combat. Amber can use her pistol for long-range attacks, and acquire upgrades for melee weapons (e.g., electric batons) for close combat.
- **Stealth Mechanics:** Allows Amber to avoid detection by Husks, using the environment to hide or silently take down enemies.

### 2.2 Health and Energy
- **Health System:** Traditional health bar, with med-kits found in the environment for healing.
- **Energy System:** Powers special abilities (e.g., temporary speed boost, enhanced melee damage) and requires blood samples collected from defeated Husks.

### 2.3 Inventory and Upgrades
- **Inventory Management:** Limited slots that require players to choose their carried items wisely.
- **Weapon Upgrades:** Collect materials to upgrade weapons' damage, fire rate, and accuracy.
- **Skill Tree:** Spend experience points to unlock new abilities or enhance existing ones, including stealth tactics, combat proficiency, and traversal skills.

## 3. User Interface Elements
- **HUD:** Minimalistic design displaying health, energy, ammo count, and a compass for navigation.
- **Inventory Screen:** Accessible via pause menu, showing current items, weapons, and available upgrades.
- **Map:** An interactive sewer and surface world map, highlighting objectives, points of interest, and safe zones.
- **Objective Tracker:** Displays current mission objective and waypoints.

## 4. Gameplay Goals
- **Survival:** Navigate through dangerous environments, managing health, ammo, and resources to survive against Husks.
- **Exploration:** Discover hidden paths, resources, and lore about the world's downfall and the origin of the nano-parasite.
- **Combat Proficiency:** Master combat mechanics to efficiently deal with varied enemy types and bosses.
- **Story Progression:** Complete missions to advance the story, uncovering the mystery behind the nano-parasite and fighting to reclaim Earth.

## 5. Exposition and Narrative
The game begins in Amber's bunker, hidden within the sewers. The player learns the basics of movement, combat, and survival through an interactive tutorial. Amber receives a distress signal from the nearby United Rebellion base, urging her assistance. The player's initial goal is to navigate through the sewer system, facing Husk encounters and environmental hazards. Along the way, Amber uncovers clues about the nano-parasite's origins and the fate of humanity. The narrative unfolds through found documents, NPC interactions, and cinematic sequences, driving Amber toward the ultimate goal of finding a way to reverse the mutation and save what remains of the human race.

## 6. Technical Details for Unreal Engine 5 Implementation
### 6.1 Visuals and World Building
- **Nanite:** Utilize Nanite virtualized geometry to create highly detailed environments without compromising performance.
- **Lumen:** Implement Lumen for real-time global illumination to enhance the dark, dystopian atmosphere with dynamic lighting effects.

### 6.2 Character and Enemy Design
- **MetaHuman:** Leverage the MetaHuman framework for creating highly realistic human characters and mutated Husks with detailed facial animations and expressions.

### 6.3 AI and Gameplay
- **AI System:** Develop sophisticated AI for Husks, with behaviors ranging from patrolling areas to aggressively hunting the player upon detection.
- **Blueprints:** Use Blueprints visual scripting to prototype and implement gameplay mechanics quickly, allowing for easy iteration on combat, stealth, and interaction systems.

### 6.4 Audio and Effects
- **Spatial Audio:** Implement spatial audio to enhance immersion, with sounds dynamically adjusting to the environment and player actions.
- **Particle Systems:** Use Unreal Engine's particle system for creating vivid effects for weapons, abilities, and environmental interactions.

By leveraging Unreal Engine 5's advanced features, "Android Hunter" aims to deliver a visually stunning, immersive, and engaging gameplay experience that combines the thrill of survival in a dystopian world with the depth of exploration and narrative progression.
