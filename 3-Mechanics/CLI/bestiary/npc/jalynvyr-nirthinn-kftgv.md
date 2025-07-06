---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/kftgv
- monster/cr/1-4
- monster/size/small
- monster/type/elemental
aliases: ["Jalynvyr Nir'Thinn"]
NoteIcon: monster
BestiaryType: elemental
SourceType: Bestiary
BookSource: Keys from the Golden Vault p. 155
---
# [Jalynvyr Nir'Thinn](2-Mechanics\CLI\bestiary\npc/jalynvyr-nirthinn-kftgv.md)
*Source: Keys from the Golden Vault p. 155*  

```statblock
"name": "Jalynvyr Nir'Thinn (KftGV)"
"size": "Small"
"type": "elemental"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "5d6 + 5"
"stats":
- !!int "6"
- !!int "14"
- !!int "12"
- !!int "10"
- !!int "10"
- !!int "11"
"speed": "30 ft., fly 30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "2"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Elvish"
"cr": "1/4"
"traits":
- "desc": "Jalynvyr Nir'Thinn can innately cast [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md),\
    \ requiring no material components. Its innate spellcasting ability is Charisma.\n\
    \nAt will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md)"
  "name": "Innate Spellcasting (1/Day)"
- "desc": "When Jalynvyr Nir'Thinn dies, it leaves behind a cloud of smoke that fills\
    \ a 5-foot-radius sphere centered on its space. The sphere is heavily obscured.\
    \ Wind disperses the cloud, which otherwise lasts for 1 minute."
  "name": "Death Burst"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 4\
    \ (1d4 + 2) slashing damage."
  "name": "Claws"
- "desc": "Jalynvyr Nir'Thinn exhales a 15-foot cone of smoldering ash. Each creature\
    \ in that area must succeed on a DC 10 Dexterity saving throw or be [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded)\
    \ until the end of Jalynvyr Nir'Thinn's next turn."
  "name": "Cinder Breath (Recharge 6)"
"source":
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/KftGV/Jalynvyr%20Nir%27Thinn.webp"
```
^statblock

```encounter-table
name: Jalynvyr Nir'Thinn
creatures:
 - 1: Jalynvyr Nir'Thinn
```