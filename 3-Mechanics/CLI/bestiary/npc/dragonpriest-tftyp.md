---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/5
- monster/size/large
- monster/type/giant
aliases: ["Dragonpriest"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 16
---
# [Dragonpriest](2-Mechanics\CLI\bestiary\npc/dragonpriest-tftyp.md)
*Source: Tales from the Yawning Portal p. 16*  

```statblock
"name": "Dragonpriest (TftYP)"
"size": "Large"
"type": "giant"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "30"
"hit_dice": "8d10 + 40"
"stats":
- !!int "18"
- !!int "13"
- !!int "20"
- !!int "7"
- !!int "9"
- !!int "7"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Elvish, Draconic"
"cr": "5"
"traits":
- "desc": "The dragonpriest has advantage on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "The dragonpriest regains 5 hit points at the start of its turn. If the\
    \ dragonpriest takes acid or fire damage, this trait doesn't function at the start\
    \ of the dragonpriest's next turn. The dragonpriest dies only if it starts its\
    \ turn with 0 hit points and doesn't regenerate."
  "name": "Regeneration"
"actions":
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) slashing damage."
  "name": "Claw"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Dragonpriest.webp"
```
^statblock

```encounter-table
name: Dragonpriest
creatures:
 - 1: Dragonpriest
```