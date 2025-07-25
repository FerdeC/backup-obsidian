---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/12
- monster/environment/arctic
- monster/environment/desert
- monster/environment/urban
- monster/size/large
- monster/type/undead
aliases: ["Boneclaw"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 66, Mordenkainen's Tome of Foes p. 121
---
# [Boneclaw](2-Mechanics\CLI\bestiary\undead/boneclaw-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 66, Mordenkainen's Tome of Foes p. 121*  

A wizard who tries to become a lich but fails might become a boneclaw instead. These hideous, cackling monsters share a few of liches' attributes, but while liches are immortal masters of the arcane, boneclaws are thralls to evil, hatred, and pain.

The most important part of the transformation ritual occurs when the soul of the aspiring lich migrates to a prepared phylactery. If the wizard is too physically or magically weak to compel the soul into its new home, the soul instead seeks out a master—a person within a few miles who has a hate-filled heart. The soul bonds to that person and becomes enslaved to its new master's wishes. The boneclaw forms near its master, sometimes appearing before that individual to receive orders and other times simply seeking to fulfill its master's desires.

A boneclaw can serve only an evil creature. If its master finds redemption or sincerely turns away from the path of evil, the boneclaw is destroyed. Otherwise, a boneclaw can't be destroyed while its master lives. No matter what happens to the boneclaw's body, it re-forms within hours.

In service to its master, a boneclaw delights in causing horrific pain. It lurks like a spider in shadowy recesses, waiting for victims to approach within reach of its long, bony limbs. Once speared, a creature is pulled into the darkness to be sliced apart.

```statblock
"name": "Boneclaw (MPMM)"
"size": "Large"
"type": "undead"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "150"
"hit_dice": "20d10 + 40"
"stats":
- !!int "19"
- !!int "16"
- !!int "15"
- !!int "13"
- !!int "15"
- !!int "9"
"speed": "40 ft."
"saves":
  "Dexterity": !!int "7"
  "Wisdom": !!int "6"
  "Constitution": !!int "6"
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "6"
"damage_resistances": "cold, necrotic"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Common plus one language spoken by its master"
"cr": "12"
"traits":
- "desc": "While its master lives, a destroyed boneclaw gains a new body in 1d10\
    \ hours, with all its hit points. The new body appears within 1 mile of the boneclaw's\
    \ master."
  "name": "Rejuvenation"
- "desc": "The boneclaw doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The boneclaw makes two Piercing Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 15 ft., one target. Hit: 20\
    \ (3d10 + 4) piercing damage plus 11 (2d10) necrotic damage. If the target\
    \ is a creature, the boneclaw can pull the target up to 10 feet toward itself,\
    \ and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 14). The boneclaw has two claws. While a claw grapples a target,\
    \ the claw can attack only that target."
  "name": "Piercing Claw"
- "desc": "If the boneclaw is in dim light or darkness, each creature of the boneclaw's\
    \ choice within 15 feet of it must succeed on a DC 14 Constitution saving throw\
    \ or take 34 (5d12 + 2) necrotic damage.\n\nThe boneclaw then teleports up to\
    \ 60 feet to an unoccupied space it can see. It can bring one creature it's grappling,\
    \ teleporting that creature to an unoccupied space it can see within 5 feet of\
    \ its destination. The destination spaces of this teleportation must be in dim\
    \ light or darkness."
  "name": "Shadow Jump (Recharge 5-6)"
"bonus_actions":
- "desc": "While in dim light or darkness, the boneclaw takes the [Hide](/2-Mechanics/CLI/rules/actions.md#Hide)\
    \ action."
  "name": "Shadow Stealth"
"reactions":
- "desc": "In response to a creature entering a space within 15 feet of it, the boneclaw\
    \ makes one Piercing Claw attack against that creature."
  "name": "Deadly Reach"
"source":
- "MPMM"
- "MTF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPMM/Boneclaw.webp"
```
^statblock

```encounter-table
name: Boneclaw
creatures:
 - 1: Boneclaw
```

## Environment

arctic, desert, urban