---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Elizar Dryflagon"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 202
---
# [Elizar Dryflagon](2-Mechanics\CLI\bestiary\npc/elizar-dryflagon-pota.md)
*Source: Princes of the Apocalypse p. 202*  

Elizar was a druid who claims to be a member of the Circle of the Scarlet Moon. However, Elizar is really in service to Imix, maintaining some druidic power through a connection to the elements.

```statblock
"name": "Elizar Dryflagon (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "71"
"hit_dice": "11d8 + 22"
"stats":
- !!int "13"
- !!int "15"
- !!int "14"
- !!int "11"
- !!int "18"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "3"
  "Arcana": !!int "3"
"senses": "passive Perception 14"
"languages": "Common, Druidic"
"cr": "5"
"traits":
- "desc": "Elizar is a 7th-level spellcaster. His spellcasting ability is Wisdom (spell\
    \ save DC 15, +7 to hit with spell attacks). Elizar has the following druid\
    \ spells prepared:\n\nCantrips (at will): [druidcraft](/2-Mechanics/CLI/spells/druidcraft.md),\
    \ [guidance](/2-Mechanics/CLI/spells/guidance.md), [poison spray](/2-Mechanics/CLI/spells/poison-spray.md),\
    \ [produce flame](/2-Mechanics/CLI/spells/produce-flame.md)\n\n1st level (4\
    \ slots): [animal friendship](/2-Mechanics/CLI/spells/animal-friendship.md),\
    \ [faerie fire](/2-Mechanics/CLI/spells/faerie-fire.md), [healing word](/2-Mechanics/CLI/spells/healing-word.md),\
    \ [jump](/2-Mechanics/CLI/spells/jump.md), [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md)\n\
    \n2nd level (3 slots): [flame blade](/2-Mechanics/CLI/spells/flame-blade.md),\
    \ [spike growth](/2-Mechanics/CLI/spells/spike-growth.md)\n\n3rd level (3 slots):\
    \ [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), [stinking cloud](/2-Mechanics/CLI/spells/stinking-cloud.md)\n\
    \n4th level (2 slots): [blight](/2-Mechanics/CLI/spells/blight.md), [wall\
    \ of fire](/2-Mechanics/CLI/spells/wall-of-fire.md)"
  "name": "Spellcasting"
- "desc": "By puffing on his pipe, Elizar can use an action to cast [conjure minor\
    \ elementals](/2-Mechanics/CLI/spells/conjure-minor-elementals.md). If he does\
    \ so, he summons four smoke mephits."
  "name": "Summon Mephits (Recharges after a Long Rest)"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage."
  "name": "Dagger +1"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Elizar%20Dryflagon.webp"
```
^statblock

```encounter-table
name: Elizar Dryflagon
creatures:
 - 1: Elizar Dryflagon
```