---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/damaran-human
aliases: ["Grisha"]
NoteIcon: monster
BestiaryType: humanoid (Damaran human)
SourceType: Bestiary
BookSource: Out of the Abyss p. 232
---
# [Grisha](2-Mechanics\CLI\bestiary\npc/grisha-oota.md)
*Source: Out of the Abyss p. 232*  

```statblock
"name": "Grisha (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "Damaran human"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "[chain mail](/2-Mechanics/CLI/items/chain-mail.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "14"
- !!int "12"
- !!int "12"
- !!int "11"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Wisdom": !!int "4"
"skillsaves":
  "Religion": !!int "2"
  "Persuasion": !!int "5"
"senses": "passive Perception 12"
"languages": "Common, Undercommon"
"cr": "2"
"traits":
- "desc": "Grisha is a 6th-level-spellcaster. His spellcasting ability is Wisdom (spell\
    \ save DC 12, +4 to hit with spell attacks). He has the following cleric spells\
    \ prepared:\n\nCantrips (at will): [guidance](/2-Mechanics/CLI/spells/guidance.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md), [sacred flame](/2-Mechanics/CLI/spells/sacred-flame.md),\
    \ [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\n1st level (4 slots):\
    \ [cure wounds](/2-Mechanics/CLI/spells/cure-wounds.md), [divine favor](/2-Mechanics/CLI/spells/divine-favor.md),\
    \ [inflict wounds](/2-Mechanics/CLI/spells/inflict-wounds.md), [protection from\
    \ evil and good](/2-Mechanics/CLI/spells/protection-from-evil-and-good.md), [shield\
    \ of faith](/2-Mechanics/CLI/spells/shield-of-faith.md)\n\n2nd level (3 slots):\
    \ [continual flame](/2-Mechanics/CLI/spells/continual-flame.md), [hold person](/2-Mechanics/CLI/spells/hold-person.md),\
    \ [magic weapon](/2-Mechanics/CLI/spells/magic-weapon.md), [spiritual weapon](/2-Mechanics/CLI/spells/spiritual-weapon.md)\n\
    \n3rd level (3 slots): [bestow curse](/2-Mechanics/CLI/spells/bestow-curse.md),\
    \ [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), [spirit guardians](/2-Mechanics/CLI/spells/spirit-guardians.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Grisha makes two attacks with his +1 flail."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) bludgeoning damage"
  "name": "+1 Flail"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Grisha.webp"
```
^statblock

```encounter-table
name: Grisha
creatures:
 - 1: Grisha
```