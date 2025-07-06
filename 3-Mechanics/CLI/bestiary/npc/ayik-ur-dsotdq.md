---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Ayik Ur"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 211
---
# [Ayik Ur](2-Mechanics\CLI\bestiary\npc/ayik-ur-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 211*  

The youthful archer [Ayik](/2-Mechanics/CLI/bestiary/npc/ayik-ur-dsotdq.md) is the consummate survivor. As the Dragon Armies swarmed over his homeland of Khur, he became a refugee, but not before his leg was injured by a charging warhorse. Even as he fled, he swore to lend his bow in the fight against the Dragon Armies. He is defiant and cocky to the point of recklessness, challenging his enemies to finish what the Dragon Armies started back in Khur.

```statblock
"name": "Ayik Ur (DSotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Good"
"ac": !!int "15"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "11"
- !!int "16"
- !!int "12"
- !!int "11"
- !!int "13"
- !!int "11"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
"skillsaves":
  "Nature": !!int "2"
  "Athletics": !!int "2"
  "Stealth": !!int "5"
  "Perception": !!int "5"
  "Survival": !!int "3"
"senses": "passive Perception 15"
"languages": "Common"
"traits":
- "desc": "Ayik gains a +2 bonus to all attack rolls (included below)."
  "name": "Attacker"
- "desc": "Ayik is proficient with simple and martial weapons, shields, and all armor."
  "name": "Bonus Proficiencies"
"actions":
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +7 to hit, range 150/600 ft., one target. Hit:\
    \ 7 (1d8 + 3) piercing damage."
  "name": "Longbow"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Ayik%20Ur.webp"
```
^statblock

```encounter-table
name: Ayik Ur
creatures:
 - 1: Ayik Ur
```