---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/mpmm
- monster/cr/11
- monster/environment/mountain
- monster/size/huge
- monster/type/giant
aliases: ["Cloud Giant Smiling One"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 81, Volo's Guide to Monsters p. 146
---
# [Cloud Giant Smiling One](2-Mechanics\CLI\bestiary\giant/cloud-giant-smiling-one-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 81, Volo's Guide to Monsters p. 146*  

Smiling ones are cloud giants who honor and emulate the craftiness and deceit of the deity Memnor above all else. They are tricksters supreme who use sleight of hand, deception, misdirection, and magic in their pursuit of wealth. They also possess a flair for unpredictability and a wicked sense of humor. Smiling ones overstep all bounds of decorum with their behavior, doing and saying things that even other knavish folk consider beneath their dignity.

Smiling ones take their name from the strange two-faced masks they wear. The smiling half of the face often looks more like a smirk or a triumphant sneer than a pleasant grin. The frowning half represents the displeasure smiling ones feel about cloud giants' place in the ordning—second to storm giants. The masks serve as symbols of smiling ones' devotion and also conceal their wearers' true facial expressions.

```statblock
"name": "Cloud Giant Smiling One (MPMM)"
"size": "Huge"
"type": "giant"
"alignment": "Typically  Chaotic Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "250"
"hit_dice": "20d12 + 120"
"stats":
- !!int "26"
- !!int "12"
- !!int "22"
- !!int "15"
- !!int "16"
- !!int "17"
"speed": "40 ft., fly 40 ft. (hover)"
"saves":
  "Charisma": !!int "7"
  "Intelligence": !!int "6"
  "Constitution": !!int "10"
"skillsaves":
  "Sleight of Hand": !!int "9"
  "Deception": !!int "11"
  "Insight": !!int "7"
  "Perception": !!int "11"
"senses": "passive Perception 21"
"languages": "Common, Giant"
"cr": "11"
"traits":
- "desc": "The giant casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 15):\n\nAt will:\
    \ [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [fog cloud](/2-Mechanics/CLI/spells/fog-cloud.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md), [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md)\n\
    \n1/day each: [gaseous form](/2-Mechanics/CLI/spells/gaseous-form.md), [major\
    \ image](/2-Mechanics/CLI/spells/major-image.md)\n\n3/day each: [invisibility](/2-Mechanics/CLI/spells/invisibility.md),\
    \ [silent image](/2-Mechanics/CLI/spells/silent-image.md), [suggestion](/2-Mechanics/CLI/spells/suggestion.md),\
    \ [tongues](/2-Mechanics/CLI/spells/tongues.md)"
  "name": "Spellcasting"
- "desc": "The giant can cast the [control weather](/2-Mechanics/CLI/spells/control-weather.md)\
    \ spell, requiring no material components and using Charisma as the spellcasting\
    \ ability."
  "name": "Control Weather (8th-level Spell)"
"actions":
- "desc": "The giant makes two Slam attacks or two Telekinetic Strike attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 10 ft., one target. Hit: 21\
    \ (3d8 + 8) bludgeoning damage plus 5 (1d10) psychic damage."
  "name": "Slam"
- "desc": "Ranged Spell Attack: +7 to hit, range 240 ft., one target. Hit: 25\
    \ (4d10 + 3) force damage."
  "name": "Telekinetic Strike"
- "desc": "The giant magically transforms to look and feel like a Beast or a Humanoid\
    \ it has seen or to return to its true form. Any equipment the giant is wearing\
    \ or carrying is absorbed by the new form. Its statistics, other than its size,\
    \ don't change. It reverts to its true form if it dies."
  "name": "Change Shape"
"bonus_actions":
- "desc": "The giant teleports, along with any equipment it is wearing or carrying,\
    \ up to 60 feet to an unoccupied space it can see."
  "name": "Cloud Step (Recharge 4-6)"
"source":
- "MPMM"
- "VGM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPMM/Cloud%20Giant%20Smiling%20One.webp"
```
^statblock

```encounter-table
name: Cloud Giant Smiling One
creatures:
 - 1: Cloud Giant Smiling One
```

## Environment

mountain