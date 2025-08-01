---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/2
- monster/size/medium
- monster/type/construct
aliases: ["Demos Magen"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 300
---
# [Demos Magen](2-Mechanics\CLI\bestiary\construct/demos-magen-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 300*  

Demos magen wear armor, wield weapons, and typically serve as guards.

Magen are magical, humanlike beings created by a wizard spell (see the [create magen](/2-Mechanics/CLI/spells/create-magen-idrotf.md) spell in appendix D) or by other arcane methods.

Though magen look like humanoids with green skin, they are constructs. When one is wounded, its blood is seen to have the color and consistency of mercury. They exist purely through magical means. When one is killed, its body disappears in a burst of harmless fire and a cloud of smoke that quickly dissipates.

```statblock
"name": "Demos Magen (IDRotF)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "[chain mail](/2-Mechanics/CLI/items/chain-mail.md)"
"hp": !!int "51"
"hit_dice": "6d8 + 24"
"stats":
- !!int "14"
- !!int "14"
- !!int "18"
- !!int "10"
- !!int "10"
- !!int "7"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/2-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/2-Mechanics/CLI/rules/conditions.md#paralyzed), [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "2"
"traits":
- "desc": "If the magen dies, its body disintegrates in a harmless burst of fire and\
    \ smoke, leaving behind anything it was wearing or carrying."
  "name": "Fiery End"
- "desc": "The magen has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The magen doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The magen makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 9 (2d6\
    \ + 2) slashing damage."
  "name": "Greatsword"
- "desc": "Ranged Weapon Attack: +4 to hit, range 80/320 ft., one target. Hit:\
    \ 6 (1d8 + 2) piercing damage."
  "name": "Light Crossbow"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Demos%20Magen.webp"
```
^statblock

```encounter-table
name: Demos Magen
creatures:
 - 1: Demos Magen
```