---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/2
- monster/size/small
- monster/type/humanoid/grung
aliases: ["Yorb"]
NoteIcon: monster
BestiaryType: humanoid (grung)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 108
---
# [Yorb](2-Mechanics\CLI\bestiary\npc/yorb-toa.md)
*Source: Tomb of Annihilation p. 108*  

```statblock
"name": "Yorb (ToA)"
"size": "Small"
"type": "humanoid"
"subtype": "grung"
"alignment": "Lawful Evil"
"ac": !!int "13"
"hp": !!int "49"
"hit_dice": "9d6 + 18"
"stats":
- !!int "7"
- !!int "16"
- !!int "15"
- !!int "10"
- !!int "11"
- !!int "12"
"speed": "25 ft., climb 25 ft."
"saves":
  "Dexterity": !!int "5"
"skillsaves":
  "Athletics": !!int "2"
  "Stealth": !!int "5"
  "Perception": !!int "2"
  "Survival": !!int "2"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "passive Perception 12"
"languages": "Grung"
"cr": "2"
"traits":
- "desc": "Yorb can breathe air and water."
  "name": "Amphibious"
- "desc": "Any creature that grapples Yorb or otherwise comes into direct contact\
    \ with Yorb's skin must succeed on a DC 12 Constitution saving throw or become\
    \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned) for 1 minute. A [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ creature no longer in direct contact with Yorb can repeat the saving throw at\
    \ the end of each of its turns, ending the effect on itself on a success."
  "name": "Poisonous Skin"
- "desc": "Yorb's long jump is up to 25 feet and its high jump is up to 15 feet, with\
    \ or without a running start."
  "name": "Standing Leap"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage, and the target must succeed\
    \ on a DC 12 Constitution saving throw or take 5 (2d4) poison damage."
  "name": "Dagger"
- "desc": "Ranged Weapon Attack: +5 to hit, range 80/320 ft., one target. Hit:\
    \ 6 (1d6 + 3) piercing damage, and the target must succeed on a DC 12 Constitution\
    \ saving throw or take 5 (2d4) poison damage."
  "name": "Shortbow"
- "desc": "Yorb makes a chirring noise to which grungs are immune. Each humanoid or\
    \ beast that is within 15 feet of Yorb and able to hear it must succeed on a DC\
    \ 12 Wisdom saving throw or be [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned)\
    \ until the end of Yorb's next turn."
  "name": "Mesmerizing Chirr (Recharge 6)"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Yorb.webp"
```
^statblock

```encounter-table
name: Yorb
creatures:
 - 1: Yorb
```