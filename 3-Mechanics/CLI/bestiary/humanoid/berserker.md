---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/2
- monster/environment/arctic
- monster/environment/coastal
- monster/environment/desert
- monster/environment/forest
- monster/environment/hill
- monster/environment/mountain
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Berserker"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Monster Manual p. 344, Curse of Strahd, Hoard of the Dragon Queen, Princes of the Apocalypse, Storm King's Thunder, Tomb of Annihilation, Waterdeep: Dungeon of the Mad Mage, Ghosts of Saltmarsh, Mythic Odysseys of Theros, Icewind Dale: Rime of the Frostmaiden, Candlekeep Mysteries. Available in the SRD and the Basic Rules.
---
# [Berserker](2-Mechanics\CLI\bestiary\humanoid/berserker.md)
*Source: Monster Manual p. 344, Curse of Strahd, Hoard of the Dragon Queen, Princes of the Apocalypse, Storm King's Thunder, Tomb of Annihilation, Waterdeep: Dungeon of the Mad Mage, Ghosts of Saltmarsh, Mythic Odysseys of Theros, Icewind Dale: Rime of the Frostmaiden, Candlekeep Mysteries. Available in the SRD and the Basic Rules.*  

Hailing from uncivilized lands, unpredictable berserkers come together in war parties and seek conflict wherever they can find it.

```statblock
"name": "Berserker"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Chaotic alignment"
"ac": !!int "13"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"stats":
- !!int "16"
- !!int "12"
- !!int "17"
- !!int "9"
- !!int "11"
- !!int "9"
"speed": "30 ft."
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "2"
"traits":
- "desc": "At the start of its turn, the berserker can gain advantage on all melee\
    \ weapon attack rolls during that turn, but attack rolls against it have advantage\
    \ until the start of its next turn."
  "name": "Reckless"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 9 (1d12\
    \ + 3) slashing damage."
  "name": "Greataxe"
"source":
- "MM"
- "CoS"
- "HotDQ"
- "PotA"
- "SKT"
- "ToA"
- "WDMM"
- "GoS"
- "DC"
- "DIP"
- "SLW"
- "EGW"
- "MOT"
- "IDRotF"
- "CM"
- "CRCotN"
- "PaBTSO"
- "ToFW"
- "BMT"
- "DoDk"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Berserker.webp"
```
^statblock

```encounter-table
name: Berserker
creatures:
 - 1: Berserker
```

## Environment

coastal, mountain, hill, arctic, forest, desert