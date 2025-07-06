---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/5
- monster/size/medium
- monster/type/undead
aliases: ["Coldlight Walker"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 284
---
# [Coldlight Walker](2-Mechanics\CLI\bestiary\undead/coldlight-walker-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 284*  

Some humanoids who died from extreme cold but whose spirits languish in the mortal world become coldlight walkers, burning with frigid fury at the meaninglessness of life. Their frostbitten corpses emit a spectral light so intense that mortal eyes can barely stand to look at them. They typically wear the clothing in which they died.

## God-Spawned Horrors

Gods that personify winter create coldlight walkers as embodiments of winter's wrath. These hateful spirits that were denied passage to the afterlife are preserved in their current forms to remind the living how fragile life can be.

When a coldlight walker dies, its light goes out, leaving behind a frozen, inanimate corpse that can never be raised from the dead.

```statblock
"name": "Coldlight Walker (IDRotF)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"stats":
- !!int "15"
- !!int "10"
- !!int "17"
- !!int "8"
- !!int "10"
- !!int "8"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "3"
  "Intelligence": !!int "2"
"damage_immunities": "cold"
"condition_immunities": "[blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/2-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "5"
"traits":
- "desc": "The walker sheds bright light in a 20-foot radius and dim light for an\
    \ additional 20 feet. As a bonus action, the walker can target one creature in\
    \ its bright light that it can see and force it to succeed on a DC 14 Constitution\
    \ saving throw or be [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded) until\
    \ the start of the walker's next turn."
  "name": "Blinding Light"
- "desc": "Any creature killed by the walker freezes for 9 days, during which time\
    \ it can't be thawed, harmed by fire, animated, or raised from the dead."
  "name": "Icy Doom"
- "desc": "The walker doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The walker makes two attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d8 + 2) bludgeoning damage plus 14 (4d6) cold damage."
  "name": "Slam"
- "desc": "Ranged Spell Attack: +3 to hit, range 60 ft., one target. Hit: 25\
    \ (4d10 + 3) cold damage."
  "name": "Cold Ray"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Coldlight%20Walker.webp"
```
^statblock

```encounter-table
name: Coldlight Walker
creatures:
 - 1: Coldlight Walker
```