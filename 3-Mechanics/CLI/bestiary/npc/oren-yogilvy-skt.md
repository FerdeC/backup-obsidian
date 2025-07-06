---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/
- monster/size/small
- monster/type/humanoid/strongheart-halfling
aliases: ["Oren Yogilvy"]
NoteIcon: monster
BestiaryType: humanoid (Strongheart halfling)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 252
---
# [Oren Yogilvy](2-Mechanics\CLI\bestiary\npc/oren-yogilvy-skt.md)
*Source: Storm King's Thunder p. 252*  

Oren came to Northfurrow's End looking for easy work and found it. He sings for his supper, drinks like a fish, and wan ders the fields at night dreaming up new lyrics to entertain the inn's other guests. Oren likes to stir up trouble from time to time, but he doesn't have a mean bone in his body.

Ideal:"Music is food for the soul."

Bond:"You had me at ?Can I buy you a drink?'"

Flaw:"I have a knack for putting myself in harm's way. Good thing I'm lucky!"

```statblock
"name": "Oren Yogilvy (SKT)"
"size": "Small"
"type": "humanoid"
"subtype": "Strongheart halfling"
"alignment": "Chaotic Good"
"ac": !!int "11"
"hp": !!int "9"
"hit_dice": "2d6 + 2"
"stats":
- !!int "8"
- !!int "13"
- !!int "12"
- !!int "11"
- !!int "10"
- !!int "16"
"speed": "25 ft."
"skillsaves":
  "Perception": !!int "2"
  "Performance": !!int "7"
  "Persuasion": !!int "5"
"damage_resistances": "poison"
"senses": "passive Perception 12"
"languages": "Common, Halfling"
"traits":
- "desc": "Oren can move through the space of any creature that is of a size larger\
    \ than his."
  "name": "Halfling Nimbleness"
- "desc": "When Oren rolls a 1 on an attack roll, ability check, or saving throw,\
    \ he can reroll the die and must use the new roll."
  "name": "Lucky"
- "desc": "Oren has advantage on saving throws against poison"
  "name": "Stout Resilience"
- "desc": "Oren came to Nurthfurrow's End looking for easy work and found it. He sings\
    \ for his supper, drinks like a fish, and wanders the fields at night dreaming\
    \ up new lyrics to entertain the inn's other guests. Oren likes to stir up trouble\
    \ from time to time, but he doesn't have a mean bone in his body.\n\nIdeal: \"\
    Music is food for the soul.\"\n\nBond: \"You had me at \"Can I buy you a drink.\"\
    \n\nFlaw: \"I have a knack for putting myself in harm's way. Good thing I'm lucky!\""
  "name": "Roleplaying Information"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 3 (1d4 + 1) piercing damage. Duvessa carries only\
    \ one dagger."
  "name": "Dagger"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Oren%20Yogilvy.webp"
```
^statblock

```encounter-table
name: Oren Yogilvy
creatures:
 - 1: Oren Yogilvy
```