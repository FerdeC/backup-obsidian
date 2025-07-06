---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/hotdq
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/high-elf
aliases: ["Dralmorrer Borngray"]
NoteIcon: monster
BestiaryType: humanoid (High elf)
SourceType: Bestiary
BookSource: Hoard of the Dragon Queen p. 90
---
# [Dralmorrer Borngray](2-Mechanics\CLI\bestiary\npc/dralmorrer-borngray-hotdq.md)
*Source: Hoard of the Dragon Queen p. 90*  

```statblock
"name": "Dralmorrer Borngray (HotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "High elf"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "52"
"hit_dice": "7d10 + 14"
"stats":
- !!int "18"
- !!int "14"
- !!int "14"
- !!int "16"
- !!int "10"
- !!int "8"
"speed": "30 ft."
"saves":
  "Strength": !!int "6"
  "Constitution": !!int "4"
"skillsaves":
  "Deception": !!int "1"
  "Religion": !!int "5"
  "Insight": !!int "2"
  "Perception": !!int "2"
  "Arcana": !!int "5"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Bullywug, Draconic, Elvish, Goblin, Sylvan"
"cr": "3"
"traits":
- "desc": "Dralmorrer is a 7th-level spellcaster that uses Intelligence as his spellcasting\
    \ ability (spell save DC 13, +5 to hit with spell attacks). Dralmorrer has the\
    \ following spells prepared from the wizard spell list:\n\nCantrips (at will):\
    \ [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md),\
    \ [shocking grasp](/2-Mechanics/CLI/spells/shocking-grasp.md)\n\n1st level (4\
    \ slots): [longstrider](/2-Mechanics/CLI/spells/longstrider.md), [magic missile](/2-Mechanics/CLI/spells/magic-missile.md),\
    \ [shield](/2-Mechanics/CLI/spells/shield.md), [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md)\n\
    \n2nd level (2 slots): [magic weapon](/2-Mechanics/CLI/spells/magic-weapon.md),\
    \ [misty step](/2-Mechanics/CLI/spells/misty-step.md)"
  "name": "Spellcasting"
- "desc": "Dralmorrer has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put him to sleep."
  "name": "Fey Ancestry"
- "desc": "When Dralmorrer uses his action to cast a cantrip, he can also take a bonus\
    \ action to make one weapon attack."
  "name": "War Magic"
- "desc": "Provided his longsword is on the same plane Dralmorrer can take a bonus\
    \ action to teleport it to his hand."
  "name": "Weapon Bond"
"actions":
- "desc": "Dralmorrer attacks twice, either with his longsword or dagger."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) slashing damage."
  "name": "Longsword"
- "desc": "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or ranged 20/60\
    \ ft., one target. Hit: 6 (1d4 + 4) piercing damage."
  "name": "Dagger"
"source":
- "HotDQ"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/HotDQ/Dralmorrer%20Borngray.webp"
```
^statblock

```encounter-table
name: Dralmorrer Borngray
creatures:
 - 1: Dralmorrer Borngray
```