---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/water-genasi
aliases: ["Shoalar Quanderil"]
NoteIcon: monster
BestiaryType: humanoid (Water genasi)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 208
---
# [Shoalar Quanderil](2-Mechanics\CLI\bestiary\npc/shoalar-quanderil-pota.md)
*Source: Princes of the Apocalypse p. 208*  

A plump water genasi armed with a jovial manner and biting sense of humor, Shoalar Quanderil seems like the last person one would expect to be a cruel member of a destructive cult. Nevertheless, Shoalar is the captain of a pirate ship that harries the Sword Coast, and a high-ranking Crushing Wave cultist. He sees Olhydra's power as a means to making himself as rich as possible.

```statblock
"name": "Shoalar Quanderil (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "Water genasi"
"alignment": "Lawful Evil"
"ac": !!int "10"
"ac_class": "13 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "60"
"hit_dice": "8d8 + 24"
"stats":
- !!int "11"
- !!int "12"
- !!int "16"
- !!int "14"
- !!int "10"
- !!int "17"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Insight": !!int "2"
  "Arcana": !!int "4"
  "Persuasion": !!int "5"
"damage_resistances": "acid"
"senses": "passive Perception 10"
"languages": "Aquan, Common"
"cr": "4"
"traits":
- "desc": "Shoalar's innate spellcasting ability is Constitution (spell save DC 13,\
    \ +5 to hit with spell attacks). He can innately cast the following spells:\n\
    \nAt will: [shape water](/2-Mechanics/CLI/spells/shape-water-xge.md)\n\n1/day:\
    \ [create or destroy water](/2-Mechanics/CLI/spells/create-or-destroy-water.md)"
  "name": "Innate Spellcasting"
- "desc": "Shoalar is a 5th-level spellcaster. His spellcasting ability is Charisma\
    \ (spell save DC 13, +5 to hit with spell attacks). He knows the following sorcerer\
    \ spells:\n\nCantrips (at will): [acid splash](/2-Mechanics/CLI/spells/acid-splash.md),\
    \ [chill touch](/2-Mechanics/CLI/spells/chill-touch.md), [friends](/2-Mechanics/CLI/spells/friends.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md), [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md)\n\
    \n1st level (4 slots): [disguise self](/2-Mechanics/CLI/spells/disguise-self.md),\
    \ [mage armor](/2-Mechanics/CLI/spells/mage-armor.md), [magic missile](/2-Mechanics/CLI/spells/magic-missile.md)\n\
    \n2nd level (3 slots): [hold person](/2-Mechanics/CLI/spells/hold-person.md),\
    \ [misty step](/2-Mechanics/CLI/spells/misty-step.md)\n\n3rd level (2 slots):\
    \ [tidal wave](/2-Mechanics/CLI/spells/tidal-wave-xge.md)"
  "name": "Spellcasting"
- "desc": "Shoalar can breathe air and water."
  "name": "Amphibious"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or ranged 20/60\
    \ ft., one target. Hit: 3 (1d4 + 1) piercing damage."
  "name": "Dagger"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Shoalar%20Quanderil.webp"
```
^statblock

```encounter-table
name: Shoalar Quanderil
creatures:
 - 1: Shoalar Quanderil
```