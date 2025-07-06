---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/4
- monster/size/medium
- monster/type/construct
aliases: ["Dzaan"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 271
---
# [Dzaan](2-Mechanics\CLI\bestiary\npc/dzaan-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 271*  

Dzaan was a Red Wizard of Thay who studied the arcane tradition of illusion. The leaders of the Arcane Brotherhood welcomed him with open arms, eager to count a Red Wizard among their ranks. Dzaan might have become a force to reckon with in the brotherhood had his quest for power not led him to Icewind Dale, where he was killed by the people of Easthaven after making a few too many enemies.

## Dzaan's Demise

Dzaan's trouble started after he broke away from his fellow wizards and hired adventurers to scour Icewind Dale for Netherese ruins. One group of them uncovered a buried tower in the tundra (see "Lost Spire of Netheril"), and Dzaan went out of his way to eliminate anyone who knew of it, including the adventurers who found it and several Ten-Towners with whom they had spoken. After turning the tower into his secret base, Dzaan visited Easthaven to gather supplies. Although he took the precaution of adopting a magical disguise, members of the local militia recognized Dzaan by the way he walked and spoke. They captured him, gagged him, confiscated his spellbook, and condemned him to death.

## Companion

Because they're so despised throughout Faerûn, Red Wizards often adopt disguises and rarely travel abroad without an escort. They generally favor undead servants and bodyguards, since they find that undead tend to be more obedient than the living. Dzaan's bodyguard is a Thayan [wight](/2-Mechanics/CLI/bestiary/undead/wight.md) named Krintaas. When Dzaan returned to Easthaven, he ordered his companion to stay with the simulacrum and watch over it and the buried Netherese spire.

```statblock
"name": "Dzaan (IDRotF)"
"size": "Medium"
"type": "construct"
"alignment": "Lawful Evil"
"ac": !!int "10"
"hp": !!int "49"
"hit_dice": "9d8 + 9"
"stats":
- !!int "10"
- !!int "11"
- !!int "12"
- !!int "16"
- !!int "13"
- !!int "15"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "3"
  "Intelligence": !!int "5"
"skillsaves":
  "Deception": !!int "4"
  "History": !!int "5"
  "Arcana": !!int "5"
"senses": "passive Perception 11"
"languages": "Abyssal, Common, Giant, Infernal"
"cr": "4"
"traits":
- "desc": "Dzaan is a 9th-level spellcaster. His spellcasting ability is Intelligence\
    \ (spell save DC 13, +5 to hit with spell attacks). He has the following wizard\
    \ spells prepared:\n\nAt will: , \n\nCantrips (at will): [acid splash](/2-Mechanics/CLI/spells/acid-splash.md)\
    \ , [light](/2-Mechanics/CLI/spells/light.md), [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md),\
    \ [shocking grasp](/2-Mechanics/CLI/spells/shocking-grasp.md) \n\n1st level\
    \ (4 slots): [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [disguise\
    \ self](/2-Mechanics/CLI/spells/disguise-self.md), [magic missile](/2-Mechanics/CLI/spells/magic-missile.md)\
    \ \n\n2nd level (3 slots): [invisibility](/2-Mechanics/CLI/spells/invisibility.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md), [phantasmal force](/2-Mechanics/CLI/spells/phantasmal-force.md)\n\
    \n3rd level (3 slots): [fireball](/2-Mechanics/CLI/spells/fireball.md), [sending](/2-Mechanics/CLI/spells/sending.md),\
    \ [slow](/2-Mechanics/CLI/spells/slow.md)\n\n4th level (3 slots): [arcane\
    \ eye](/2-Mechanics/CLI/spells/arcane-eye.md), [confusion](/2-Mechanics/CLI/spells/confusion.md)\n\
    \n5th level (1 slots): [animate objects](/2-Mechanics/CLI/spells/animate-objects.md)\n\
    \nSee \"Actions\" below."
  "name": "Spellcasting"
"actions":
- "desc": "Melee Spell Attack: +5 to hit, reach 5 ft., one creature (the attack\
    \ roll has advantage if the target is wearing armor made of metal). Hit: 9 (2d8)\
    \ lightning damage, and the target can't take reactions until the start of its\
    \ next turn."
  "name": "Shocking Grasp (Cantrip)"
- "desc": "Dzaan hurls a bubble of acid at one creature it can see within 60 feet\
    \ of it, or at two such creatures that are within 5 feet of each other. A target\
    \ must succeed on a DC 13 Dexterity saving throw or take 7 (2d6) acid damage."
  "name": "Acid Splash (Cantrip)"
- "desc": "Dzaan creates three darts of magical force. Each dart unerringly strikes\
    \ one creature Dzaan can see within 120 feet of it, dealing 3 (1d4 + 1) force\
    \ damage. If Dzaan casts this spell using a 2nd-level spell slot, it creates one\
    \ more dart."
  "name": "Magic Missile (1st-Level Spell; Requires a Spell Slot)"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Dzaan.webp"
```
^statblock

```encounter-table
name: Dzaan
creatures:
 - 1: Dzaan
```