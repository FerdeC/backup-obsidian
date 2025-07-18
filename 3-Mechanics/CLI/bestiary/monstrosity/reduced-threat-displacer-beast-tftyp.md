---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/3
- monster/size/large
- monster/type/monstrosity
aliases: ["Reduced-Threat Displacer Beast"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 113
---
# [Reduced-Threat Displacer Beast](2-Mechanics\CLI\bestiary\monstrosity/reduced-threat-displacer-beast-tftyp.md)
*Source: Tales from the Yawning Portal p. 113*  

```statblock
"name": "Reduced-Threat Displacer Beast (TftYP)"
"size": "Large"
"type": "monstrosity"
"alignment": "Lawful Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "42"
"hit_dice": "10d10 + 30"
"stats":
- !!int "18"
- !!int "15"
- !!int "16"
- !!int "6"
- !!int "12"
- !!int "8"
"speed": "40 ft."
"senses": "darkvision 60 ft., passive Perception 11"
"languages": ""
"cr": "3"
"traits":
- "desc": "A reduced-threat monster takes a −2 penalty on attack rolls (included in\
    \ the stat block), ability checks (included in the stat block for skill proficiencies),\
    \ saving throws (included in the stat block for saving throw proficiencies), and\
    \ saving throw DCs (included in the stat block)."
  "name": "Reduced Threat"
- "desc": "If the displacer beast is subjected to an effect that allows it to make\
    \ a saving throw to take only half damage, it instead takes no damage if it succeeds\
    \ on the saving throw, and only half damage if it fails."
  "name": "Avoidance"
- "desc": "The displacer beast projects a magical illusion that makes it appear to\
    \ be standing near its actual location, causing attack rolls against it to have\
    \ disadvantage. If it is hit by an attack, this trait is disrupted until the end\
    \ of its next turn. This trait is also disrupted while the displacer beast is\
    \ [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated) or has a\
    \ speed of 0."
  "name": "Displacement"
"actions":
- "desc": "The displacer beast makes two attacks with its tentacles."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 10 ft., one target. Hit: 7\
    \ (1d6 + 4) bludgeoning damage plus 3 (1d6) piercing damage."
  "name": "Tentacle"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Reduced-Threat%20Displacer%20Beast.webp"
```
^statblock

```encounter-table
name: Reduced-Threat Displacer Beast
creatures:
 - 1: Reduced-Threat Displacer Beast
```