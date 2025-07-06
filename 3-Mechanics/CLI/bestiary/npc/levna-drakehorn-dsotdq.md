---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/dsotdq
- monster/cr/
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Levna Drakehorn"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Dragonlance: Shadow of the Dragon Queen p. 213
---
# [Levna Drakehorn](2-Mechanics\CLI\bestiary\npc/levna-drakehorn-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 213*  

Though a recent inductee into the Order of the Rose, [Levna](/2-Mechanics/CLI/bestiary/npc/levna-drakehorn-dsotdq.md) is a confident, experienced Solamnic knight. She is brave, decisive, and deadly with her two-handed sword. After a chance encounter with agents of the Blue Dragon Army, Levna was left with a distinctive, branching scar. She claims it came from the breath of a blue dragon, but few of her fellow Knights of Solamnia believe her.

```statblock
"name": "Levna Drakehorn (DSotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Good"
"ac": !!int "18"
"ac_class": "[plate](/2-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "13"
"hit_dice": "2d8 + 4"
"stats":
- !!int "15"
- !!int "10"
- !!int "14"
- !!int "10"
- !!int "11"
- !!int "14"
"speed": "30 ft."
"saves":
  "Constitution": !!int "4"
"skillsaves":
  "Intimidation": !!int "4"
  "Athletics": !!int "4"
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "Common"
"traits":
- "desc": "Levna is proficient with simple and martial weapons, shields, and all armor."
  "name": "Bonus Proficiencies"
- "desc": "Levna has advantage on an attack roll against a creature if at least one\
    \ of her allies is within 5 feet of the creature and the ally isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 9 (2d6\
    \ + 2) slashing damage."
  "name": "Greatsword"
"reactions":
- "desc": "When a creature Levna can see within 5 feet of her is targeted by an attack,\
    \ she can impose disadvantage on the attack roll if she can see the attacker and\
    \ she is wielding a melee weapon."
  "name": "Protection"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/DSotDQ/Levna%20Drakehorn.webp"
```
^statblock

```encounter-table
name: Levna Drakehorn
creatures:
 - 1: Levna Drakehorn
```