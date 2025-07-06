---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mm
- monster/cr/1-8
- monster/environment/coastal
- monster/environment/desert
- monster/environment/forest
- monster/environment/grassland
- monster/environment/hill
- monster/environment/mountain
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Guard"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Monster Manual p. 347, Curse of Strahd, Hoard of the Dragon Queen, Princes of the Apocalypse, The Rise of Tiamat, Storm King's Thunder, Tomb of Annihilation, Waterdeep: Dragon Heist, Ghosts of Saltmarsh, Baldur's Gate: Descent Into Avernus, Mythic Odysseys of Theros, Candlekeep Mysteries, Journeys through the Radiant Citadel, Dragonlance: Shadow of the Dragon Queen, Keys from the Golden Vault. Available in the SRD and the Basic Rules.
---
# [Guard](2-Mechanics\CLI\bestiary\humanoid/guard.md)
*Source: Monster Manual p. 347, Curse of Strahd, Hoard of the Dragon Queen, Princes of the Apocalypse, The Rise of Tiamat, Storm King's Thunder, Tomb of Annihilation, Waterdeep: Dragon Heist, Ghosts of Saltmarsh, Baldur's Gate: Descent Into Avernus, Mythic Odysseys of Theros, Candlekeep Mysteries, Journeys through the Radiant Citadel, Dragonlance: Shadow of the Dragon Queen, Keys from the Golden Vault. Available in the SRD and the Basic Rules.*  

Guards include members of a city watch, sentries in a citadel or fortified town, and the bodyguards of merchants and nobles.

```statblock
"name": "Guard"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[chain shirt](/2-Mechanics/CLI/items/chain-shirt.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "13"
- !!int "12"
- !!int "12"
- !!int "10"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "any one language (usually Common)"
"cr": "1/8"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d6 + 1) piercing damage, or 5 (1d8 + 1) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Spear"
"source":
- "MM"
- "CoS"
- "HotDQ"
- "PotA"
- "RoT"
- "SKT"
- "ToA"
- "WDH"
- "GoS"
- "DC"
- "DIP"
- "SLW"
- "BGDIA"
- "ERLW"
- "EGW"
- "MOT"
- "CM"
- "CRCotN"
- "JttRC"
- "LoX"
- "DSotDQ"
- "KftGV"
- "AATM"
- "SatO"
- "ToFW"
- "DoDk"
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Guard.webp"
```
^statblock

```encounter-table
name: Guard
creatures:
 - 1: Guard
```

## Environment

coastal, mountain, grassland, hill, urban, forest, desert