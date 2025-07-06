---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/gos
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/sahuagin
aliases: ["Sahuagin Deep Diver"]
NoteIcon: monster
BestiaryType: humanoid (sahuagin)
SourceType: Bestiary
BookSource: Ghosts of Saltmarsh p. 250
---
# [Sahuagin Deep Diver](2-Mechanics\CLI\bestiary\humanoid/sahuagin-deep-diver-gos.md)
*Source: Ghosts of Saltmarsh p. 250*  

These mighty sahuagin, found in The Final Enemy, are transformed by the divine magic of Sekolah to enable them to better explore the darkest depths of the ocean. Out of the water, they cling to shadows and serve as hunters and assassins. A long, scaly lure that can be illuminated extends from a deep diver's forehead.

```statblock
"name": "Sahuagin Deep Diver (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "sahuagin"
"alignment": "Lawful Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "91"
"hit_dice": "14d8 + 28"
"stats":
- !!int "14"
- !!int "16"
- !!int "15"
- !!int "12"
- !!int "13"
- !!int "9"
"speed": "30 ft., swim 40 ft."
"saves":
  "Wisdom": !!int "3"
  "Constitution": !!int "4"
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "5"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": "Sahuagin"
"cr": "4"
"traits":
- "desc": "The deep diver has advantage on melee attack rolls against any creature\
    \ that doesn't have all its hit points."
  "name": "Blood Frenzy"
- "desc": "The deep diver has advantage on Dexterity ([Stealth](/2-Mechanics/CLI/rules/skills.md#Stealth))\
    \ checks made while submerged in water."
  "name": "Brine Lurker"
- "desc": "The deep diver can breathe air and water, but it needs to be submerged\
    \ at least once every 4 hours to avoid suffocating."
  "name": "Limited Amphibiousness"
- "desc": "The deep diver can cause its lure to light up or darken at will. While\
    \ the lure is lit, the deep diver sheds bright light in a 30-foot radius centered\
    \ on itself and dim light for an additional 20 feet."
  "name": "Lure"
- "desc": "The deep diver can magically command any shark within 120 feet of it, using\
    \ a limited telepathy."
  "name": "Shark Telepathy"
"actions":
- "desc": "The deep diver makes two attacks with its glaive, or one attack with its\
    \ bite and two with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 10 ft., one target. Hit: 13\
    \ (2d10 + 2) slashing damage."
  "name": "Glaive"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (1d10\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) slashing damage."
  "name": "Claws"
- "desc": "The deep diver pulses magical light from its lure. Any creature within\
    \ 30 feet of the deep diver that can see the light must succeed on a DC 11 Wisdom\
    \ saving throw or be [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed) until\
    \ the end of its next turn. A creature [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)\
    \ in this way is [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)\
    \ as it stares at the light."
  "name": "Light of Sekolah"
"source":
- "GoS"
- "LR"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GoS/Sahuagin%20Deep%20Diver.webp"
```
^statblock

```encounter-table
name: Sahuagin Deep Diver
creatures:
 - 1: Sahuagin Deep Diver
```