---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/0
- monster/environment/grassland
- monster/environment/hill
- monster/environment/mountain
- monster/environment/urban
- monster/size/medium
- monster/type/beast
aliases: ["Goat"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 330, Curse of Strahd, Princes of the Apocalypse, The Rise of Tiamat, Storm King's Thunder, Tomb of Annihilation, Waterdeep: Dungeon of the Mad Mage, Ghosts of Saltmarsh, Baldur's Gate: Descent Into Avernus, Icewind Dale: Rime of the Frostmaiden, The Wild Beyond the Witchlight. Available in the SRD and the Basic Rules.
---
# [Goat](2-Mechanics\CLI\bestiary\beast/goat.md)
*Source: Monster Manual p. 330, Curse of Strahd, Princes of the Apocalypse, The Rise of Tiamat, Storm King's Thunder, Tomb of Annihilation, Waterdeep: Dungeon of the Mad Mage, Ghosts of Saltmarsh, Baldur's Gate: Descent Into Avernus, Icewind Dale: Rime of the Frostmaiden, The Wild Beyond the Witchlight. Available in the SRD and the Basic Rules.*  

```statblock
"name": "Goat"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "4"
"hit_dice": "1d8"
"stats":
- !!int "12"
- !!int "10"
- !!int "11"
- !!int "2"
- !!int "10"
- !!int "5"
"speed": "40 ft."
"senses": "passive Perception 10"
"languages": ""
"cr": "0"
"traits":
- "desc": "If the goat moves at least 20 feet straight toward a target and then hits\
    \ it with a ram attack on the same turn, the target takes an extra 2 (1d4) bludgeoning\
    \ damage. If the target is a creature, it must succeed on a DC 10 Strength saving\
    \ throw or be knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Charge"
- "desc": "The goat has advantage on Strength and Dexterity saving throws made against\
    \ effects that would knock it [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Sure-Footed"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d4\
    \ + 1) bludgeoning damage."
  "name": "Ram"
"source":
- "MM"
- "CoS"
- "PotA"
- "RoT"
- "SKT"
- "ToA"
- "WDMM"
- "GoS"
- "BGDIA"
- "IDRotF"
- "WBtW"
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Goat.webp"
```
^statblock

```encounter-table
name: Goat
creatures:
 - 1: Goat
```

## Environment

mountain, grassland, hill, urban