---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/6
- monster/size/small
- monster/type/humanoid/lightfoot-halfling
aliases: ["Manafret Cherryport"]
NoteIcon: monster
BestiaryType: humanoid (Lightfoot halfling)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 149
---
# [Manafret Cherryport](2-Mechanics\CLI\bestiary\npc/manafret-cherryport-wdh.md)
*Source: Waterdeep: Dragon Heist p. 149*  

One of Manshoon's lieutenants

```statblock
"name": "Manafret Cherryport (WDH)"
"size": "Small"
"type": "humanoid"
"subtype": "Lightfoot halfling"
"alignment": "Lawful Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "31"
"hit_dice": "9d6"
"stats":
- !!int "9"
- !!int "14"
- !!int "11"
- !!int "17"
- !!int "12"
- !!int "11"
"speed": "25 ft."
"saves":
  "Wisdom": !!int "4"
  "Intelligence": !!int "6"
"skillsaves":
  "History": !!int "6"
  "Arcana": !!int "6"
"senses": "passive Perception 11"
"languages": "Common, Halfling"
"cr": "6"
"traits":
- "desc": "The mage is a 9th-level spellcaster. Its spellcasting ability is Intelligence.\
    \ The mage has the following wizard spells prepared:\n\nCantrips (at will):\
    \ [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md), [light](/2-Mechanics/CLI/spells/light.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\
    \n1st level (4 slots): [detect magic](/2-Mechanics/CLI/spells/detect-magic.md),\
    \ [mage armor](/2-Mechanics/CLI/spells/mage-armor.md), [magic missile](/2-Mechanics/CLI/spells/magic-missile.md),\
    \ [shield](/2-Mechanics/CLI/spells/shield.md)\n\n2nd level (3 slots): [misty\
    \ step](/2-Mechanics/CLI/spells/misty-step.md), [suggestion](/2-Mechanics/CLI/spells/suggestion.md)\n\
    \n3rd level (3 slots): [counterspell](/2-Mechanics/CLI/spells/counterspell.md),\
    \ [fireball](/2-Mechanics/CLI/spells/fireball.md), [fly](/2-Mechanics/CLI/spells/fly.md)\n\
    \n4th level (3 slots): [greater invisibility](/2-Mechanics/CLI/spells/greater-invisibility.md),\
    \ [ice storm](/2-Mechanics/CLI/spells/ice-storm.md)\n\n5th level (1 slots):\
    \ [cone of cold](/2-Mechanics/CLI/spells/cone-of-cold.md)"
  "name": "Spellcasting"
- "desc": "Manafret can move through a space of a Medium or larger creature."
  "name": "Halfling Nimbleness"
- "desc": "Manafret has advantage on saving throws against being [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Brave"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage. Or Ranged Weapon Attack: +5 to hit, range 20/60 ft.,\
    \ one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "WDH"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDH/Manafret%20Cherryport.webp"
```
^statblock

```encounter-table
name: Manafret Cherryport
creatures:
 - 1: Manafret Cherryport
```