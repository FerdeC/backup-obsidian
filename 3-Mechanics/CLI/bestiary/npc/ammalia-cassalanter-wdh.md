---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdh
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Ammalia Cassalanter"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Waterdeep: Dragon Heist p. 193
---
# [Ammalia Cassalanter](2-Mechanics\CLI\bestiary\npc/ammalia-cassalanter-wdh.md)
*Source: Waterdeep: Dragon Heist p. 193*  

The vainglorious lady of House Cassalanter is schooled in the arcane arts. Like her husband Victoro, she worships Asmodeus. When they were young, Ammalia and Victoro signed a contract with the archdevil, trading the souls of their children for power, good health, and long life. The soul of Osvaldo, their eldest son, was taken immediately, and he was transformed into a chain devil. The souls of the younger twins, Terenzio and Elzerina, will be taken when they turn nine years old.

A provision in the contract allows the Cassalanters to buy their way out of it, but doing so requires a tremendous amount of coin and a mass sacrifice of unfortunate people. While Victoro hunts for Dagult Neverember's lost cache of gold, Ammalia makes plans to host a poisoned feast in celebration of Founders' Day.

Ammalia is well mannered, well read, well traveled, and exceptionally shrewd. She is known for driving a hard bargain. Her hobby is lepidopterology, and her estate has the most beautiful butterfly garden. She allows her youngest children to play in the garden under her supervision.

```statblock
"name": "Ammalia Cassalanter (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "45"
"hit_dice": "10d8"
"stats":
- !!int "9"
- !!int "14"
- !!int "11"
- !!int "17"
- !!int "12"
- !!int "15"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
  "Intelligence": !!int "6"
"skillsaves":
  "Insight": !!int "4"
  "History": !!int "6"
  "Arcana": !!int "6"
  "Persuasion": !!int "5"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "passive Perception 11"
"languages": "Common, Draconic, Elvish, Infernal"
"cr": "5"
"traits":
- "desc": "Ammalia is a 9th-level spellcaster. Her spellcasting ability is Intelligence\
    \ (spell save DC 14, +6 to hit with spell attacks). She has the following wizard\
    \ spells prepared:\n\nCantrips (at will): [friends](/2-Mechanics/CLI/spells/friends.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [mending](/2-Mechanics/CLI/spells/mending.md),\
    \ [message](/2-Mechanics/CLI/spells/message.md)\n\n1st level (4 slots): [charm\
    \ person](/2-Mechanics/CLI/spells/charm-person.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md),\
    \ [magic missile](/2-Mechanics/CLI/spells/magic-missile.md)\n\n2nd level (3\
    \ slots): [hold person](/2-Mechanics/CLI/spells/hold-person.md), [invisibility](/2-Mechanics/CLI/spells/invisibility.md),\
    \ [suggestion](/2-Mechanics/CLI/spells/suggestion.md)\n\n3rd level (3 slots):\
    \ [fireball](/2-Mechanics/CLI/spells/fireball.md), [haste](/2-Mechanics/CLI/spells/haste.md),\
    \ [tongues](/2-Mechanics/CLI/spells/tongues.md)\n\n4th level (3 slots): [confusion](/2-Mechanics/CLI/spells/confusion.md),\
    \ [stoneskin](/2-Mechanics/CLI/spells/stoneskin.md)\n\n5th level (1 slots):\
    \ [hold monster](/2-Mechanics/CLI/spells/hold-monster.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d6\
    \ - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two\
    \ hands."
  "name": "Quarterstaff"
"source":
- "WDH"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDH/Ammalia%20Cassalanter.webp"
```
^statblock

```encounter-table
name: Ammalia Cassalanter
creatures:
 - 1: Ammalia Cassalanter
```