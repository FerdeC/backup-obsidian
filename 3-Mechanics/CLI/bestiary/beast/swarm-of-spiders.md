---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/1-2
- monster/environment/desert
- monster/environment/forest
- monster/environment/grassland
- monster/environment/hill
- monster/environment/swamp
- monster/environment/underdark
- monster/environment/urban
- monster/size/medium
- monster/type/beast
aliases: ["Swarm of Spiders"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 338, Curse of Strahd, Storm King's Thunder, Waterdeep: Dungeon of the Mad Mage, Ghosts of Saltmarsh, Mythic Odysseys of Theros. Available in the SRD.
---
# [Swarm of Spiders](2-Mechanics\CLI\bestiary\beast/swarm-of-spiders.md)
*Source: Monster Manual p. 338, Curse of Strahd, Storm King's Thunder, Waterdeep: Dungeon of the Mad Mage, Ghosts of Saltmarsh, Mythic Odysseys of Theros. Available in the SRD.*  

> [!note] The Nature of Swarms
> 
> The swarms presented here aren't ordinary or benign assemblies of little creatures. They form as a result of some sinister or unwholesome influence. A vampire can summon swarms of bats and rats from the darkest corners of the night, while the very presence of a mummy lord can cause scarab beetles to boil up from the sand-filled depths of its tomb. A hag might have the power to turn swarms of ravens against her enemies, while a [yuan-ti abomination](/2-Mechanics/CLI/bestiary/monstrosity/yuan-ti-abomination.md) might have [swarms of poisonous snakes](/2-Mechanics/CLI/bestiary/beast/swarm-of-poisonous-snakes.md) slithering in its wake. Even druids can't charm these swarms, and their aggressiveness is borderline unnatural.
^the-nature-of-swarms

```statblock
"name": "Swarm of Spiders"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "22"
"hit_dice": "5d8"
"stats":
- !!int "3"
- !!int "13"
- !!int "10"
- !!int "1"
- !!int "7"
- !!int "1"
"speed": "20 ft., climb 20 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone), [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
  \ [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)"
"senses": "blindsight 10 ft., passive Perception 8"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "The swarm can occupy another creature's space and vice versa, and the swarm\
    \ can move through any opening large enough for a Tiny insect. The swarm can't\
    \ regain hit points or gain temporary hit points."
  "name": "Swarm"
- "desc": "The swarm can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
- "desc": "While in contact with a web, the swarm knows the exact location of any\
    \ other creature in contact with the same web."
  "name": "Web Sense"
- "desc": "The swarm ignores movement restrictions caused by webbing."
  "name": "Web Walker"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 0 ft., one target in the swarm's\
    \ space. Hit: 10 (4d4) piercing damage, or 5 (2d4) piercing damage if the\
    \ swarm has half of its hit points or fewer."
  "name": "Bites"
"source":
- "MM"
- "CoS"
- "SKT"
- "WDMM"
- "GoS"
- "DC"
- "DIP"
- "MOT"
- "BMT"
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Swarm%20of%20Spiders.webp"
```
^statblock

```encounter-table
name: Swarm of Spiders
creatures:
 - 1: Swarm of Spiders
```

## Environment

underdark, grassland, forest, swamp, hill, urban, desert