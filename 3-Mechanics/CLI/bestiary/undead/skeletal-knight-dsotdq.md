---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/7
- monster/size/medium
- monster/type/undead
aliases: ["Skeletal Knight"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 208
---
# [Skeletal Knight](2-Mechanics\CLI\bestiary\undead/skeletal-knight-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 208*  

Skeletal knights are powerful Undead that arise to serve even more wicked beings—often death knights. Those who become skeletal knights were typically virtuous in life but betrayed their oaths and died in disgrace. Unable to rest, they are now unswervingly loyal to the villains they serve. Should a skeletal knight's master be destroyed, the knight regains its will and is free to pursue its own ends.

Skeletal knights are relentless in battle and difficult to destroy. They cling to the sins that curse them, and they fight until their skulls are reduced to shards. Their blades deal lingering wounds that sap their victims' life force and leave blackened scars even after magical healing.

```statblock
"name": "Skeletal Knight (DSotDQ)"
"size": "Medium"
"type": "undead"
"alignment": "typically  Lawful Evil"
"ac": !!int "18"
"ac_class": "[plate](/2-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"stats":
- !!int "20"
- !!int "10"
- !!int "16"
- !!int "13"
- !!int "14"
- !!int "10"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "5"
  "Constitution": !!int "6"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "understands the languages it knew in life but can't speak"
"cr": "7"
"traits":
- "desc": "If damage reduces the skeletal knight to 0 hit points, it must make a Constitution\
    \ saving throw with a DC of 5 + the damage taken, unless the damage is bludgeoning\
    \ or from a critical hit. On a success, the skeletal knight drops to 1 hit point\
    \ instead."
  "name": "Undead Fortitude"
- "desc": "The skeletal knight doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The skeletal knight makes three Enervating Blade or Throwing Axe attacks\
    \ in any combination."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 15\
    \ (3d6 + 5) necrotic damage, and if the target is a creature, it can't regain\
    \ hit points until the start of the skeletal knight's next turn."
  "name": "Enervating Blade"
- "desc": "Melee or Ranged Weapon Attack: +8 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 14 (2d8 + 5) slashing damage."
  "name": "Throwing Axe"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Skeletal%20Knight.webp"
```
^statblock

```encounter-table
name: Skeletal Knight
creatures:
 - 1: Skeletal Knight
```