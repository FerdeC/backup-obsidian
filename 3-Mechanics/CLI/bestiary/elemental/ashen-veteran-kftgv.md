---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/3
- monster/size/medium
- monster/type/elemental
aliases: ["Ashen Veteran"]
NoteIcon: monster
BestiaryType: elemental
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 154
---
# [Ashen Veteran](2-Mechanics\CLI\bestiary\elemental/ashen-veteran-kftgv.md)
*Source: Keys from the Golden Vault p. 154*  

Veterans are professional fighters that take up arms for pay or to protect something they believe in or value. Their ranks include soldiers retired from long service and warriors who never served anyone but themselves.

```statblock
"name": "Ashen Veteran (KftGV)"
"size": "Medium"
"type": "elemental"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "[splint armor](/2-Mechanics/CLI/items/splint-armor.md)"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"stats":
- !!int "16"
- !!int "13"
- !!int "14"
- !!int "10"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "5"
  "Perception": !!int "2"
"damage_immunities": "fire"
"senses": "passive Perception 12"
"languages": "any one language (usually Common)"
"cr": "3"
"traits":
- "desc": "When the veteran drops to 0 hit points, it is reduced to a pile of ash,\
    \ and any equipment it was wearing or carrying falls to the ground."
  "name": "Ashen Creature"
"actions":
- "desc": "The veteran makes two longsword attacks. If it has a shortsword drawn,\
    \ it can also make a shortsword attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands."
  "name": "Longsword"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +3 to hit, range 100/400 ft., one target. Hit:\
    \ 6 (1d10 + 1) piercing damage."
  "name": "Heavy Crossbow"
"source":
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/KftGV/Ashen%20Veteran.webp"
```
^statblock

```encounter-table
name: Ashen Veteran
creatures:
 - 1: Ashen Veteran
```