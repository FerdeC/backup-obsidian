---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/1-4
- monster/environment/swamp
- monster/environment/underdark
- monster/environment/urban
- monster/size/small
- monster/type/monstrosity
aliases: ["Wretched Sorrowsworn"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 224, Mordenkainen's Tome of Foes p. 233
---
# [Wretched Sorrowsworn](2-Mechanics\CLI\bestiary\monstrosity/wretched-sorrowsworn-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 224, Mordenkainen's Tome of Foes p. 233*  

Horrid little monsters, wretched sorrowsworn—or the Wretched—gather in packs to scour the Shadowfell for prey. These desperate entities subsist on life force; when they find a creature, they surge forward to sink their fangs into their victims and drink deep.

## Sorrowsworn

The Shadowfell's pervasive melancholy sometimes gives rise to strange incarnations of the plane's bleak nature. Sorrowsworn embody the forms of suffering inherent to the shadowy landscape and visit horror on those who stumble into their midst. Each sorrowsworn personifies a different aspect of despair or distress.

```statblock
"name": "Wretched Sorrowsworn (MPMM)"
"size": "Small"
"type": "monstrosity"
"alignment": "Typically  Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "10"
"hit_dice": "4d6 - 4"
"stats":
- !!int "7"
- !!int "12"
- !!int "9"
- !!int "5"
- !!int "6"
- !!int "5"
"speed": "40 ft."
"damage_resistances": "bludgeoning, piercing, slashing while in dim light or darkness"
"senses": "darkvision 60 ft., passive Perception 8"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The sorrowsworn has advantage on an attack roll against a creature if at\
    \ least one of the sorrowsworn's allies is within 5 feet of the creature and the\
    \ ally isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated).\
    \ The sorrowsworn otherwise has disadvantage on attack rolls."
  "name": "Wretched Pack Tactics"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 6 (1d10\
    \ + 1) piercing damage, and the sorrowsworn attaches to the target. While attached,\
    \ the sorrowsworn can't attack, and at the start of each of the sorrowsworn's\
    \ turns, the target takes 6 (1d10 + 1) necrotic damage.\n\nThe attached sorrowsworn\
    \ moves with the target whenever the target moves, requiring none of the sorrowsworn's\
    \ movement. The sorrowsworn can detach itself by spending 5 feet of its movement\
    \ on its turn. A creature, including the target, can use its action to detach\
    \ the sorrowsworn."
  "name": "Bite"
"source":
- "MPMM"
- "MTF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPMM/Wretched%20Sorrowsworn.webp"
```
^statblock

```encounter-table
name: Wretched Sorrowsworn
creatures:
 - 1: Wretched Sorrowsworn
```

## Environment

swamp, underdark, urban