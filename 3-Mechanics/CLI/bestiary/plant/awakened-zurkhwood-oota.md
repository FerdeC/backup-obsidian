---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/oota
- monster/cr/2
- monster/size/huge
- monster/type/plant
aliases: ["Awakened Zurkhwood"]
NoteIcon: monster
BestiaryType: plant
SourceType: Bestiary
BookSource: Out of the Abyss p. 230
---
# [Awakened Zurkhwood](2-Mechanics\CLI\bestiary\plant/awakened-zurkhwood-oota.md)
*Source: Out of the Abyss p. 230*  

This creature is an ordinary zurkhwood mushroom (see "Fungi of the Underdark" in chapter 2) given sentience and mobility. An awakened zurkhwood can be created by casting the [awaken](/2-Mechanics/CLI/spells/awaken.md) spell on a normal zurkhwood mushroom. A myconid sovereign can create one by performing a lengthy ritual.

An awakened zurkhwood has the same statistics as an awakened tree (see appendix A of the Monster Manual), with the following modifications:

- The awakened zurkhwood has [darkvision](/2-Mechanics/CLI/rules/senses.md#darkvision) out to a range of 120 feet.  
- If the awakened zurkhwood was created by a myconid sovereign, it can't speak.  
- The awakened zurkhwood's False Appearance feature allows it to be mistaken for a normal zurkhwood mushroom (instead of a tree).  

```statblock
"name": "Awakened Zurkhwood (OotA)"
"size": "Huge"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "59"
"hit_dice": "7d12 + 14"
"stats":
- !!int "19"
- !!int "6"
- !!int "15"
- !!int "10"
- !!int "10"
- !!int "7"
"speed": "20 ft."
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "one language known by its creator"
"cr": "2"
"traits":
- "desc": "While the tree remains motionless, it is indistinguishable from a normal\
    \ zurkhwood mushroom."
  "name": "False Appearance"
- "desc": "If the awakened zurkhwood was created by a myconid sovereign, it can't\
    \ speak."
  "name": "Mute"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 14\
    \ (3d6 + 4) bludgeoning damage."
  "name": "Slam"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/OotA/Awakened%20Zurkhwood.webp"
```
^statblock

```encounter-table
name: Awakened Zurkhwood
creatures:
 - 1: Awakened Zurkhwood
```