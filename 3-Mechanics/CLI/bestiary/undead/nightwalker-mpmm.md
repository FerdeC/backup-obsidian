---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/20
- monster/environment/arctic
- monster/environment/desert
- monster/environment/swamp
- monster/environment/underdark
- monster/size/huge
- monster/type/undead
aliases: ["Nightwalker"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 194, Mordenkainen's Tome of Foes p. 216
---
# [Nightwalker](2-Mechanics\CLI\bestiary\undead/nightwalker-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 194, Mordenkainen's Tome of Foes p. 216*  

The Negative Plane is a place of death, anathema to all living things. Yet there are some who would tap into its fell power and use its energy for sinister ends. Most individuals prove unequal to the task. Those not destroyed outright are sometimes drawn inside the plane and replaced by nightwalkers—terrifying Undead creatures that devour all life they encounter.

One can reach the Negative Plane from the Shadowfell in places where the barrier between the planes is thin. Stepping onto the Negative Plane is almost always fatal since the plane sucks the life and soul from creatures, annihilating most at once. The few who survive by sheer luck or by harnessing some rare form of protective magic soon discover that they can't leave as easily as they arrived. Worse, for each creature that enters the plane, a nightwalker is released to take its place. In order for a trapped creature to escape, the released nightwalker must be lured back to the Negative Plane by offerings of life for it to devour. If the nightwalker is destroyed, the trapped creature has no hope of escape.

Generally, a nightwalker on the Material Plane is attracted to elements of the world associated with the creature responsible for its creation, which can provide clues as to who the trapped creature is. This attraction doesn't indicate a willingness to engage with the world, though; nightwalkers exist to make life extinct, and they prioritize anything associated with the trapped creature for destruction.

```statblock
"name": "Nightwalker (MPMM)"
"size": "Huge"
"type": "undead"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "14"
"hp": !!int "337"
"hit_dice": "25d12 + 175"
"stats":
- !!int "22"
- !!int "19"
- !!int "24"
- !!int "6"
- !!int "9"
- !!int "8"
"speed": "40 ft., fly 40 ft."
"saves":
  "Constitution": !!int "13"
"damage_resistances": "acid; cold; fire; lightning; thunder; bludgeoning, piercing,\
  \ slashing from nonmagical attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned), [prone](/2-Mechanics/CLI/rules/conditions.md#prone),\
  \ [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained)"
"senses": "darkvision 120 ft., passive Perception 9"
"languages": ""
"cr": "20"
"traits":
- "desc": "Any creature that starts its turn within 30 feet of the nightwalker must\
    \ succeed on a DC 21 Constitution saving throw or take 21 (6d6) necrotic damage.\
    \ Undead are immune to this aura."
  "name": "Annihilating Aura"
- "desc": "A creature dies if reduced to 0 hit points by the nightwalker and can't\
    \ be revived except by a [wish](/2-Mechanics/CLI/spells/wish.md) spell."
  "name": "Life Eater"
- "desc": "The nightwalker doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The nightwalker makes two Enervating Focus attacks, one of which can be\
    \ replaced by Finger of Doom, if available."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 15 ft., one target. Hit: 28\
    \ (5d8 + 6) necrotic damage. The target must succeed on a DC 21 Constitution\
    \ saving throw or its hit point maximum is reduced by an amount equal to the necrotic\
    \ damage taken. This reduction lasts until the target finishes a long rest. The\
    \ target dies if its hit point maximum is reduced to 0."
  "name": "Enervating Focus"
- "desc": "The nightwalker points at one creature it can see within 300 feet of it.\
    \ The target must succeed on a DC 21 Wisdom saving throw or take 39 (6d12) necrotic\
    \ damage and become [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ until the end of the nightwalker's next turn. While [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)\
    \ in this way, the creature is also [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed).\
    \ If a target's saving throw is successful, the target is immune to the nightwalker's\
    \ Finger of Doom for the next 24 hours."
  "name": "Finger of Doom (Recharge 6)"
"source":
- "MPMM"
- "MTF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPMM/Nightwalker.webp"
```
^statblock

```encounter-table
name: Nightwalker
creatures:
 - 1: Nightwalker
```

## Environment

arctic, desert, swamp, underdark