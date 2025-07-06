---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cos
- monster/cr/6
- monster/size/medium
- monster/type/construct
aliases: ["Strahd's Animated Armor"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Curse of Strahd p. 227
---
# [Strahd's Animated Armor](2-Mechanics\CLI\bestiary\npc/strahds-animated-armor-cos.md)
*Source: Curse of Strahd p. 227*  

The armor that Strahd wore into battle when he was alive lives on today as a headless, animated suit of plate armor. The armor is painted burgundy and adorned with golden angelic motifs.

## Thing of Evil

Strahd imbued his automaton with a sliver of his being, bequeathing unto his armor a malevolence not found in most animated objects. He also fortified his armor and placed a number of permanent spell effects on it to make the armor a better castle defender.

The armor understands Common but obeys only the commands of its master.

```statblock
"name": "Strahd's Animated Armor (CoS)"
"size": "Medium"
"type": "construct"
"alignment": "Lawful Evil"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"stats":
- !!int "17"
- !!int "13"
- !!int "16"
- !!int "9"
- !!int "10"
- !!int "9"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "3"
"damage_resistances": "cold, fire"
"damage_immunities": "lightning, poison"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 13"
"languages": "understands Common but can't speak"
"cr": "6"
"traits":
- "desc": "An animated object doesn't require air, food, drink, or sleep.\n\nThe magic\
    \ that animates an object is dispelled when the construct drops to 0 hit points.\
    \ An animated object reduced to 0 hit points becomes inanimate and is too damaged\
    \ to be of much use or value to anyone."
  "name": "Constructed Nature"
- "desc": "The armor is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ while in the area of an [antimagic field](/2-Mechanics/CLI/spells/antimagic-field.md).\
    \ If targeted by [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), the\
    \ armor must succeed on a Constitution saving throw against the caster's spell\
    \ save DC or fall [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious)\
    \ for 1 minute."
  "name": "Antimagic Susceptibility"
- "desc": "While the armor remains motionless, it is indistinguishable from a normal\
    \ suit of armor."
  "name": "False Appearance"
"actions":
- "desc": "The armor makes two melee attacks or uses Shocking Bolt twice."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) slashing damage plus 3 (1d6) lightning damage."
  "name": "Greatsword"
- "desc": "Ranged Spell Attack: +4 to hit (with advantage on the attack roll if\
    \ the target is wearing armor made of metal), range 60 ft., one target. Hit:\
    \ 10 (3d6) lightning damage."
  "name": "Shocking Bolt"
"source":
- "CoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CoS/Strahd%27s%20Animated%20Armor.webp"
```
^statblock

```encounter-table
name: Strahd's Animated Armor
creatures:
 - 1: Strahd's Animated Armor
```