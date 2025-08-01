---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/3
- monster/environment/coastal
- monster/environment/underwater
- monster/size/medium
- monster/type/fey
aliases: ["Dolphin Delighter"]
NoteIcon: monster
BestiaryType: fey
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 97
---
# [Dolphin Delighter](2-Mechanics\CLI\bestiary\fey/dolphin-delighter-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 97*  

In the Feywild, dolphin delighters brighten the moods of those who travel the seas of the Domains of Delight. Telepathically singing sea chanteys, these dolphins leap and teleport through the luminous waters of Faerie and the Material Plane, and they are faithful allies to any who battle the forces of gloom and brutality under the waves.

Dolphin delighters often accompany groups of sea elves, tritons, and tortles as guardians and friends.

## Dolphins

Dolphins are clever, social marine mammals that feed on small fish and squid. An adult specimen is between 5 and 6 feet long.

```statblock
"name": "Dolphin Delighter (MPMM)"
"size": "Medium"
"type": "fey"
"alignment": "Typically  Chaotic Good"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "14"
- !!int "13"
- !!int "13"
- !!int "11"
- !!int "12"
- !!int "16"
"speed": "0 ft., swim 60 ft."
"saves":
  "Charisma": !!int "5"
  "Wisdom": !!int "3"
"skillsaves":
  "Perception": !!int "3"
  "Performance": !!int "5"
"senses": "blindsight 60 ft., passive Perception 13"
"languages": "Aquan, telepathy 120 ft."
"cr": "3"
"traits":
- "desc": "The dolphin can hold its breath for 20 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "The dolphin makes two Dazzling Slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage plus 7 (2d6) psychic damage, and the target is [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded)\
    \ until the start of the dolphin's next turn."
  "name": "Dazzling Slam"
"bonus_actions":
- "desc": "The dolphin magically emanates light in a 10-foot radius for a moment.\
    \ The dolphin and each creature of its choice in that light gain 11 (2d10) temporary\
    \ hit points."
  "name": "Delightful Light (Recharge 5-6)"
- "desc": "The dolphin teleports up to 30 feet to an unoccupied space it can see.\
    \ Immediately before teleporting, the dolphin can choose one creature within 5\
    \ feet of it. That creature can teleport with the dolphin, appearing in an unoccupied\
    \ space within 5 feet of the dolphin's destination space."
  "name": "Fey Leap"
"source":
- "MPMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPMM/Dolphin%20Delighter.webp"
```
^statblock

```encounter-table
name: Dolphin Delighter
creatures:
 - 1: Dolphin Delighter
```

## Environment

coastal, underwater