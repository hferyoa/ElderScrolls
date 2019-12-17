# ElderScrolls
A github repo of Elder Scrolls mods I am working on.

# New Racial Abilities

|Race|Name of Racial|Effect of Racial Spell(s)|
|----|---|---|
|Altmer|Zealotry|Once per day: Lower max hitpoints by 10 until you next pray at an altar of the Eight. Your magic abilities gain magnitude, duration, and projectile flight speed the lower your current health is. Can not kill you.|
|Argonian|Shadowscale|Costs 50 Magicka: Become invisible for 60 seconds.|
|Bosmer|Meat Mandate|Gain the ability to eat any creature you kill to regenerate health and stamina. Once per day: Lower max stamina by ten until you next consume a creature you kill. Your movement speed, arrow flight speed, and Muffle %, are all increased the lower your current stamina is.|
|Breton|Will of the Breton|Once per day: Gain 50 maximum Magicka and $% Magicka Regen for 1 hour. Gain slight additional magic resistance, and a chance to absorb incoming spells, the higher your current Magicka stat.|
|Dunmer|Ancestral Teachings|Pick your Ancestral Lineage (your surname will reflect this choice); Pick one of the following abilities. House Redoran: Summon an Ancestral Ghost that attacks enemies with physical weapons and increases your Health while it's alive. House Telvanni: Summon an Ancestral Ghost that attacks enemies with spells and increases your Magicka while it's alive. Houseless: Summon an Ancestral Morag Tong agent that attacks enemies with a bow and increases your Stamina while it's alive.|
|Imperial|Blood of the Empire|Once per day: Gain 50 maximum Health an $% Health Regen for 1 hour. Gain slight physical resistances and increase your Block skill, the higher your current Health stat.|
|Khajiit|Hunter's Stamina|Once per day: Gain 50 maximum Stamina and $% Stamina Regen for 1 hour. Gain slight attack speed and movement speed, the higher your current Stamina stat.|
|Nord|Berserk|Once per day: Lower max Magicka by ten until you next pray at an altar of Talos. Gain physical and magical defenses, as well as increasing your damage dealt, the lower your current Magicka is.|
|Orsimer|Reckless Fury|Costs 50 Health: Your next attack dealt within the next hour will deal 5x damage. Can not kill you.|
|Redguard|The Way of the Sword|Costs 50 Stamina: Summon a spectral sword called a Shehai for 1 hour. The sword has it's own levelling screen similar to the Werewolf and Vampire Lord ones.|


# Combat Magic Overhaul
Cast combat magic with every school of Magic. Grants multiple new spells for all skill levels of each school of magic (exceptt Destruction). I am toying around with two potential mappings of the types of enemy each School can affect:

|School|Enemy List 1|Enemy List 2|
|------|------------|------------|
|Alteration|Automatons|Daedra|
|Conjuration|Daedra|Undead|
|Enchanting|Mer|Automatons|
|Illusion|Humanoids|Animals|
|Restoration|Undead|Humanoids|

Enchanting may not be a viable option; if it is not possible, the possibilities will be:

|School|Enemy List 1|Enemy List 2|
|------|------------|------------|
|Alteration|Automatons|Daedra|
|Conjuration|Daedra|Undead|
|Illusion|Humanoids|Automatons|
|Restoration|Undead|Humanoids|

# Combat Magic Overhaul 2

A combat magic mod that allows the caster to specialise in alternate forms of combat.

|School|Theme|Novice|Apprentice Spells|Adept|Expert|Master|
|------|-----|------|----------|-----|------|------|
|Alteration|Attacking and defending with Dwarven style mechanisms|Creates a steam powered bow and charges an arrow shot with it. This shot uses active perks from the Archery skill, as well as damage perks from *Mage Armor* and Destruction perks|Releases jets of steam, propelling the player backwards and burning enemies in front of the player|Creates a Dwarven Shield that uses steam to position itself and hover in front of the player. The shield will protect the player from one physical or magical attack from that direction, and lasts for 60 seconds|Creates and fires a trap that creates a cloud of steam, burning all creatures nearby when an enemy triggers it|Creates a large warhammer and dashes forward, hitting the first target the player makes contact with and knocking them back|
|Conjuration|Banishing and Summoning Thralls|Cast a summoning circle on the floor. When summoning a creature in the circle, that creature gains health and magicka|Target becomes Marked, and if it dies whilst the Mark is active, revive it as a thrall and capture its soul|All summoned creatures attack the target of this spell|Banish the target. Cast again to summon the target at target location|Ritual: Any Conjuration spell you cast for the next 5 minutes has no cast time|
|Destruction|Summoning of elementals|3 spells, one for each element: Summon an elemental wisp that cannot move and casts Novice level Destruction spells of that element at nearby enemies|3 Spells, one for each element: Summon an elemental mage that can move and cast Apprentice level Destruction spells of that element at nearby enemies|3 Spells, one for each element: Summon an elemental aspect that can move and cast Adept level Destruction spells of that element at nearby enemies|3 spells, one for each element: Summon an elemental familiar that attacks physically with elementally charged attacks|Cast on a summoned elemental to cause the elemental to explode, dealing that element's damage to all nearby enemies|
|Enchanting|Enhance equipped weapons and armor with effects|Left: Attacks with equipped weapons or fists will damage an enemy's stamina. Right: Stamina recharges twice as fast|Left: Attacks with equipped weapons or fists will drain health. Right: Fortify health|Left: Attacks with equipped weapons or fists will deal additional frost damage. Right: Leave an icy wind behind you when you sprint, slowing enemies|Left: Attacks with equipped weapons or fists will deal additional shock damage. Right: Cloak yourself in an electric field, moving faster|Left: Attacks with equipped weapons or fists will deal additional fire damage. Right: Create a ward of fire, damaging the caster of any spell that hits you whilst you have this ward active|
|Illusion|Pranks and Avoiding Fights|Make a sound where the spell hits to distract enemies|Summon an illusory person that runs fron enemies and dies to one attack|Cast on a sleeping enemy to paralyze them and deal health and stamina damage over time|Summon an illusory creature that runs at enemies and fears them|Halve target's HP and cause a frenzied clone to appear near them|
|Restoration|Siphons health and magicka from enemies|Concentration: Deals damage to a target and heals the caster|Drains the target's magicka to restore the player's|Target takes damage over time, if it dies whilst under this effect, heal the player|Drain an enemy's magicka, dealing damage based on the amount of magicka drained|Creates a circle centered on the caster. Enemies within the circle take damage, allies are healed and have their magicka restored over time|

# General Magic Overhaul 

A large magic addition that includes the possibility of using items and other resources to cast stronger spells.

|School|Theme|Novice|Apprentice|Adept|Expert|Master|Notes|
|--|--|--|--|--|--|--|--|
|Alteration|Armor and Cloaks||||||Sacrifice Dwarven ingots to bolster armor or cloak yourself in metal shards, dealing damage.|
|Conjuration|Soul Magic||||||Sacrifice soul gems in your inventory to cast more powerful spells. Drains Azura's Star.|
|Destruction|Blood Magic||||||Sacrifice health instead of magicka to cast spells|
|Enchanting|Disenchanting Options||||||Gives the player more options when disenchanting items.|
|Illusion|Rift Traversal||||||Explore in an ethereal form unable to interact with enemies.|
|Restoration|Soul Transferal||||||Cast on a dead body to lure its soul to your lantern (or doll, if Hearthfire is installed), then cast on another dead body to resurrect it.|



# Own Plane of Oblivion
 
 Discover a small plane of oblivion just for you, complete with a quest detailing the history behind it.


# Skill Tree Overhaul

Overhaul the Skyrim Skill tree page, possibility for retro look and reintroduce certain skills.