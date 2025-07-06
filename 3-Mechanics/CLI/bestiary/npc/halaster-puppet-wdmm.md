---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wdmm
- monster/cr/
- monster/size/medium
- monster/type/construct
aliases: ["Halaster Puppet"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Waterdeep: Dungeon of the Mad Mage p. 31
---
# [Halaster Puppet](2-Mechanics\CLI\bestiary\npc/halaster-puppet-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 31*  

```statblock
"name": "Halaster Puppet (WDMM)"
"size": "Medium"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "10"
"hp": !!int "8"
"stats":
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
"speed": "20 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "[frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion)"
"senses": "passive Perception 10"
"languages": "Common"
"traits":
- "desc": "The puppet is destroyed if a successful [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md)\
    \ spell (DC 15) is cast on it"
  "name": "Antimagic Susceptibility"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WDMM/Halaster%20Puppet.webp"
```
^statblock

```encounter-table
name: Halaster Puppet
creatures:
 - 1: Halaster Puppet
```