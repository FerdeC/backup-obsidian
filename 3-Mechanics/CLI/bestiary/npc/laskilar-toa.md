---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Laskilar"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 67
---
# [Laskilar](2-Mechanics\CLI\bestiary\npc/laskilar-toa.md)
*Source: Tomb of Annihilation p. 67*  

```statblock
"name": "Laskilar (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "15"
- !!int "16"
- !!int "14"
- !!int "14"
- !!int "11"
- !!int "14"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "2"
  "Strength": !!int "4"
"skillsaves":
  "Athletics": !!int "4"
  "Deception": !!int "4"
"senses": "passive Perception 10"
"languages": "any two languages"
"cr": "2"
"traits":
- "desc": "Laskilar wears a [cape of the mountebank](/2-Mechanics/CLI/items/cape-of-the-mountebank.md)."
  "name": "Special Equipment"
"actions":
- "desc": "Laskilar makes three melee attacks: two with its scimitar and one with\
    \ its dagger. Or Laskilar makes two ranged attacks with its daggers."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Scimitar"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage."
  "name": "Dagger"
"reactions":
- "desc": "Laskilar adds 2 to its AC against one melee attack that would hit it. To\
    \ do so, Laskilar must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Laskilar.webp"
```
^statblock

```encounter-table
name: Laskilar
creatures:
 - 1: Laskilar
```