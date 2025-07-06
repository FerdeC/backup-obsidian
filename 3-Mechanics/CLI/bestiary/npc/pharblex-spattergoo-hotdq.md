---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/hotdq
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/bullywug
aliases: ["Pharblex Spattergoo"]
NoteIcon: monster
BestiaryType: humanoid (bullywug)
SourceType: Bestiary
BookSource: Hoard of the Dragon Queen p. 91
---
# [Pharblex Spattergoo](2-Mechanics\CLI\bestiary\npc/pharblex-spattergoo-hotdq.md)
*Source: Hoard of the Dragon Queen p. 91*  

```statblock
"name": "Pharblex Spattergoo (HotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "bullywug"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "59"
"hit_dice": "7d8 + 28"
"stats":
- !!int "15"
- !!int "12"
- !!int "18"
- !!int "11"
- !!int "16"
- !!int "7"
"speed": "20 ft., swim 40 ft."
"saves":
  "Strength": !!int "4"
  "Constitution": !!int "6"
"skillsaves":
  "Stealth": !!int "3"
  "Religion": !!int "2"
  "Perception": !!int "5"
"senses": "passive Perception 15"
"languages": "Common, Bullywug"
"cr": "3"
"traits":
- "desc": "Pharblex is a 6th-level spellcaster that uses Wisdom as his spellcasting\
    \ ability (spell save DC 13, +5 to hit with spell attacks). Pharblex has the\
    \ following spells prepared from the druid spell list:\n\nCantrips (at will):\
    \ [druidcraft](/2-Mechanics/CLI/spells/druidcraft.md), [guidance](/2-Mechanics/CLI/spells/guidance.md),\
    \ [poison spray](/2-Mechanics/CLI/spells/poison-spray.md)\n\n1st level (4 slots):\
    \ [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md), [entangle](/2-Mechanics/CLI/spells/entangle.md),\
    \ [healing word](/2-Mechanics/CLI/spells/healing-word.md), [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md)\n\
    \n2nd level (3 slots): [barkskin](/2-Mechanics/CLI/spells/barkskin.md), [beast\
    \ sense](/2-Mechanics/CLI/spells/beast-sense.md), [spike growth](/2-Mechanics/CLI/spells/spike-growth.md)\n\
    \n3rd level (3 slots): [plant growth](/2-Mechanics/CLI/spells/plant-growth.md),\
    \ [water walk](/2-Mechanics/CLI/spells/water-walk.md)"
  "name": "Spellcasting"
- "desc": "Pharblex can breathe air and water."
  "name": "Amphibious"
- "desc": "Once per turn, when Pharblex hits with a melee attack, he can expend a\
    \ use of this trait to deal an extra 9 (2d8) poison damage."
  "name": "Poison Strike (3/Day)"
- "desc": "As part of his movement and without a running start, Pharblex can long\
    \ jump up to 20 feet and high jump up to 10 feet."
  "name": "Standing Leap"
- "desc": "Pharblex has advantage on Dexterity ([Stealth](/2-Mechanics/CLI/rules/skills.md#Stealth))\
    \ checks made to hide in swampy terrain."
  "name": "Swamp Camouflage"
"actions":
- "desc": "Pharblex attacks twice. Once with his bite and once with his spear."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit. reach 5 ft. or ranged 20/60\
    \ ft., one target. Hit: 5 (1d6 + 2) piercing damage."
  "name": "Spear"
"source":
- "HotDQ"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/HotDQ/Pharblex%20Spattergoo.webp"
```
^statblock

```encounter-table
name: Pharblex Spattergoo
creatures:
 - 1: Pharblex Spattergoo
```