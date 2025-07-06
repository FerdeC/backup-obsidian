---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Kadroth"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 42
---
# [Kadroth](2-Mechanics\CLI\bestiary\npc/kadroth-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 42*  

From this usurped office, he coordinates all cult activities in Ten-Towns. It's a role he carved out for himself by asserting that he's tight with Levistus. He rules the roost by sheer force of personality, though it chafes him that Hethyl Arkorran has more respect and influence within the cult. Kadroth doesn't involve Avarice in cult affairs because he fears her spellcasting ability and her connection to the Arcane Brotherhood. She could take over the cult anytime she wanted, and Kadroth doesn't want to give her any reason to do so.

For all his political machinations, Kadroth is a visionary who has so far made the cult stronger through his actions and decisions. He spends hours behind his desk, staring into the burning fireplace and drawing inspiration from its crackling flames. The slightest disturbance upsets him.

Kadroth appreciates the wisdom of maintaining the illusion that Speaker Crannoc Siever is still in charge, if only to keep Caer-Dineval's townsfolk from becoming restless. Thus, when necessary, Kadroth has the town speaker brought to his office to sign official documents.

```statblock
"name": "Kadroth (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Evil"
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
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "any one language (usually Common), Infernal"
"cr": "2"
"traits":
- "desc": "Kadroth is a 4th-level spellcaster. Its spellcasting ability is Wisdom\
    \ (spell save DC 11, +3 to hit with spell attacks). Kadroth has the following\
    \ cleric spells prepared:\n\nCantrips (at will): [light](/2-Mechanics/CLI/spells/light.md),\
    \ [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1st level (4 slots): [command](/2-Mechanics/CLI/spells/command.md), [inflict\
    \ wounds](/2-Mechanics/CLI/spells/inflict-wounds.md), [shield of faith](/2-Mechanics/CLI/spells/shield-of-faith.md)\n\
    \n2nd level (3 slots): [hold person](/2-Mechanics/CLI/spells/hold-person.md),\
    \ [spiritual weapon](/2-Mechanics/CLI/spells/spiritual-weapon.md)"
  "name": "Spellcasting"
- "desc": "Kadroth\n\nAt will: [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1/day each: [darkness](/2-Mechanics/CLI/spells/darkness.md), [hellish rebuke](/2-Mechanics/CLI/spells/hellish-rebuke.md)"
  "name": "Innate Spellcasting"
- "desc": "Kadroth has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened)."
  "name": "Dark Devotion"
"actions":
- "desc": "Kadroth makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one creature. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Kadroth.webp"
```
^statblock

```encounter-table
name: Kadroth
creatures:
 - 1: Kadroth
```