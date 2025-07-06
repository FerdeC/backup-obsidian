---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/1-4
- monster/size/small
- monster/type/plant
aliases: ["Kupalué"]
NoteIcon: monster
BestiaryType: plant
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 35
---
# [Kupalué](2-Mechanics\CLI\bestiary\npc/kupalue-toa.md)
*Source: Tomb of Annihilation p. 35*  

```statblock
"name": "Kupalué (ToA)"
"size": "Small"
"type": "plant"
"alignment": "Neutral"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "9"
"hit_dice": "2d6 + 2"
"stats":
- !!int "7"
- !!int "14"
- !!int "13"
- !!int "6"
- !!int "11"
- !!int "7"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "2"
"damage_resistances": "lightning, piercing"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Vegepygmy"
"cr": "1/4"
"traits":
- "desc": "Kupalué has advantage on Dexterity ([Stealth](/2-Mechanics/CLI/rules/skills.md#Stealth))\
    \ checks it makes in any terrain with ample obscuring plant life."
  "name": "Plant Camouflage"
- "desc": "Kupalué regains 3 hit points at the start of its turn. If it takes cold,\
    \ fire, or necrotic damage, this trait doesn't function at the start of Kupalué\
    's next turn. Kupalué dies only if it starts its turn with 0 hit points and doesn't\
    \ regenerate."
  "name": "Regeneration"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) slashing damage."
  "name": "Claws"
- "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit:\
    \ 4 (1d4 + 2) bludgeoning damage."
  "name": "Sling"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Kupalue.webp"
```
^statblock

```encounter-table
name: Kupalué
creatures:
 - 1: Kupalué
```