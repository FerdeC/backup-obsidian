---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Mev Flintknapper"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Out of the Abyss p. 103
---
# [Mev Flintknapper](2-Mechanics\CLI\bestiary\npc/mev-flintknapper-oota.md)
*Source: Out of the Abyss p. 103*  

```statblock
"name": "Mev Flintknapper (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "[splint armor](/2-Mechanics/CLI/items/splint-armor.md)"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"stats":
- !!int "16"
- !!int "13"
- !!int "14"
- !!int "10"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "5"
  "Perception": !!int "2"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "any one language (usually Common), Gnomish, Terran, Undercommon"
"cr": "3"
"traits":
- "desc": "Mev\n\nAt will: [nondetection](/2-Mechanics/CLI/spells/nondetection.md)\
    \ (self only)\n\n1/day each: [blindness/deafness](/2-Mechanics/CLI/spells/blindness-deafness.md),\
    \ [blur](/2-Mechanics/CLI/spells/blur.md), [disguise self](/2-Mechanics/CLI/spells/disguise-self.md)"
  "name": "Innate Spellcasting"
- "desc": "Mev"
  "name": "Gnome Cunning"
- "desc": "Mev"
  "name": "Stone Camouflage"
"actions":
- "desc": "Mev makes two longsword attacks. If it has a shortsword drawn, it can also\
    \ make a shortsword attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands."
  "name": "Longsword"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +3 to hit, range 100/400 ft., one target. Hit:\
    \ 6 (1d10 + 1) piercing damage."
  "name": "Heavy Crossbow"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Mev%20Flintknapper.webp"
```
^statblock

```encounter-table
name: Mev Flintknapper
creatures:
 - 1: Mev Flintknapper
```