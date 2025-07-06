---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/1
- monster/size/medium
- monster/type/monstrosity
aliases: ["Su-monster"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 232
---
# [Su-monster](2-Mechanics\CLI\bestiary\monstrosity/su-monster-toa.md)
*Source: Tomb of Annihilation p. 232*  

Su-monsters are cunning, wicked primates that inhabit forsaken wilderness areas and caves. Adults stand 5 feet tall and have long prehensile tails. Although they can grasp tools and weapons with their tails or clawed feet, su-monsters prefer to rend prey with their claws. Adult su-monsters can also project blasts of psionic energy that leave enemies [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned) and unable to flee or defend themselves.

A su-monster sleeps while hanging upside down by its tail. While awake, it can also unleash a devastating attack from that position, rending with all four of its claws.

Su-monsters communicate silently by using their prehensile tails to make gestures. They typically kill more than they can eat, burying the leftovers and marking their location with the victim's possessions.

```statblock
"name": "Su-monster (ToA)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "14"
- !!int "15"
- !!int "12"
- !!int "9"
- !!int "13"
- !!int "9"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Athletics": !!int "6"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "1"
"actions":
- "desc": "The su-monster makes two attacks: one with its bite and one with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (2d4\
    \ + 2) slashing damage, or 12 (4d4 + 2) slashing damage if the su-monster is\
    \ hanging by its tail and all four of its limbs are free."
  "name": "Claws"
- "desc": "The su-monster targets one creature it can see within 30 feet of it. The\
    \ target must succeed on a DC 11 Wisdom saving throw or take 17 (5d6) psychic\
    \ damage and be [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned) for 1\
    \ minute. The [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned) target can\
    \ repeat the saving throw at the end of each of its turns, ending the effect on\
    \ itself on a success."
  "name": "Psychic Crush (Recharge 5-6)"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Su-monster.webp"
```
^statblock

```encounter-table
name: Su-monster
creatures:
 - 1: Su-monster
```