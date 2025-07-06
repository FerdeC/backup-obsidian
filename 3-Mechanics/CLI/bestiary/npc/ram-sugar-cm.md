---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cm
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/dragonborn
aliases: ["Ram Sugar"]
NoteIcon: monster
BestiaryType: humanoid (dragonborn)
SourceType: Bestiary
BookSource: Candlekeep Mysteries p. 132
---
# [Ram Sugar](2-Mechanics\CLI\bestiary\npc/ram-sugar-cm.md)
*Source: Candlekeep Mysteries p. 132*  

Fanatics are often part of a cult's leadership, using their charisma and dogma to influence and prey on those of weak will. Most are interested in personal power above all else.

```statblock
"name": "Ram Sugar (CM)"
"size": "Medium"
"type": "humanoid"
"subtype": "dragonborn"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "11"
- !!int "14"
- !!int "12"
- !!int "10"
- !!int "13"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "4"
  "Religion": !!int "2"
  "Persuasion": !!int "4"
"damage_resistances": "fire"
"senses": "passive Perception 11"
"languages": "Common, Draconic"
"cr": "2"
"traits":
- "desc": "Ram Sugar is a 4th-level spellcaster. Its spellcasting ability is Wisdom\
    \ (spell save DC 11, +3 to hit with spell attacks). Ram Sugar has the following\
    \ cleric spells prepared:\n\nCantrips (at will): [light](/2-Mechanics/CLI/spells/light.md),\
    \ [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1st level (4 slots): [command](/2-Mechanics/CLI/spells/command.md), [inflict\
    \ wounds](/2-Mechanics/CLI/spells/inflict-wounds.md), [shield of faith](/2-Mechanics/CLI/spells/shield-of-faith.md)\n\
    \n2nd level (3 slots): [hold person](/2-Mechanics/CLI/spells/hold-person.md),\
    \ [spiritual weapon](/2-Mechanics/CLI/spells/spiritual-weapon.md)"
  "name": "Spellcasting"
- "desc": "Ram Sugar has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Dark Devotion"
"actions":
- "desc": "Ram Sugar makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one creature. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
- "desc": "Ram Sugar exhales fire in a 30-foot-long line that is 5 feet wide. Any\
    \ creature in the line must make a DC 11 Dexterity saving throw, taking 7 (2d6)\
    \ fire damage on a failed save, or half as much damage on a successful one."
  "name": "Breath Weapon (Recharges after a Short or Long Rest)"
"source":
- "CM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CM/Ram%20Sugar.webp"
```
^statblock

```encounter-table
name: Ram Sugar
creatures:
 - 1: Ram Sugar
```