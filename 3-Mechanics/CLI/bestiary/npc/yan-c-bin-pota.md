---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/18
- monster/size/huge
- monster/type/elemental
aliases: ["Yan-C-Bin"]
NoteIcon: monster
BestiaryType: elemental
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 221
---
# [Yan-C-Bin](2-Mechanics\CLI\bestiary\npc/yan-c-bin-pota.md)
*Source: Princes of the Apocalypse p. 221*  

Yan-C-Bin (pronounced yan-see-bin) is the Prince of Evil Air. A being of great wisdom and malice, Yan-C-Bin's plots began at the forging of the worlds. Subtler than the other elemental princes, Yan-C-Bin operates unseen, studying his enemies from afar, ambushing them swiftly, and vanishing before his foes can retaliate.

His natural form is an invisible vortex of howling, swirling air 30 feet high and 15 feet wide, but Yan-C-Bin sometimes takes the shape of a gaunt, venerable, dark-skinned human with wispy white hair and glowing white eyes. When he wishes to remain unseen, Yan-C-Bin manifests only as a gust of cold wind flowing silently past.

From his floating palace in the endless, cloudy skies of the Plane of Air, Yan-C-Bin watches worlds as they change over millennia. Evil aerial creatures worship the elemental prince as a god, and claim to see Yan-C-Bin's eyes in swirling storms. Yan-C-Bin doesn't care for their offerings, their sacrifices, or their worship. His only concern is the annihilation of the material realms as they are ripped apart by the superior elemental might of air and wind.

## Yan-C-Bin's Lair

Yan-C-Bin dwells in a palace of air on the Elemental Plane of Air. In his palace and in air nodes on the Material Plane (including the Howling Caves, described in chapter 5), Yan-C-Bin is master. He can use the following actions in his lair.

```statblock
"name": "Yan-C-Bin (PotA)"
"size": "Huge"
"type": "elemental"
"alignment": "Neutral Evil"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "283"
"hit_dice": "21d12 + 147"
"stats":
- !!int "18"
- !!int "24"
- !!int "24"
- !!int "16"
- !!int "21"
- !!int "23"
"speed": "50 ft., fly 150 ft."
"saves":
  "Charisma": !!int "12"
  "Dexterity": !!int "13"
  "Wisdom": !!int "11"
"damage_resistances": "cold; fire; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "lightning, poison, thunder"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone), [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)"
"senses": "blindsight 120 ft., passive Perception 15"
"languages": "Auran"
"cr": "18"
"traits":
- "desc": "Yan-C-Bin's innate spellcasting ability is Charisma (spell save DC 20,\
    \ +12 to hit with spell attacks). He can innately cast the following spells,\
    \ requiring no material components:\n\nAt will: [gust of wind](/2-Mechanics/CLI/spells/gust-of-wind.md),\
    \ [invisibility](/2-Mechanics/CLI/spells/invisibility.md), [lightning bolt](/2-Mechanics/CLI/spells/lightning-bolt.md)\n\
    \n2/day each: [chain lightning](/2-Mechanics/CLI/spells/chain-lightning.md),\
    \ [cloudkill](/2-Mechanics/CLI/spells/cloudkill.md), [haste](/2-Mechanics/CLI/spells/haste.md)"
  "name": "Innate Spellcasting"
- "desc": "Yan-C-Bin can enter a hostile creature's space and stop there. He can move\
    \ through a space as narrow as 1 inch wide without squeezing if air could pass\
    \ through that space."
  "name": "Air Form"
- "desc": "Yan-C-Bin's slam attacks are treated as magical for the purpose of bypassing\
    \ resistance and immunity to nonmagical attacks."
  "name": "Empowered Attacks"
- "desc": "If Yan-C-Bin fails a saving throw, he can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Yan-C-Bin has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Yan-C-Bin makes two slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 20\
    \ (3d8 + 7) force damage plus 10 (3d6) lightning damage."
  "name": "Slam"
- "desc": "Yan-C-Bin unleashes a terrible thundercrack in a 100-foot-radius sphere\
    \ centered on himself. All other creatures in the area must succeed on a DC 24\
    \ Constitution saving throw or take 31 (9d6) thunder damage and be [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened)\
    \ for 1 minute. On a successful save, a creature takes half as much damage and\
    \ is [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened) until the start\
    \ of Yan-C-Bin's next turn."
  "name": "Thundercrack (Recharges after a Short or Long Rest)"
- "desc": "Yan-C-Bin polymorphs into a Medium humanoid. While in polymorphed form,\
    \ a swirling breeze surrounds him, his eyes are pale and cloudy, and he loses\
    \ the Air Form trait. He can remain in polymorphed form for up to 1 hour. Reverting\
    \ to his true form requires an action."
  "name": "Change Shape"
- "desc": "Yan-C-Bin summons up to three [air elementals](/2-Mechanics/CLI/bestiary/elemental/air-elemental.md)\
    \ and loses 30 hit points for each elemental he summons. Summoned elementals have\
    \ maximum hit points, appear within 100 feet of Yan-C-Bin, and disappear if Yan-C-Bin\
    \ is reduced to 0 hit points."
  "name": "Summon Elementals (1/Day)"
"legendary_actions":
- "desc": "Yan-C-Bin unleashes a peal of thunder that can be heard out to a range\
    \ of 300 feet. Each creature within 30 feet of Yan-C-Bin takes 5 (1d10) thunder\
    \ damage."
  "name": "Peal of Thunder"
- "desc": "Yan-C-Bin magically teleports up to 120 feet to an unoccupied space he\
    \ can see. Anything Yan-C-Bin is wearing or carrying is teleported with him."
  "name": "Teleport (Costs 2 Actions)"
- "desc": "Yan-C-Bin steals the air of one breathing creature he can see within 60\
    \ feet of him. The target must make a DC 21 Constitution saving throw. On a failed\
    \ save, the target drops to 0 hit points and is dying. On a successful save, the\
    \ target can't breathe or speak until the start of its next turn."
  "name": "Suffocate (Costs 3 Actions)"
"lair_actions":
- "desc": "Yan-C-Bin dwells in a palace of air on the Elemental Plane of Air. In his\
    \ palace and in air nodes on the Material Plane (including the Howling Caves,\
    \ described in chapter 5), Yan-C-Bin is master. He can use the following actions\
    \ in his lair. On initiative count 20 (losing initiative ties), Yan-C-Bin takes\
    \ a lair action to cause one of the following effects; he can't use the same effect\
    \ two rounds in a row:"
  "name": ""
- "desc": "- Yan-C-Bin drops the temperature of the air, covering all surfaces with\
    \ ice. This effect is identical to the [sleet storm](/2-Mechanics/CLI/spells/sleet-storm.md)\
    \ spell.  \n- Yan-C-Bin controls the surrounding air as an extension of himself.\
    \ Each creature Yan-C-Bin designates must succeed at a DC 24 Constitution saving\
    \ throw or be hoisted or flung 3d6 × 10 feet through the air. A creature smashed\
    \ into a solid object or released in mid-air takes 1d6 bludgeoning damage for\
    \ every 10 feet moved or fallen.  \n- Yan-C-Bin creates a torrent of debris within\
    \ 120 feet of him that lasts until initiative count 20 on the next round. The\
    \ debris lightly obscures every creature and object in the area for the duration.\
    \ All creatures in the area must succeed at a DC 24 Wisdom saving throw or be\
    \ [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded) until initiative count\
    \ 20 on the next round.  "
  "name": ""
"regional_effects":
- "desc": "When Yan-C-Bin inhabits an elemental node, the air is at his command. Temperatures\
    \ fluctuate from blistering hot to freezing cold; thunder rolls and lightning\
    \ cracks; powerful gales bear heavy creatures and objects aloft and hurl them\
    \ with incredible force; cyclones touch down randomly, obliterating whatever they\
    \ touch."
  "name": ""
- "desc": "- Gale force winds tear across the landscape in a 5-mile radius, whisking\
    \ away small or light objects, dismantling roofs and fences, tearing branches\
    \ from trees, and making flight impossible. Small and Medium creatures move at\
    \ half speed through the wind; Tiny creatures exposed to the wind are carried\
    \ away with it at a rate of 40 feet per round unless they succeed at a DC 15 Strength\
    \ ([Athletics](/2-Mechanics/CLI/rules/skills.md#Athletics)) check.  \n- Thunderstorms\
    \ erupt in a 5-mile radius centered on Yan-C-Bin's lair, creating deafening cracks\
    \ of thunder and constant lightning. Every ten minutes the storm rages, creatures\
    \ standing beneath the open sky have a five percent chance of being struck by\
    \ lightning. A creature struck by lightning must make a DC 21 Constitution saving\
    \ throw, taking 21 (6d6) lightning damage on a failed save, or half as much\
    \ damage on a successful one.  \n- Cyclones touch down within a 5-mile radius\
    \ of Yan-C-Bin's lair. Every hour, there is a five percent chance that characters\
    \ in this area are caught in the path of a cyclone moving 250 feet per round.\
    \ Each character must succeed on a DC 21 Constitution saving throw or take 33\
    \ (6d10) bludgeoning damage. Wooden or flimsy structures in the path of the\
    \ cyclone are destroyed.  \n- Natural caverns and windblown canyons within 1 mile\
    \ of the lair form intermittent portals to the Elemental Plane of Air, allowing\
    \ elemental creatures into the mortal world to dwell near those locations.  "
  "name": ""
- "desc": "If Yan-C-Bin is destroyed or banished back to his home plane, the regional\
    \ effects fade over the next 1d10 days."
  "name": ""
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Yan-C-Bin.webp"
```
^statblock

```encounter-table
name: Yan-C-Bin
creatures:
 - 1: Yan-C-Bin
```