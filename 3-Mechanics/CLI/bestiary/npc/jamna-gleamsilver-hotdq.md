---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/hotdq
- monster/cr/1
- monster/size/small
- monster/type/humanoid/gnome
aliases: ["Jamna Gleamsilver"]
NoteIcon: monster
BestiaryType: humanoid (gnome)
SourceType: Bestiary
BookSource: Hoard of the Dragon Queen p. 91
---
# [Jamna Gleamsilver](2-Mechanics\CLI\bestiary\npc/jamna-gleamsilver-hotdq.md)
*Source: Hoard of the Dragon Queen p. 91*  

```statblock
"name": "Jamna Gleamsilver (HotDQ)"
"size": "Small"
"type": "humanoid"
"subtype": "gnome"
"alignment": "Neutral"
"ac": !!int "15"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "22"
"hit_dice": "4d6 + 8"
"stats":
- !!int "8"
- !!int "17"
- !!int "14"
- !!int "15"
- !!int "10"
- !!int "12"
"speed": "25 ft."
"saves":
  "Dexterity": !!int "5"
  "Intelligence": !!int "4"
"skillsaves":
  "Deception": !!int "3"
  "Stealth": !!int "7"
  "Insight": !!int "2"
  "Perception": !!int "4"
  "Acrobatics": !!int "5"
  "Persuasion": !!int "3"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Gnomish, Goblin, Sylvan"
"cr": "1"
"traits":
- "desc": "Jamna is a 4th-level spellcaster that uses Intelligence as her spellcasting\
    \ ability (spell save DC 12, +4 to hit with spell attacks). Jamna has the following\
    \ spells prepared from the wizard spell list.\n\nCantrips (at will): [mage\
    \ hand](/2-Mechanics/CLI/spells/mage-hand.md), [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md), [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md)\n\
    \n1st level (3 slots): [charm person](/2-Mechanics/CLI/spells/charm-person.md),\
    \ [color spray](/2-Mechanics/CLI/spells/color-spray.md), [disguise self](/2-Mechanics/CLI/spells/disguise-self.md),\
    \ [longstrider](/2-Mechanics/CLI/spells/longstrider.md)"
  "name": "Spellcasting"
- "desc": "Jamna can take a bonus action to take the Dash, Disengage, or Hide action."
  "name": "Cunning Action"
- "desc": "Jamna has advantage on Intelligence, Wisdom and Charisma saving throws\
    \ against magic."
  "name": "Gnome Cunning"
"actions":
- "desc": "Jamna attacks twice with her shortswords."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage, or 9 (1d6 + 3) plus (1d6) piercing damage if the\
    \ target is Medium or larger."
  "name": "Shortsword"
"source":
- "HotDQ"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/HotDQ/Jamna%20Gleamsilver.webp"
```
^statblock

```encounter-table
name: Jamna Gleamsilver
creatures:
 - 1: Jamna Gleamsilver
```