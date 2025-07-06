---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wbtw
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/cleric
- monster/type/humanoid/human
aliases: ["Mercion"]
NoteIcon: monster
BestiaryType: humanoid (cleric, human)
SourceType: Bestiary
BookSource: The Wild Beyond the Witchlight p. 224
---
# [Mercion](2-Mechanics\CLI\bestiary\npc/mercion-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 224*  

Mercion strikes the balance of a natural leader and a protective caregiver. She has a direct manner that reassures and inspires those around her.

Mercion does not worship a deity, but rather an ideal: that truth gives life to artistry and beauty, and that those who embrace deceit should be censured and punished. Light is her domain.

```statblock
"name": "Mercion (WBtW)"
"size": "Medium"
"type": "humanoid"
"subtype": "cleric, human"
"alignment": "Lawful Good"
"ac": !!int "19"
"ac_class": "[plate armor](/2-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "31"
"hit_dice": "9d8 - 9"
"stats":
- !!int "15"
- !!int "10"
- !!int "9"
- !!int "12"
- !!int "17"
- !!int "17"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Wisdom": !!int "5"
"skillsaves":
  "Medicine": !!int "5"
  "Insight": !!int "5"
"senses": "passive Perception 13"
"languages": "Common, Dwarvish"
"cr": "3"
"traits":
- "desc": "Mercion casts one of the following spells, using Wisdom as the spellcasting\
    \ ability (spell save DC 13):\n\nAt will: [light](/2-Mechanics/CLI/spells/light.md),\
    \ [spare the dying](/2-Mechanics/CLI/spells/spare-the-dying.md)\n\n1/day:\
    \ [death ward](/2-Mechanics/CLI/spells/death-ward.md)\n\n2/day each: [command](/2-Mechanics/CLI/spells/command.md),\
    \ [create food and water](/2-Mechanics/CLI/spells/create-food-and-water.md), [cure\
    \ wounds](/2-Mechanics/CLI/spells/cure-wounds.md), [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md),\
    \ [hold person](/2-Mechanics/CLI/spells/hold-person.md), [revivify](/2-Mechanics/CLI/spells/revivify.md)"
  "name": "Spellcasting"
- "desc": "Mercion wields a +1 quarterstaff."
  "name": "Special Equipment"
"actions":
- "desc": "Mercion makes one Divine Radiance attack and one +1 Quarterstaff attack.\
    \ She can replace one of these attacks with a use of Spellcasting."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 60 ft.,\
    \ one target. Hit: 13 (3d8) radiant damage."
  "name": "Divine Radiance"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) bludgeoning damage, or 7 (1d8 + 3) bludgeoning damage when used with\
    \ two hands."
  "name": "+1 Quarterstaff"
- "desc": "Mercion creates a magical explosion of fiery radiance centered on a point\
    \ she can see within 120 feet of her. Each creature in a 20-foot-radius sphere\
    \ centered on that point must make a DC 13 Dexterity saving throw, taking 28 (8d6)\
    \ radiant damage on a failed save, or half as much damage on a successful one."
  "name": "Radiant Fire (Recharge 5-6)"
"source":
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WBtW/Mercion.webp"
```
^statblock

```encounter-table
name: Mercion
creatures:
 - 1: Mercion
```