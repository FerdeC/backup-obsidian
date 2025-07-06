---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/hotdq
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Captain Othelstan"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Hoard of the Dragon Queen p. 89
---
# [Captain Othelstan](2-Mechanics\CLI\bestiary\npc/captain-othelstan-hotdq.md)
*Source: Hoard of the Dragon Queen p. 89*  

```statblock
"name": "Captain Othelstan (HotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "19"
"ac_class": "[splint armor](/2-Mechanics/CLI/items/splint-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "93"
"hit_dice": "11d10 + 33"
"stats":
- !!int "19"
- !!int "10"
- !!int "16"
- !!int "13"
- !!int "14"
- !!int "12"
"speed": "30 ft."
"saves":
  "Strength": !!int "7"
  "Constitution": !!int "6"
"skillsaves":
  "Intimidation": !!int "7"
  "Athletics": !!int "7"
  "Religion": !!int "4"
  "Perception": !!int "5"
"senses": "passive Perception 15"
"languages": "Common, Draconic, Giant"
"cr": "5"
"traits":
- "desc": "On his turn, Othelstan can take one additional action."
  "name": "Action Surge (Recharges on a Short or Long Rest)"
- "desc": "When Othelstan takes damage that reduces him to 0 hit points, he immediately\
    \ regains 20 hit points. If he has 20 hit points or fewer at the end of his next\
    \ turn, he dies."
  "name": "Tiamat's Blessing of Retribution"
"actions":
- "desc": "Othelstan attacks twice with his flail or spear, or makes two ranged attacks\
    \ with his spears."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) bludgeoning damage."
  "name": "Flail"
- "desc": "Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or ranged 20/60\
    \ ft., one target. Hit: 7 (1d6 + 4) piercing damage."
  "name": "Spear"
"source":
- "HotDQ"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/HotDQ/Captain%20Othelstan.webp"
```
^statblock

```encounter-table
name: Captain Othelstan
creatures:
 - 1: Captain Othelstan
```