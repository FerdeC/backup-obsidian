---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/ftd
- monster/cr/7
- monster/size/large
- monster/type/monstrosity
aliases: ["Liondrake"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Fizban's Treasury of Dragons p. 207
---
# [Liondrake](2-Mechanics\CLI\bestiary\monstrosity/liondrake-ftd.md)
*Source: Fizban's Treasury of Dragons p. 207*  

A liondrake is a solitary and territorial predator with the long neck and wings of a brass dragon and the head and body of a lion (including a luxurious mane on males). Sometimes known as dragonnes, liondrakes rely on their ferocity and their frightful roar to overcome prey and drive off rivals.

Liondrakes are voracious hunters that range across well-established territories. They don't typically seek out people as prey, but those folk who encroach into liondrake territory are fair game—which feeds the creature's reputation as hungering for Humanoid flesh.

```statblock
"name": "Liondrake (FTD)"
"size": "Large"
"type": "monstrosity"
"alignment": "typically  Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "119"
"hit_dice": "14d10 + 42"
"stats":
- !!int "19"
- !!int "15"
- !!int "17"
- !!int "6"
- !!int "12"
- !!int "12"
"speed": "40 ft., fly 60 ft."
"skillsaves":
  "Perception": !!int "7"
"senses": "darkvision 60 ft., passive Perception 17"
"languages": "Draconic"
"cr": "7"
"actions":
- "desc": "The liondrake makes one Bite attack and two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 15\
    \ (2d10 + 4) piercing damage. If the target is a Medium or smaller creature,\
    \ it must succeed on a DC 15 Strength saving throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) slashing damage."
  "name": "Claw"
- "desc": "The liondrake lets out a terrifying roar audible out to 300 feet. Any creature\
    \ within 30 feet of the liondrake that can hear its roar must succeed on a DC\
    \ 14 Wisdom saving throw or be [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ of the liondrake for 1 minute. A creature that fails the save by 5 or more is\
    \ also [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed) for the same\
    \ duration. A creature can repeat the saving throw at the end of its turns, ending\
    \ the effect on itself on a success. If a target's saving throw is successful\
    \ or the effect ends for it, the target is immune to this liondrake's Blood-Chilling\
    \ Roar for the next 24 hours."
  "name": "Blood-Chilling Roar (Recharge 4-6)"
"source":
- "FTD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/FTD/Liondrake.webp"
```
^statblock

```encounter-table
name: Liondrake
creatures:
 - 1: Liondrake
```