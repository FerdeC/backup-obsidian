---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/9
- monster/size/huge
- monster/type/giant
aliases: ["Vaal"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Storm King's Thunder p. 207
---
# [Vaal](2-Mechanics\CLI\bestiary\npc/vaal-skt.md)
*Source: Storm King's Thunder p. 207*  

```statblock
"name": "Vaal (SKT)"
"size": "Huge"
"type": "giant"
"alignment": "Neutral Good or Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "200"
"hit_dice": "16d12 + 96"
"stats":
- !!int "27"
- !!int "10"
- !!int "22"
- !!int "12"
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
"languages": "Common, Giant"
"cr": "9"
"traits":
- "desc": "Vaal's innate spellcasting ability is Charisma. It can innately cast the\
    \ following spells, requiring no material components:\n\nAt will: [detect\
    \ magic](/2-Mechanics/CLI/spells/detect-magic.md), [fog cloud](/2-Mechanics/CLI/spells/fog-cloud.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md)\n\n1/day each: [control weather](/2-Mechanics/CLI/spells/control-weather.md),\
    \ [gaseous form](/2-Mechanics/CLI/spells/gaseous-form.md)\n\n3/day each: [feather\
    \ fall](/2-Mechanics/CLI/spells/feather-fall.md), [fly](/2-Mechanics/CLI/spells/fly.md),\
    \ [misty step](/2-Mechanics/CLI/spells/misty-step.md), [telekinesis](/2-Mechanics/CLI/spells/telekinesis.md)"
  "name": "Innate Spellcasting"
- "desc": "Vaal has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
"actions":
- "desc": "Vaal makes two morningstar attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 10 ft., one target. Hit: 21\
    \ (3d8 + 8) piercing damage."
  "name": "Morningstar"
- "desc": "Ranged Weapon Attack: +12 to hit, range 60/240 ft., one target. Hit:\
    \ 30 (4d10 + 8) bludgeoning damage."
  "name": "Rock"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Vaal.webp"
```
^statblock

```encounter-table
name: Vaal
creatures:
 - 1: Vaal
```