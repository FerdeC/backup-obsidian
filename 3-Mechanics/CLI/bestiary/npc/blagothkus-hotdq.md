---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/hotdq
- monster/cr/9
- monster/size/huge
- monster/type/giant/cloud-giant
aliases: ["Blagothkus"]
NoteIcon: monster
BestiaryType: giant (cloud giant)
SourceType: Bestiary
BookSource: Hoard of the Dragon Queen p. 89
---
# [Blagothkus](2-Mechanics\CLI\bestiary\npc/blagothkus-hotdq.md)
*Source: Hoard of the Dragon Queen p. 89*  

```statblock
"name": "Blagothkus (HotDQ)"
"size": "Huge"
"type": "giant"
"subtype": "cloud giant"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "[splint armor](/2-Mechanics/CLI/items/splint-armor.md)"
"hp": !!int "138"
"hit_dice": "12d12 + 60"
"stats":
- !!int "26"
- !!int "13"
- !!int "20"
- !!int "16"
- !!int "15"
- !!int "15"
"speed": "40 ft."
"saves":
  "Charisma": !!int "6"
  "Wisdom": !!int "6"
  "Constitution": !!int "9"
"skillsaves":
  "Intimidation": !!int "6"
  "Insight": !!int "6"
  "Perception": !!int "6"
  "Arcana": !!int "7"
"senses": "passive Perception 16"
"languages": "Common, Draconic, Giant"
"cr": "9"
"traits":
- "desc": "Blagothkus can innately cast the following spells (spell save DC 15), requiring\
    \ no material components:\n\n3/day each: [fog cloud](/2-Mechanics/CLI/spells/fog-cloud.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md)"
  "name": "Innate Spellcasting"
- "desc": "Blagothkus is a 5th-level spellcaster that uses Intelligence as his spellcasting\
    \ ability (spell save DC 15, +7 to hit with spell attacks). Blagothkus has the\
    \ following spells prepared from the wizard spell list:\n\nCantrips (at will):\
    \ [light](/2-Mechanics/CLI/spells/light.md), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\n1st level\
    \ (4 slots): [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [identify](/2-Mechanics/CLI/spells/identify.md),\
    \ [magic missile](/2-Mechanics/CLI/spells/magic-missile.md), [shield](/2-Mechanics/CLI/spells/shield.md)\n\
    \n2nd level (3 slots): [gust of wind](/2-Mechanics/CLI/spells/gust-of-wind.md),\
    \ [misty step](/2-Mechanics/CLI/spells/misty-step.md), [shatter](/2-Mechanics/CLI/spells/shatter.md)\n\
    \n3rd level (2 slots): [fly](/2-Mechanics/CLI/spells/fly.md), [lightning bolt](/2-Mechanics/CLI/spells/lightning-bolt.md)"
  "name": "Spellcasting"
- "desc": "Blagothkus has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
"actions":
- "desc": "Blagothkus attacks twice with his morningstar."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 21\
    \ (3d8 + 8) piercing damage."
  "name": "Morningstar"
"source":
- "HotDQ"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/HotDQ/Blagothkus.webp"
```
^statblock

```encounter-table
name: Blagothkus
creatures:
 - 1: Blagothkus
```