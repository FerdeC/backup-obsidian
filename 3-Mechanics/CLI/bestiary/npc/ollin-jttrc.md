---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/jttrc
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Ollin"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Journeys through the Radiant Citadel p. 109
---
# [Ollin](2-Mechanics\CLI\bestiary\npc/ollin-jttrc.md)
*Source: Journeys through the Radiant Citadel p. 109*  

```statblock
"name": "Ollin (JttRC)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Good"
"ac": !!int "13"
"ac_class": "[chain shirt](/2-Mechanics/CLI/items/chain-shirt.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "10"
- !!int "10"
- !!int "12"
- !!int "13"
- !!int "16"
- !!int "13"
"speed": "30 ft."
"skillsaves":
  "Medicine": !!int "7"
  "Religion": !!int "5"
  "Performance": !!int "3"
"damage_resistances": "fire"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Ignan, Tletlahtolli, Infernal"
"cr": "2"
"traits":
- "desc": "Ollin is a 5th-level spellcaster. Its spellcasting ability is Wisdom (spell\
    \ save DC 13, +5 to hit with spell attacks). Ollin has the following cleric\
    \ spells prepared:\n\nCantrips (at will): [light](/2-Mechanics/CLI/spells/light.md),\
    \ [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1st level (4 slots): [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md),\
    \ [guiding bolt](/2-Mechanics/CLI/spells/guiding-bolt.md), [sanctuary](/2-Mechanics/CLI/spells/sanctuary.md)\n\
    \n2nd level (3 slots): [lesser restoration](/2-Mechanics/CLI/spells/lesser-restoration.md),\
    \ [spiritual weapon](/2-Mechanics/CLI/spells/spiritual-weapon.md)\n\n3rd level\
    \ (2 slots): [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), [spirit\
    \ guardians](/2-Mechanics/CLI/spells/spirit-guardians.md)"
  "name": "Spellcasting"
- "desc": "Ollin\n\nAt will: [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1/day each: [darkness](/2-Mechanics/CLI/spells/darkness.md), [hellish rebuke](/2-Mechanics/CLI/spells/hellish-rebuke.md)"
  "name": "Innate Spellcasting"
- "desc": "As a bonus action, Ollin can expend a spell slot to cause its melee weapon\
    \ attacks to magically deal an extra 10 (3d6) radiant damage to a target on\
    \ a hit. This benefit lasts until the end of the turn. If Ollin expends a spell\
    \ slot of 2nd level or higher, the extra damage increases by 1d6 for each level\
    \ above 1st."
  "name": "Divine Eminence"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 3 (1d6)\
    \ bludgeoning damage."
  "name": "Mace"
"source":
- "JttRC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/JttRC/Ollin.webp"
```
^statblock

```encounter-table
name: Ollin
creatures:
 - 1: Ollin
```