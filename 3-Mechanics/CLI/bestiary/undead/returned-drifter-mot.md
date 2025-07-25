---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mot
- monster/cr/1-4
- monster/size/medium
- monster/type/undead
aliases: ["Returned Drifter"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Mythic Odysseys of Theros p. 240
---
# [Returned Drifter](2-Mechanics\CLI\bestiary\undead/returned-drifter-mot.md)
*Source: Mythic Odysseys of Theros p. 240*  

Many Returned are pitiable souls who managed to escape from the Underworld only to find themselves stripped of the passions that motivated their flight. Lacking purpose and shunned by the living, these Returned typically seek places where they'll be left in peace, such as lonely tombs or the necropoleis of Asphodel and Odunos. There they go through half-hearted parodies of life, impeded by distraction and ennui. Despite this, even the most languorous Returned defend themselves if threatened and might be pressed into the service of their more willful brethren.

Returned have escaped the Underworld and dwell among the living once more, but their second lives are rarely what they expected—not that they remember what it was they expected. As a result of having followed the Path of Phenax (see chapter 4), the Returned lose their identities, which manifest as separate beings known as eidolons. The experience of escaping the Underworld also causes them to lose their faces, which become expressionless surfaces with empty eye sockets and gaping mouths. These blank surfaces they cover with distinctive golden masks.

Returned reenter the world blank and undead. No longer possessing the ability to form long-term memories, they generally can't build meaningful relationships or establish new lives. Instead, most experience fleeting emotions and follow hollow routines, their existences reduced to shadow plays without weight or substance.

```statblock
"name": "Returned Drifter (MOT)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Neutral"
"ac": !!int "13"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "14"
- !!int "15"
- !!int "12"
- !!int "10"
- !!int "12"
- !!int "11"
"speed": "30 ft."
"damage_resistances": "necrotic"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "passive Perception 11"
"languages": "the languages it knew in life"
"cr": "1/4"
"traits":
- "desc": "The Returned has advantage on saving throws against any effect that turns\
    \ undead."
  "name": "Turn Resistance"
- "desc": "The Returned is immune to any effect that would sense its emotions or read\
    \ its thoughts. Wisdom ([Insight](/2-Mechanics/CLI/rules/skills.md#Insight)) checks\
    \ to ascertain the Returned's intentions or sincerity are made with disadvantage."
  "name": "Unreadable Face"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) slashing damage plus 3 (1d6) poison damage."
  "name": "Scimitar"
- "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit:\
    \ 4 (1d4 + 2) bludgeoning damage."
  "name": "Sling"
"source":
- "MOT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MOT/Returned%20Drifter.webp"
```
^statblock

```encounter-table
name: Returned Drifter
creatures:
 - 1: Returned Drifter
```