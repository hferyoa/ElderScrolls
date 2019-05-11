# ElderScrolls
A github repo of Elder Scrolls mods I am working on.

# New Racial Abilities

|Race|Name of Racial|Effect of Racial Spell(s)|
|----|---|---|
|Altmer|Zealotry|Once per day: Lower max hitpoints by ten until you next pray at an altar of the Eight. Your magic abilities gain magnitude, duration, and projectile flight speed the lower your current health is. Can not kill you.|
|Argonian|Shadowscale|Costs 50 Magicka: Become invisible for 60 seconds.|
|Bosmer|Meat Mandate|Gain the ability to eat any creature you kill to regenerate health and stamina. Once per day: Lower max stamina by ten until you next consume a creature you kill. Your movement speed, arrow flight speed, and sneak skill, are all increased the lower your current stamina is.|
|Breton|Will of the Breton|Once per day: Gain 50 maximum Magicka for 1 hour. Gain  slight additional magic resistance, and a chance to absorb incoming spells, the higher your current Magicka stat.|
|Dunmer|Ancestral Teachings|Pick your Ancestral Lineage; Pick one of the following abilities. House Redoran: Summon an Ancestral Ghost that attacks enemies with physical weapons and increases your Health while it's alive. House Telvanni: Summon an Ancestral Ghost that attacks enemies with spells and increases yiour Magicka while it's alive. Houseless: Summon an Ancestral Morag Tong agent that attacks enemies with a bow and increases your Stamina while it's alive.|
|Imperial|Blood of the Empire|Once per day: Gain 50 maximum Health for 1 hour. Gain slight physical resistances and increase your Block skill, the higher your current Health stat.|
|Khajiit|Hunter's Stamina|Once per day: Gain 50 maximum Stamina for 1 hour. Gain slight attack speed and movement speed, the higher your current Stamina stat.|
|Nord|Berserk|Once per day: Lower max magicka by ten until you next pray at an altar of Talos, or equip an Amulet of Talos. Gain physical and magical defenses, as well as increasing your damage dealt, the lower your current Magicka is.|
|Orsimer|Reckless Fury|Costs 50 Health: Your next attack dealt within the next hour will deal 5x damage. Can not kill you.|
|Redguard|The Way of the Sword|Costs 50 Stamina: Summon a spectral sword called a Shehai for 1 hour. The sword is levelled to you, and above level 40, it will start gaining Enchantments.|


# Combat Magic Overhaul
Cast combat magic with every school of Magic. Grants multiple new spells for all skill levels of each school of magic. I am toying around with two potential mappings of the types of enemy each School can affect:

|School|Enemy List 1|Enemy List 2|
|------|------------|------------|
|Alteration|Automatons|Daedra|
|Conjuration|Daedra|Undead|
|Destruction|Animals|Man|
|Enchanting|Mer|Automatons|
|Illusion|Man|Animals|
|Restoration|Undead|Mer|

Enchanting may not be a viable option, I may need to attempt to script it in Papyrus, which will take longer and may not be possible.

If it is not possible to include spells for Enchanting, the possibilities will be:

|School|Enemy List 1|Enemy List 2|
|------|------------|------------|
|Alteration|Automatons|Daedra|
|Conjuration|Daedra|Undead|
|Destruction|Animals|Automatons|
|Illusion|Humanoids|Animals|
|Restoration|Undead|Humanoids|

# Combat Magic Overhaul 2

A smaller combat magic mod that allows the caster to specialise in alternate forms of combat. May be game breaking.

|School|Theme|Novice|Apprentice Spells|Adept|Expert|Master|
|------|-----|------|----------|-----|------|------|
|Alteration|Attacking and defending with Dwarven style mechanisms|Creates a steam powered bow and charges an arrow shot with it. This shot uses active perks from the Archery skill, as well as damage perks from *Mage Armor* and Destruction perks|Releases jets of steam, propelling the player backwards and burning enemies in front of the player|Creates a Dwarven Shield that uses steam to position itself and hover in front of the player. The shield will protect the player from one physical or magical attack from that direction, and lasts for 60 seconds|Creates and fires a trap that creates a cloud of steam, burning all creatures nearby when an enemy triggers it|Creates a large warhammer and dashes forward, hitting the first target the player makes contact with and knocking them back|
|Conjuration|Banishing and Summoning Thralls|Cast a summoning circle on the floor. When summoning a creature in the circle, that creature gains health and magicka|Target becomes Marked, and if it dies whilst the Mark is active, revive it as a thrall and capture its soul|All summoned creatures attack the target of this spell|Banish the target. Cast again to summon the target at target location|1) Cast a circle on the ground, dealing damage over time to all enemies and banishing enemies who die whilst under this spell's influence. 2) Summon an enemy banished from the first spell's effect.|
|Destruction|Summoning of elementals|3 spells, one for each element: Summon an elemental familiar that attacks physically with elementally charged attacks|3 spells, one for each element: Summon an elemental wisp that cannot move and casts Novice level Destruction spells of that element at nearby enemies|3 Spells, one for each element: Summon an elemental mage that can move and cast Apprentice level Destruction spells of that element at nearby enemies|3 Spells, one for each element: Summon an elemental aspect that can move and cast Adept level Destruction spells of that element at nearby enemies|Cast on a summoned elemental to cause the elemental to explode, dealing that element's damage to all nearby enemies|
|Enchanting|Enhance equipped weapons and armor with effects|Left: Attacks with equipped weapons or fists will damage an enemy's stamina. Right: Stamina recharges twice as fast|Left: Attacks with equipped weapons or fists will drain health. Right: Fortify health|Left: Attacks with equipped weapons or fists will deal additional frost damage. Right: Leave an icy wind behind you when you sprint, slowing enemies|Left: Attacks with equipped weapons or fists will deal additional shock damage. Right: Cloak yourself in an electric field, moving faster|Left: Attacks with equipped weapons or fists will deal additional fire damage. Right: Create a ward of fire, damaging the caster of any spell that hits you whilst you have this ward active|
|Illusion|Pranks and Avoiding Fights|Make a sound where the spell hits to distract enemies|Summon an illusory person that runs fron enemies and dies to one attack|Cast on a sleeping enemy to paralyze them and deal health and stamina damage over time|Summon an illusory creature that runs at enemies and fears them|Halve target's HP and cause a frenzied clone to appear near them|
|Restoration|Siphons health and magicka from enemies|Concentration: Deals damage to a target and heals the caster|Drains the target's magicka to restore the player's|Target takes damage over time, if it dies whilst under this effect, heal the player|Drain an enemy's magicka, dealing damage based on the amount of magicka drained|Creates a circle centered on the caster. Enemies within the circle take damage, allies are healed and have their magicka restored over time|

# Combat Magic Overhaul 3

A large combat magic addition that includes the possibility of using item resources to cast stronger spells.

|School|Theme|Novice|Apprentice|Adept|Expert|Master|Notes|
|--|--|--|--|--|--|--|--|
|Alteration|Abandoned Plane of Oblivion||||||Discover a small plane of oblivion just for you, complete with a quest detailing the history behind it.|
|Conjuration|Soul Magic||||||Sacrifice soul gems in your inventory to deal damage. Drains Azura's Star.|
|Destruction|Blood Magic||||||Sacrifice health instead of magicka to cast spells|
|Enchanting||||||||
|Illusion|Bow of Shadows||||||Conjured Bow - chameleon effect on user. Drains health to deal damage, doesn't need arrows.|
|Restoration||||||||


# Own Plane of Oblivion
 
 
