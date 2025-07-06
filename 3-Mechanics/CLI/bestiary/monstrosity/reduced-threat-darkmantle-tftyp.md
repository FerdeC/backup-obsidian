---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/1-2
- monster/size/small
- monster/type/monstrosity
aliases: ["Reduced-Threat Darkmantle"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 113
---
# [Reduced-Threat Darkmantle](2-Mechanics\CLI\bestiary\monstrosity/reduced-threat-darkmantle-tftyp.md)
*Source: Tales from the Yawning Portal p. 113*  

```statblock
"name": "Reduced-Threat Darkmantle (TftYP)"
"size": "Small"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "11"
"hit_dice": "5d6 + 5"
"stats":
- !!int "16"
- !!int "12"
- !!int "13"
- !!int "2"
- !!int "10"
- !!int "5"
"speed": "10 ft., fly 30 ft."
"skillsaves":
  "Stealth": !!int "1"
"senses": "blindsight 60 ft., passive Perception 10"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "A reduced-threat monster takes a −2 penalty on attack rolls (included in\
    \ the stat block), ability checks (included in the stat block for skill proficiencies),\
    \ saving throws (included in the stat block for saving throw proficiencies), and\
    \ saving throw DCs (included in the stat block)."
  "name": "Reduced Threat"
- "desc": "The darkmantle can't use its blindsight while [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened)."
  "name": "Echolocation"
- "desc": "While the darkmantle remains motionless, it is indistinguishable from a\
    \ cave formation such as a stalactite or stalagmite."
  "name": "False Appearance"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one creature. Hit: 6\
    \ (1d6 + 3) bludgeoning damage, and the darkmantle attaches to the target. If\
    \ the target is Medium or smaller and the darkmantle has advantage on the attack\
    \ roll, it attaches by engulfing the target's head, and the target is also [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded)\
    \ and unable to breathe while the darkmantle is attached in this way.\n\nWhile\
    \ attached to the target, the darkmantle can attack no other creature except the\
    \ target but has advantage on its attack rolls. The darkmantle's speed also becomes\
    \ 0, it can't benefit from any bonus to its speed, and it moves with the target.\n\
    \nA creature can detach the darkmantle by making a successful DC 11 Strength check\
    \ as an action. On its turn, the darkmantle can detach itself from the target\
    \ by using 5 feet of movement."
  "name": "Crush"
- "desc": "A 15-foot radius of magical darkness extends out from the darkmantle, moves\
    \ with it, and spreads around corners. The darkness lasts as long as the darkmantle\
    \ maintains [concentration](/2-Mechanics/CLI/rules/conditions.md#concentration),\
    \ up to 10 minutes (as if concentrating on a spell). Darkvision can't penetrate\
    \ this darkness, and no natural light can illuminate it. If any of the darkness\
    \ overlaps with an area of light created by a spell of 2nd level or lower, the\
    \ spell creating the light is dispelled."
  "name": "Darkness Aura (1/Day)"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Reduced-Threat%20Darkmantle.webp"
```
^statblock

```encounter-table
name: Reduced-Threat Darkmantle
creatures:
 - 1: Reduced-Threat Darkmantle
```