---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Mennek Ariz"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 157
---
# [Mennek Ariz](2-Mechanics\CLI\bestiary\npc/mennek-ariz-tftyp.md)
*Source: Tales from the Yawning Portal p. 157*  

```statblock
"name": "Mennek Ariz (TftYP)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "40"
"hit_dice": "9d8"
"stats":
- !!int "9"
- !!int "14"
- !!int "11"
- !!int "17"
- !!int "12"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
  "Intelligence": !!int "6"
"skillsaves":
  "History": !!int "6"
  "Arcana": !!int "6"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "5"
"traits":
- "desc": "Mennek is a 9th-level spellcaster. Its spellcasting ability is Intelligence\
    \ (spell save DC 14, +6 to hit with spell attacks). Mennek has the following\
    \ wizard spells prepared:\n\nCantrips (at will): [friends](/2-Mechanics/CLI/spells/friends.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [mending](/2-Mechanics/CLI/spells/mending.md),\
    \ [message](/2-Mechanics/CLI/spells/message.md)\n\n1st level (4 slots): [charm\
    \ person](/2-Mechanics/CLI/spells/charm-person.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md),\
    \ [magic missile](/2-Mechanics/CLI/spells/magic-missile.md)\n\n2nd level (3\
    \ slots): [hold person](/2-Mechanics/CLI/spells/hold-person.md), [invisibility](/2-Mechanics/CLI/spells/invisibility.md),\
    \ [suggestion](/2-Mechanics/CLI/spells/suggestion.md)\n\n3rd level (3 slots):\
    \ [fireball](/2-Mechanics/CLI/spells/fireball.md), [haste](/2-Mechanics/CLI/spells/haste.md),\
    \ [tongues](/2-Mechanics/CLI/spells/tongues.md)\n\n4th level (3 slots): [dominate\
    \ beast](/2-Mechanics/CLI/spells/dominate-beast.md), [stoneskin](/2-Mechanics/CLI/spells/stoneskin.md)\n\
    \n5th level (2 slots): [hold monster](/2-Mechanics/CLI/spells/hold-monster.md)\n\
    \nEnchantment spell of 1st level or higher"
  "name": "Spellcasting"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d6\
    \ - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two\
    \ hands."
  "name": "Quarterstaff"
"reactions":
- "desc": "Mennek tries to magically divert an attack made against it, provided that\
    \ the attacker is within 30 feet of it and visible to it. Mennek must decide to\
    \ do so before the attack hits or misses.\n\nThe attacker must make a DC 14 Wisdom\
    \ saving throw. On a failed save, the attacker targets the creature closest to\
    \ it, other than Mennek or itself. If multiple creatures are closest, the attacker\
    \ chooses which one to target."
  "name": "Instinctive Charm (Recharges after the Enchanter Casts an Enchantment Spell\
    \ of 1st level or Higher)"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Mennek%20Ariz.webp"
```
^statblock

```encounter-table
name: Mennek Ariz
creatures:
 - 1: Mennek Ariz
```