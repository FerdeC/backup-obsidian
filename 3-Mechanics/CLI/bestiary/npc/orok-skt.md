---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/1-8
- monster/size/small
- monster/type/humanoid/human
aliases: ["Orok"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 115
---
# [Orok](2-Mechanics\CLI\bestiary\npc/orok-skt.md)
*Source: Storm King's Thunder p. 115*  

```statblock
"name": "Orok (SKT)"
"size": "Small"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Neutral"
"ac": !!int "12"
"hp": !!int "5"
"hit_dice": "2d6 - 2"
"stats":
- !!int "7"
- !!int "15"
- !!int "9"
- !!int "8"
- !!int "7"
- !!int "8"
"speed": "30 ft."
"senses": "passive Perception 8"
"languages": "Bothii, Common"
"cr": "1/8"
"traits":
- "desc": "Orok has advantage on an attack roll against a creature if at least one\
    \ of Orok's allies is within 5 feet of the creature and the ally isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage."
  "name": "Dagger"
- "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit:\
    \ 4 (1d4 + 2) bludgeoning damage."
  "name": "Sling"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Orok.webp"
```
^statblock

```encounter-table
name: Orok
creatures:
 - 1: Orok
```