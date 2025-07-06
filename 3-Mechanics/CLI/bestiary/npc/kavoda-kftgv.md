---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/1-2
- monster/size/small
- monster/type/humanoid/gnome
aliases: ["Kavoda"]
NoteIcon: monster
BestiaryType: humanoid (gnome)
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 78
---
# [Kavoda](2-Mechanics\CLI\bestiary\npc/kavoda-kftgv.md)
*Source: Keys from the Golden Vault p. 78*  

```statblock
"name": "Kavoda (KftGV)"
"size": "Small"
"type": "humanoid"
"subtype": "gnome"
"alignment": "Chaotic Good"
"ac": !!int "12"
"ac_class": "[robes](/2-Mechanics/CLI/items/robes.md)"
"hp": !!int "16"
"hit_dice": "3d6 + 6"
"stats":
- !!int "15"
- !!int "14"
- !!int "14"
- !!int "12"
- !!int "10"
- !!int "9"
"speed": "20 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Investigation": !!int "3"
  "Perception": !!int "2"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "Common, Gnomish, Terran, Undercommon"
"cr": "1/2"
"traits":
- "desc": "Kavoda's innate spellcasting ability is Intelligence (spell save DC 11).\
    \ It can innately cast the following spells, requiring no material components:\n\
    \nAt will: [nondetection](/2-Mechanics/CLI/spells/nondetection.md) (self only)\n\
    \n1/day each: [blindness/deafness](/2-Mechanics/CLI/spells/blindness-deafness.md),\
    \ [blur](/2-Mechanics/CLI/spells/blur.md), [disguise self](/2-Mechanics/CLI/spells/disguise-self.md)"
  "name": "Innate Spellcasting"
- "desc": "Kavoda carries a [spell scroll](/2-Mechanics/CLI/items/spell-scroll-2nd-level.md)\
    \ of [magic weapon](/2-Mechanics/CLI/spells/magic-weapon.md) and a [potion of\
    \ giant strength (hill)](/2-Mechanics/CLI/items/potion-of-hill-giant-strength.md)."
  "name": "Special Equipment"
- "desc": "Kavoda has advantage on Dexterity ([Stealth](/2-Mechanics/CLI/rules/skills.md#Stealth))\
    \ checks made to hide in rocky terrain."
  "name": "Stone Camouflage"
- "desc": "Kavoda has advantage on Intelligence, Wisdom, and Charisma saving throws\
    \ against magic."
  "name": "Gnome Cunning"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) piercing damage."
  "name": "War Pick"
- "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one creature. Hit:\
    \ 4 (1d4 + 2) piercing damage, and the target must succeed on a DC 12 Constitution\
    \ saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ for 1 minute. The target can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success"
  "name": "Poisoned Dart"
"source":
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/KftGV/Kavoda.webp"
```
^statblock

```encounter-table
name: Kavoda
creatures:
 - 1: Kavoda
```