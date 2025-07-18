---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/0
- monster/size/medium
- monster/type/beast
aliases: ["Kingsport"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 243
---
# [Kingsport](2-Mechanics\CLI\bestiary\npc/kingsport-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 243*  

Scrivenscry is an arcanaloth who always refers to itself in the third person. It has a fondness for black licorice, strips of which it keeps in the pockets of its robe. The fiend is attended by Kingsport, a blind, albino giant penguin under the effect of an [awaken](/2-Mechanics/CLI/spells/awaken.md) spell.

Scrivenscry's anxious penguin servant, Kingsport, was promised a life of enlightenment. The truth is that Kingsport was turned into Scrivenscry's lackey, who lives in fear of his cruel, unpredictable master. The blind giant penguin hopes to be free of the arcanaloth one day.

```statblock
"name": "Kingsport (IDRotF)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "5"
"hit_dice": "1d8 + 1"
"stats":
- !!int "6"
- !!int "12"
- !!int "12"
- !!int "10"
- !!int "10"
- !!int "4"
"speed": "20 ft., swim 40 ft."
"senses": "blindsight 30 ft. (blind beyond this radius), passive Perception 10"
"languages": "Common"
"cr": "0"
"traits":
- "desc": "Kingsport can hold its breath for 20 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d4\
    \ + 1) piercing damage."
  "name": "Beak"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Kingsport.webp"
```
^statblock

```encounter-table
name: Kingsport
creatures:
 - 1: Kingsport
```