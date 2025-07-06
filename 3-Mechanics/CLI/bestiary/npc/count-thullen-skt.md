---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/10
- monster/size/huge
- monster/type/giant
aliases: ["Count Thullen"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Storm King's Thunder p. 198
---
# [Count Thullen](2-Mechanics\CLI\bestiary\npc/count-thullen-skt.md)
*Source: Storm King's Thunder p. 198*  

```statblock
"name": "Count Thullen (SKT)"
"size": "Huge"
"type": "giant"
"alignment": "Neutral Good"
"ac": !!int "14"
"ac_class": "natural armor; 16 with [barkskin](/2-Mechanics/CLI/spells/barkskin.md)"
"hp": !!int "200"
"hit_dice": "16d12 + 96"
"stats":
- !!int "27"
- !!int "10"
- !!int "22"
- !!int "14"
- !!int "16"
- !!int "16"
"speed": "40 ft."
"saves":
  "Charisma": !!int "7"
  "Wisdom": !!int "7"
  "Constitution": !!int "10"
"skillsaves":
  "Insight": !!int "7"
  "Perception": !!int "7"
"senses": "passive Perception 17"
"languages": "Common, Draconic, Druidic, Giant"
"cr": "10"
"traits":
- "desc": "Thullen's innate spellcasting ability is Charisma. It can innately cast\
    \ the following spells, requiring no material components:\n\nAt will: [detect\
    \ magic](/2-Mechanics/CLI/spells/detect-magic.md), [fog cloud](/2-Mechanics/CLI/spells/fog-cloud.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md)\n\n1/day each: [control weather](/2-Mechanics/CLI/spells/control-weather.md),\
    \ [gaseous form](/2-Mechanics/CLI/spells/gaseous-form.md)\n\n3/day each: [feather\
    \ fall](/2-Mechanics/CLI/spells/feather-fall.md), [fly](/2-Mechanics/CLI/spells/fly.md),\
    \ [misty step](/2-Mechanics/CLI/spells/misty-step.md), [telekinesis](/2-Mechanics/CLI/spells/telekinesis.md)"
  "name": "Innate Spellcasting"
- "desc": "Thullen is a 9th-level spellcaster. His spellcasting ability is Wisdom\
    \ (spell save DC 15, +7 to hit with spell attacks). He has the following druid\
    \ spells prepared:\n\nCantrips (at will): [druidcraft](/2-Mechanics/CLI/spells/druidcraft.md),\
    \ [mending](/2-Mechanics/CLI/spells/mending.md), [produce flame](/2-Mechanics/CLI/spells/produce-flame.md)\n\
    \n1st level (4 slots): [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md),\
    \ [entangle](/2-Mechanics/CLI/spells/entangle.md), [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md)\n\
    \n2nd level (3 slots): [animal messenger](/2-Mechanics/CLI/spells/animal-messenger.md),\
    \ [barkskin](/2-Mechanics/CLI/spells/barkskin.md), [gust of wind](/2-Mechanics/CLI/spells/gust-of-wind.md)\n\
    \n3rd level (3 slots): [call lightning](/2-Mechanics/CLI/spells/call-lightning.md),\
    \ [conjure animals](/2-Mechanics/CLI/spells/conjure-animals.md), [speak with plants](/2-Mechanics/CLI/spells/speak-with-plants.md)\n\
    \n4th level (3 slots): [freedom of movement](/2-Mechanics/CLI/spells/freedom-of-movement.md),\
    \ [grasping vine](/2-Mechanics/CLI/spells/grasping-vine.md)\n\n5th level (1\
    \ slots): [conjure elemental](/2-Mechanics/CLI/spells/conjure-elemental.md)"
  "name": "Spellcasting"
- "desc": "Thullen has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
"actions":
- "desc": "Thullen makes two morningstar attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 10 ft., one target. Hit: 21\
    \ (3d8 + 8) piercing damage."
  "name": "Morningstar"
- "desc": "Ranged Weapon Attack: +12 to hit, range 60/240 ft., one target. Hit:\
    \ 30 (4d10 + 8) bludgeoning damage."
  "name": "Rock"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Count%20Thullen.webp"
```
^statblock

```encounter-table
name: Count Thullen
creatures:
 - 1: Count Thullen
```