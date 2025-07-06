---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/1
- monster/size/large
- monster/type/beast
aliases: ["Giant Rocktopus"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Out of the Abyss p. 28
---
# [Giant Rocktopus](2-Mechanics\CLI\bestiary\beast/giant-rocktopus-oota.md)
*Source: Out of the Abyss p. 28*  

```statblock
"name": "Giant Rocktopus (OotA)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "52"
"hit_dice": "8d10 + 8"
"stats":
- !!int "17"
- !!int "13"
- !!int "13"
- !!int "4"
- !!int "10"
- !!int "4"
"speed": "20 ft., climb 10 ft."
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": ""
"cr": "1"
"traits":
- "desc": "The octopus has advantage on Dexterity ([Stealth](/2-Mechanics/CLI/rules/skills.md#Stealth))\
    \ checks."
  "name": "Camouflage"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 15 ft., one target. Hit: 10\
    \ (2d6 + 3) bludgeoning damage. If the target is a creature, it is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 16). Until this grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and the octopus can't use its tentacles on another target."
  "name": "Tentacles"
- "desc": "A 20-foot-radius cloud of ink extends all around the octopus if it is underwater.\
    \ The area is heavily obscured for 1 minute, although a significant current can\
    \ disperse the ink. After releasing the ink, the octopus can use the Dash action\
    \ as a bonus action."
  "name": "Ink Cloud (Recharges after a Short or Long Rest)"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Giant%20Rocktopus.webp"
```
^statblock

```encounter-table
name: Giant Rocktopus
creatures:
 - 1: Giant Rocktopus
```