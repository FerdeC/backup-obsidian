---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/goblinoid
aliases: ["Bugbear Lieutenant"]
NoteIcon: monster
BestiaryType: humanoid (goblinoid)
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 173
---
# [Bugbear Lieutenant](2-Mechanics\CLI\bestiary\humanoid/bugbear-lieutenant-tftyp.md)
*Source: Tales from the Yawning Portal p. 173*  

```statblock
"name": "Bugbear Lieutenant (TftYP)"
"size": "Medium"
"type": "humanoid"
"subtype": "goblinoid"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "15"
- !!int "14"
- !!int "13"
- !!int "8"
- !!int "11"
- !!int "9"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Survival": !!int "2"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Goblin"
"cr": "1"
"traits":
- "desc": "A melee weapon deals one extra die of its damage when the bugbear hits\
    \ with it (included in the attack)."
  "name": "Brute"
- "desc": "If the bugbear surprises a creature and hits it with an attack during the\
    \ first round of combat, the target takes an extra 7 (2d6) damage from the attack."
  "name": "Surprise Attack"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 10 ft., one target. Hit: 11\
    \ (2d8 + 2) slashing damage, or 13 (2d10 + 2) slashing damage if used with\
    \ both hands."
  "name": "Longsword"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 9 (2d6 + 2) piercing damage in melee or 5 (1d6 +\
    \ 2) piercing damage at range."
  "name": "Javelin"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Bugbear%20Lieutenant.webp"
```
^statblock

```encounter-table
name: Bugbear Lieutenant
creatures:
 - 1: Bugbear Lieutenant
```