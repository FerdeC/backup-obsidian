---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/4
- monster/environment/desert
- monster/environment/forest
- monster/environment/underdark
- monster/size/medium
- monster/type/monstrosity/warlock
aliases: ["Yuan-ti Mind Whisperer"]
NoteIcon: monster
BestiaryType: monstrosity (warlock)
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 274, Volo's Guide to Monsters p. 204
---
# [Yuan-ti Mind Whisperer](2-Mechanics\CLI\bestiary\monstrosity/yuan-ti-mind-whisperer-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 274, Volo's Guide to Monsters p. 204*  

Mind whisperers are yuan-ti malison spellcasters who enter into a pact with the serpent god Sseth, the Sibilant Death. They use their abilities to convert others to their faith, increase their personal power, and befuddle the minds of their enemies.

Mind whisperers are elusive, manipulative, unpredictable, and willing to cheat or kill comrades and rivals alike if doing so benefits them. The worshipers of Sseth have their hands in many schemes, often plying the middle ground between two factions, and thus spend a lot of energy making sure none of their allies learn of their conflicting connections. Even among Sseth-worshiping communities, mind whisperers are known for being self-important, sneaky, and prone to flee at the first sign of trouble.

```statblock
"name": "Yuan-ti Mind Whisperer (MPMM)"
"size": "Medium"
"type": "monstrosity"
"subtype": "warlock"
"alignment": "Typically  Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "71"
"hit_dice": "13d8 + 13"
"stats":
- !!int "16"
- !!int "14"
- !!int "13"
- !!int "14"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Wisdom": !!int "4"
"skillsaves":
  "Deception": !!int "5"
  "Stealth": !!int "4"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "Abyssal, Common, Draconic"
"cr": "4"
"traits":
- "desc": "The yuan-ti casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 13):\n\nAt will:\
    \ [animal friendship](/2-Mechanics/CLI/spells/animal-friendship.md) (snakes only),\
    \ [message](/2-Mechanics/CLI/spells/message.md), [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\n2/day each:\
    \ [detect thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md), [hypnotic pattern](/2-Mechanics/CLI/spells/hypnotic-pattern.md)\n\
    \n3/day: [suggestion](/2-Mechanics/CLI/spells/suggestion.md)"
  "name": "Spellcasting (Yuan-ti Form Only)"
- "desc": "Magical darkness doesn't impede the yuan-ti's [darkvision](/2-Mechanics/CLI/rules/senses.md#darkvision)."
  "name": "Devil's Sight"
- "desc": "The yuan-ti has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "When the yuan-ti reduces an enemy to 0 hit points, the yuan-ti gains 9\
    \ temporary hit points."
  "name": "Sseth's Blessing"
"actions":
- "desc": "The yuan-ti makes two Bite attacks and one Scimitar attack, or it makes\
    \ two Spectral Fangs attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
    \ + 3) piercing damage plus 7 (2d6) poison damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Scimitar (Yuan-ti Form Only)"
- "desc": "Ranged Spell Attack: +5 to hit, range 120 ft., one target. Hit: 16\
    \ (3d8 + 3) psychic damage."
  "name": "Spectral Fangs"
"bonus_actions":
- "desc": "The yuan-ti transforms into a Medium snake or back into its true form.\
    \ Its statistics are the same in each form. Any equipment it is wearing or carrying\
    \ isn't transformed. If it dies, it stays in its current form."
  "name": "Change Shape"
"source":
- "MPMM"
- "VGM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPMM/Yuan-ti%20Mind%20Whisperer.webp"
```
^statblock

```encounter-table
name: Yuan-ti Mind Whisperer
creatures:
 - 1: Yuan-ti Mind Whisperer
```

## Environment

desert, forest, underdark