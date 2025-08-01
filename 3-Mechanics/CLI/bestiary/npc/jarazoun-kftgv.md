---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/11
- monster/size/large
- monster/type/elemental
aliases: ["Jarazoun"]
NoteIcon: monster
BestiaryType: elemental
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 200
---
# [Jarazoun](2-Mechanics\CLI\bestiary\npc/jarazoun-kftgv.md)
*Source: Keys from the Golden Vault p. 200*  

```statblock
"name": "Jarazoun (KftGV)"
"size": "Large"
"type": "elemental"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "200"
"hit_dice": "16d10 + 112"
"stats":
- !!int "22"
- !!int "12"
- !!int "24"
- !!int "16"
- !!int "15"
- !!int "16"
"speed": "40 ft., fly 60 ft."
"saves":
  "Charisma": !!int "7"
  "Wisdom": !!int "6"
  "Intelligence": !!int "7"
"damage_immunities": "fire"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "Ignan"
"cr": "11"
"traits":
- "desc": "Jarazoun's innate spellcasting ability is Charisma (spell save DC 15, +7\
    \ to hit with spell attacks). It can innately cast the following spells, requiring\
    \ no material components:\n\nAt will: [detect magic](/2-Mechanics/CLI/spells/detect-magic.md)\n\
    \n1/day each: [conjure elemental](/2-Mechanics/CLI/spells/conjure-elemental.md)\
    \ ([fire elemental](/2-Mechanics/CLI/bestiary/elemental/fire-elemental.md) only),\
    \ [gaseous form](/2-Mechanics/CLI/spells/gaseous-form.md), [invisibility](/2-Mechanics/CLI/spells/invisibility.md),\
    \ [major image](/2-Mechanics/CLI/spells/major-image.md), [plane shift](/2-Mechanics/CLI/spells/plane-shift.md),\
    \ [wall of fire](/2-Mechanics/CLI/spells/wall-of-fire.md)\n\n3/day each: [enlarge/reduce](/2-Mechanics/CLI/spells/enlarge-reduce.md),\
    \ [tongues](/2-Mechanics/CLI/spells/tongues.md)"
  "name": "Innate Spellcasting"
- "desc": "If Jarazoun dies, its body disintegrates in a flash of fire and puff of\
    \ smoke, leaving behind only equipment Jarazoun was wearing or carrying."
  "name": "Elemental Demise"
"actions":
- "desc": "Jarazoun makes two scimitar attacks or uses its Hurl Flame twice."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d6 + 6) slashing damage plus 7 (2d6) fire damage."
  "name": "Scimitar"
- "desc": "Ranged Spell Attack: +7 to hit, range 120 ft., one target. Hit: 17\
    \ (5d6) fire damage."
  "name": "Hurl Flame"
"source":
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/KftGV/Jarazoun.webp"
```
^statblock

```encounter-table
name: Jarazoun
creatures:
 - 1: Jarazoun
```