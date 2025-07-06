---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/goliath
aliases: ["Goliath Warrior"]
NoteIcon: monster
BestiaryType: humanoid (goliath)
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 292
---
# [Goliath Warrior](2-Mechanics\CLI\bestiary\humanoid/goliath-warrior-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 292*  

Goliaths inhabit the Spine of the World, where their mettle is tested against orcs, ogres, frost giants, remorhazes, ice trolls, young white dragons, the treacherous mountain terrain, and the cruel indifference of nature.

```statblock
"name": "Goliath Warrior (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "goliath"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"stats":
- !!int "18"
- !!int "11"
- !!int "16"
- !!int "10"
- !!int "15"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "6"
  "Perception": !!int "4"
  "Survival": !!int "4"
"damage_resistances": "cold"
"senses": "passive Perception 14"
"languages": "Common, Giant"
"cr": "3"
"traits":
- "desc": "The goliath is acclimated to high altitude, including elevations above\
    \ 20,000 feet."
  "name": "Mountain Born"
- "desc": "The goliath counts as one size larger when determining its carrying capacity\
    \ and the weight it can push, drag, or lift."
  "name": "Powerful Build"
"actions":
- "desc": "The goliath makes two attacks with its greataxe or hurls two javelins."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
    \ (1d12 + 4) slashing damage."
  "name": "Greataxe"
- "desc": "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 7 (1d6 + 4) piercing damage."
  "name": "Javelin"
"reactions":
- "desc": "When the goliath takes damage, it reduces the damage taken by 9 (1d12\
    \ + 3)."
  "name": "Stone's Endurance (Recharges after a Short or Long Rest)"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Goliath%20Warrior.webp"
```
^statblock

```encounter-table
name: Goliath Warrior
creatures:
 - 1: Goliath Warrior
```