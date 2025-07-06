---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Black Earth Guard"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 195
---
# [Black Earth Guard](2-Mechanics\CLI\bestiary\humanoid/black-earth-guard-pota.md)
*Source: Princes of the Apocalypse p. 195*  

Black Earth guards are the warriors of the earth cult. They are brutal, heavily armored thugs devoted to Ogrémoch. That devotion has granted them an uncanny ability to hold their ground against the buffeting assaults. It has also earned them the right to wear special plate armor of elemental stone, which breaks down when the guard is slain.

These guards are fanatically loyal to the Black Earth priests and the leaders of the cult. They fight to the death if commanded to do so by their superiors. Those with more potential become burrowsharks.

```statblock
"name": "Black Earth Guard (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "[plate armor](/2-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"stats":
- !!int "17"
- !!int "11"
- !!int "14"
- !!int "10"
- !!int "10"
- !!int "9"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "1"
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "2"
"actions":
- "desc": "The guard makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) piercing damage."
  "name": "Morningstar"
"reactions":
- "desc": "When the guard is subjected to an effect that would move it, knock it [prone](/2-Mechanics/CLI/rules/conditions.md#prone),\
    \ or both, it can use its reaction to be neither moved nor knocked [prone](/2-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Unyielding"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Black%20Earth%20Guard.webp"
```
^statblock

```encounter-table
name: Black Earth Guard
creatures:
 - 1: Black Earth Guard
```