---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Feathergale Knight"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 189
---
# [Feathergale Knight](2-Mechanics\CLI\bestiary\humanoid/feathergale-knight-pota.md)
*Source: Princes of the Apocalypse p. 189*  

The Feathergale Knights are ambitious, wealthy folk from cities such as Waterdeep seduced by the air cult's promises of power. From the backs of hippogriffs or giant vultures, they survey the land around Feathergale Spire, guarding the entrance to the air cult's hidden temple.

The knights are contemptuous of other elemental cultists, whom they view as depraved lunatics. Under lord commander Thurl Merosska, the Feathergale Knights see themselves as elite men and women who can make hard choices for the good of their realms. In reality, they are bound to Yan-C-Bin and are blind to their own corruption and decadence. Despite their refined manners and social sophistication, each has sealed that pact with the murder of a sentient being-deaths the knights have dubbed necessary for the security of the realm.

The knights have access to wingwear, as described in the "Elemental Magic Items" section. They are often wearing it when encountered.

```statblock
"name": "Feathergale Knight (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "[scale mail](/2-Mechanics/CLI/items/scale-mail.md)"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "14"
- !!int "14"
- !!int "12"
- !!int "11"
- !!int "10"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Animal Handling": !!int "2"
  "History": !!int "2"
"senses": "passive Perception 10"
"languages": "Auran, Common"
"cr": "1"
"traits":
- "desc": "The knight is a 1st-level spellcaster. Its spellcasting ability is Charisma\
    \ (spell save DC 12, +4 to hit with spell attacks). It knows the following sorcerer\
    \ spell:\n\nCantrips (at will): [gust](/2-Mechanics/CLI/spells/gust-xge.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md), [message](/2-Mechanics/CLI/spells/message.md),\
    \ [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md)\n\n1st level (2 slots):\
    \ [expeditious retreat](/2-Mechanics/CLI/spells/expeditious-retreat.md), [feather\
    \ fall](/2-Mechanics/CLI/spells/feather-fall.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The knight makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with two hands."
  "name": "Longsword"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Spear"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Feathergale%20Knight.webp"
```
^statblock

```encounter-table
name: Feathergale Knight
creatures:
 - 1: Feathergale Knight
```