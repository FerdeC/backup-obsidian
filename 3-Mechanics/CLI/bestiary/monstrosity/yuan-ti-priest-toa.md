---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/3
- monster/size/medium
- monster/type/monstrosity/shapechanger
- monster/type/monstrosity/yuan-ti
aliases: ["Yuan-ti Priest"]
NoteIcon: monster
BestiaryType: monstrosity (shapechanger, yuan-ti)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 118
---
# [Yuan-ti Priest](2-Mechanics\CLI\bestiary\monstrosity/yuan-ti-priest-toa.md)
*Source: Tomb of Annihilation p. 118*  

```statblock
"name": "Yuan-ti Priest (ToA)"
"size": "Medium"
"type": "monstrosity"
"subtype": "shapechanger, yuan-ti"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"stats":
- !!int "16"
- !!int "14"
- !!int "13"
- !!int "14"
- !!int "12"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Stealth": !!int "4"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Abyssal, Common, Draconic"
"cr": "3"
"traits":
- "desc": "The yuan-ti's innate spellcasting ability is Charisma (spell save DC 13,\
    \ +5 to hit with spell attacks). The yuan-ti can innately cast the following\
    \ spells, requiring no material components:\n\nAt will: [animal friendship](/2-Mechanics/CLI/spells/animal-friendship.md)\
    \ (snakes only), [eldritch blast](/2-Mechanics/CLI/spells/eldritch-blast.md) (2\
    \ beams), [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md), [poison\
    \ spray](/2-Mechanics/CLI/spells/poison-spray.md)\n\n3/day: [suggestion](/2-Mechanics/CLI/spells/suggestion.md)"
  "name": "Innate Spellcasting (Yuan-ti Form Only)"
- "desc": "The yuan-ti can use its action to polymorph into a Medium snake, or back\
    \ into its true form. Its statistics are the same in each form. Any equipment\
    \ it is wearing or carrying isn't transformed. It doesn't change form if it dies."
  "name": "Shapechanger"
- "desc": "The yuan-ti has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The yuan-ti has one of the following types:\n\n- Type 1. Human body\
    \ with snake head  \n- Type 2. Human head and body with snakes for arms  \n\
    - Type 3. Human head and upper body with a serpentine lower body instead of\
    \ legs  "
  "name": "Malison Type"
"actions":
- "desc": "The yuan-ti makes two ranged attacks or two melee attacks, but can constrict\
    \ only once."
  "name": "Multiattack (Yuan-ti Form Only)"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 5\
    \ (1d4 + 3) piercing damage plus 7 (2d6) poison damage."
  "name": "Bite (Snake Form Only)"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) bludgeoning damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 13). Until this grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and the yuan-ti can't constrict another target."
  "name": "Constrict"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Scimitar (Yuan-ti Form Only)"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Yuan-ti%20Priest.webp"
```
^statblock

```encounter-table
name: Yuan-ti Priest
creatures:
 - 1: Yuan-ti Priest
```