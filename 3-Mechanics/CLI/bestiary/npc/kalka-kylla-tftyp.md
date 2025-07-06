---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/3
- monster/size/large
- monster/type/monstrosity
aliases: ["Kalka-Kylla"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 238
---
# [Kalka-Kylla](2-Mechanics\CLI\bestiary\npc/kalka-kylla-tftyp.md)
*Source: Tales from the Yawning Portal p. 238*  

```statblock
"name": "Kalka-Kylla (TftYP)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "10d10 + 30"
"stats":
- !!int "17"
- !!int "12"
- !!int "16"
- !!int "15"
- !!int "16"
- !!int "12"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Deception": !!int "3"
  "Stealth": !!int "3"
  "Insight": !!int "5"
"senses": "blindsight 30 ft., passive Perception 13"
"languages": "Olman"
"cr": "3"
"traits":
- "desc": "Kalka-Kylla can breathe air and water."
  "name": "Amphibious"
- "desc": "While Kalka-Kylla remains motionless and hidden in its shell, it is indistinguishable\
    \ from a polished boulder."
  "name": "False Appearance"
- "desc": "Kalka-Kylla can use a bonus action to retract into or emerge from its shell.\
    \ While retracted, Kalka-Kylla gains a +4 bonus to AC, and it has a speed of 0\
    \ and can't benefit from bonuses to speed."
  "name": "Shell"
"actions":
- "desc": "Kalka-Kylla makes two claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) bludgeoning damage, and if the target is a Medium or smaller creature,\
    \ it is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled) (escape DC 13).\
    \ Until this grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained).\
    \ Kalka-Kylla has two claws, each of which can grapple only one target."
  "name": "Claw"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Kalka-Kylla.webp"
```
^statblock

```encounter-table
name: Kalka-Kylla
creatures:
 - 1: Kalka-Kylla
```