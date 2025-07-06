---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/bgdia
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Mortlock Vanthampur"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Baldur's Gate: Descent Into Avernus p. 26
---
# [Mortlock Vanthampur](2-Mechanics\CLI\bestiary\npc/mortlock-vanthampur-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 26*  

Mortlock is tolerated by his mother, Duke Thalamra Vanthampur, and despised by his older brothers, Thurstwell and Amrik, who view him as a simpleton and an abomination. Half of Mortlock's face was scarred by fire when he was a child, and his disfigurement gives him a fearsome countenance.

```statblock
"name": "Mortlock Vanthampur (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "12"
"hp": !!int "90"
"hit_dice": "12d8 + 36"
"stats":
- !!int "18"
- !!int "14"
- !!int "17"
- !!int "10"
- !!int "12"
- !!int "13"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "5"
  "Athletics": !!int "6"
"senses": "passive Perception 11"
"languages": "Common"
"cr": "3"
"traits":
- "desc": "Mortlock can reroll a saving throw that he fails. He must use the new roll."
  "name": "Indomitable (2/Day)"
"actions":
- "desc": "Mortlock makes two attacks with his greatclub."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 9 (2d4\
    \ + 4) bludgeoning damage, plus 5 (2d4) bludgeoning damage if Mortlock has\
    \ taken any damage since his last turn."
  "name": "Greatclub"
- "desc": "Ranged Weapon Attack: +4 to hit, range 100/400 ft., one target. Hit:\
    \ 7 (1d10 + 2) piercing damage."
  "name": "Heavy Crossbow"
"source":
- "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/BGDIA/Mortlock%20Vanthampur.webp"
```
^statblock

```encounter-table
name: Mortlock Vanthampur
creatures:
 - 1: Mortlock Vanthampur
```