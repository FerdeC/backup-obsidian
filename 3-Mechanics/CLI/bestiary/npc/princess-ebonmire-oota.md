---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/4
- monster/size/large
- monster/type/ooze
aliases: ["Princess Ebonmire"]
NoteIcon: monster
BestiaryType: ooze
SourceType: Bestiary
BookSource: Out of the Abyss p. 111
---
# [Princess Ebonmire](2-Mechanics\CLI\bestiary\npc/princess-ebonmire-oota.md)
*Source: Out of the Abyss p. 111*  

```statblock
"name": "Princess Ebonmire (OotA)"
"size": "Large"
"type": "ooze"
"alignment": "Unaligned"
"ac": !!int "7"
"hp": !!int "85"
"hit_dice": "10d10 + 30"
"stats":
- !!int "16"
- !!int "5"
- !!int "16"
- !!int "6"
- !!int "6"
- !!int "1"
"speed": "20 ft., climb 20 ft."
"damage_immunities": "acid, cold, lightning, slashing"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [prone](/2-Mechanics/CLI/rules/conditions.md#prone)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 8"
"languages": ""
"cr": "4"
"traits":
- "desc": "Princess Ebonmire can move through a space as narrow as 1 inch wide without\
    \ squeezing."
  "name": "Amorphous"
- "desc": "A creature that touches Princess Ebonmire or hits it with a melee attack\
    \ while within 5 feet of it takes 4 (1d8) acid damage. Any nonmagical weapon\
    \ made of metal or wood that hits Princess Ebonmire corrodes. After dealing damage,\
    \ the weapon takes a permanent and cumulative −1 penalty to damage rolls. If its\
    \ penalty drops to −5, the weapon is destroyed. Nonmagical ammunition made of\
    \ metal or wood that hits Princess Ebonmire is destroyed after dealing damage.\
    \ Princess Ebonmire can eat through 2-inch-thick, nonmagical wood or metal in\
    \ 1 round."
  "name": "Corrosive Form"
- "desc": "Princess Ebonmire can climb difficult surfaces, including upside down on\
    \ ceilings, without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or 30 ft., one\
    \ target. Hit: 6 (1d6 + 3) bludgeoning damage plus 18 (4d8) acid damage.\
    \ In addition, nonmagical armor worn by the target is partly dissolved and takes\
    \ a permanent and cumulative −1 penalty to the AC it offers. The armor is destroyed\
    \ if the penalty reduces its AC to 10."
  "name": "Pseudopod"
"reactions":
- "desc": "When a pudding that is Medium or larger is subjected to lightning or slashing\
    \ damage, it splits into two new puddings if it has at least 10 hit points. Each\
    \ new pudding has hit points equal to half the original pudding's, rounded down.\
    \ New puddings are one size smaller than the original pudding."
  "name": "Split"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Princess%20Ebonmire.webp"
```
^statblock

```encounter-table
name: Princess Ebonmire
creatures:
 - 1: Princess Ebonmire
```