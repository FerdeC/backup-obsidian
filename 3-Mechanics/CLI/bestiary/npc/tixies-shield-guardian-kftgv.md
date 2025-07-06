---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/7
- monster/size/large
- monster/type/construct
aliases: ["Tixie's Shield Guardian"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 80
---
# [Tixie's Shield Guardian](2-Mechanics\CLI\bestiary\npc/tixies-shield-guardian-kftgv.md)
*Source: Keys from the Golden Vault p. 80*  

```statblock
"name": "Tixie's Shield Guardian (KftGV)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "142"
"hit_dice": "15d10 + 60"
"stats":
- !!int "18"
- !!int "8"
- !!int "18"
- !!int "7"
- !!int "10"
- !!int "3"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 10 ft., darkvision 60 ft., passive Perception 10"
"languages": "understands commands given in any language but can't speak"
"cr": "7"
"traits":
- "desc": "The shield guardian is magically bound to an amulet. As long as the guardian\
    \ and its amulet are on the same plane of existence, the amulet's wearer can telepathically\
    \ call the guardian to travel to it, and the guardian knows the distance and direction\
    \ to the amulet. If the guardian is within 60 feet of the amulet's wearer, half\
    \ of any damage the wearer takes (rounded up) is transferred to the guardian."
  "name": "Bound"
- "desc": "The shield guardian regains 10 hit points at the start of its turn if it\
    \ has at least 1 hit point."
  "name": "Regeneration"
"actions":
- "desc": "The guardian makes two fist attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) bludgeoning damage."
  "name": "Fist"
"reactions":
- "desc": "When a creature makes an attack against the wearer of the guardian's amulet,\
    \ the guardian grants a +2 bonus to the wearer's AC if the guardian is within\
    \ 5 feet of the wearer."
  "name": "Shield"
"source":
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/KftGV/Tixie%27s%20Shield%20Guardian.webp"
```
^statblock

```encounter-table
name: Tixie's Shield Guardian
creatures:
 - 1: Tixie's Shield Guardian
```