---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/3
- monster/size/medium
- monster/type/fiend/demon
aliases: ["Nahual"]
NoteIcon: monster
BestiaryType: fiend (demon)
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 91
---
# [Nahual](2-Mechanics\CLI\bestiary\npc/nahual-tftyp.md)
*Source: Tales from the Yawning Portal p. 91*  

```statblock
"name": "Nahual (TftYP)"
"size": "Medium"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "11"
- !!int "18"
- !!int "14"
- !!int "11"
- !!int "12"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "6"
  "Insight": !!int "3"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common"
"cr": "3"
"traits":
- "desc": "The doppelganger can use its action to polymorph into a Small or Medium\
    \ humanoid it has seen, or back into its true form. Its statistics, other than\
    \ its size, are the same in each form. Any equipment it is wearing or carrying\
    \ isn't transformed. It reverts to its true form if it dies."
  "name": "Shapechanger"
- "desc": "In the first round of a combat, the doppelganger has advantage on attack\
    \ rolls against any creature it has [surprised](/2-Mechanics/CLI/rules/conditions.md#surprised)."
  "name": "Ambusher"
- "desc": "If the doppelganger surprises a creature and hits it with an attack during\
    \ the first round of combat, the target takes an extra 10 (3d6) damage from\
    \ the attack."
  "name": "Surprise Attack"
"actions":
- "desc": "The doppelganger makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) bludgeoning damage."
  "name": "Slam"
- "desc": "The doppelganger magically reads the surface thoughts of one creature within\
    \ 60 feet of it. The effect can penetrate barriers, but 3 feet of wood or dirt,\
    \ 2 feet of stone, 2 inches of metal, or a thin sheet of lead blocks it. While\
    \ the target is in range, the doppelganger can continue reading its thoughts,\
    \ as long as the doppelganger's [concentration](/2-Mechanics/CLI/rules/conditions.md#concentration)\
    \ isn't broken (as if concentrating on a spell). While reading the target's mind,\
    \ the doppelganger has advantage on Wisdom ([Insight](/2-Mechanics/CLI/rules/skills.md#Insight))\
    \ and Charisma ([Deception](/2-Mechanics/CLI/rules/skills.md#Deception), [Intimidation](/2-Mechanics/CLI/rules/skills.md#Intimidation),\
    \ and [Persuasion](/2-Mechanics/CLI/rules/skills.md#Persuasion)) checks against\
    \ the target."
  "name": "Read Thoughts"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Nahual.webp"
```
^statblock

```encounter-table
name: Nahual
creatures:
 - 1: Nahual
```