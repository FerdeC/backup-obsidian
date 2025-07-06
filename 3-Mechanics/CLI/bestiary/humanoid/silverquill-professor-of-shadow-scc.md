---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/scc
- monster/cr/7
- monster/size/small-or-medium
- monster/type/humanoid/bard
aliases: ["Silverquill Professor of Shadow"]
NoteIcon: monster
BestiaryType: humanoid (bard)
SourceType: Bestiary
BookSource: Strixhaven: A Curriculum of Chaos p. 215
---
# [Silverquill Professor of Shadow](2-Mechanics\CLI\bestiary\humanoid/silverquill-professor-of-shadow-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 215*  

Professors of shadow wield the linguistic magic of Silverquill College through slicing wit and debilitating inky shadow. Whether weaving their magic through spoken incantations and scathing insults or through shadows, these teachers break down the resolve of their foes.

The professors strive to carry themselves as immaculately as possible, seeking to overawe and wrong-foot anyone who would stand against them in debate or in battle. In teaching their students, professors of shadow focus on words that find the tiniest, most invisible cracks in an opponent's defenses and break them.

## Silverquill Scholars

The scholars of Silverquill College study the power of magic shaped through spoken and written words. They use that power either to illuminate and guide or to obscure and demoralize.

```statblock
"name": "Silverquill Professor of Shadow (SCC)"
"size": "Small or Medium"
"type": "humanoid"
"subtype": "bard"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "97"
"hit_dice": "15d8 + 30"
"stats":
- !!int "11"
- !!int "14"
- !!int "14"
- !!int "16"
- !!int "13"
- !!int "19"
"speed": "30 ft."
"saves":
  "Charisma": !!int "7"
  "Dexterity": !!int "5"
  "Wisdom": !!int "4"
  "Intelligence": !!int "6"
"skillsaves":
  "Deception": !!int "10"
  "Stealth": !!int "5"
  "Arcana": !!int "6"
  "Persuasion": !!int "7"
"damage_resistances": "necrotic"
"senses": "darkvision 300 ft., passive Perception 11"
"languages": "Common plus any four languages"
"cr": "7"
"traits":
- "desc": "The professor casts one of the following spells, requiring no material\
    \ components and using Charisma as the spellcasting ability (spell save DC 15):\n\
    \nAt will: [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md), [friends](/2-Mechanics/CLI/spells/friends.md)\n\
    \n1/day each: [tongues](/2-Mechanics/CLI/spells/tongues.md)\n\n2/day each:\
    \ [bane](/2-Mechanics/CLI/spells/bane.md), [command](/2-Mechanics/CLI/spells/command.md),\
    \ [darkness](/2-Mechanics/CLI/spells/darkness.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
  "name": "Spellcasting"
- "desc": "Magical darkness doesn't impede the professor's darkvision."
  "name": "Devil's Sight"
"actions":
- "desc": "The professor makes two Ink Lance attacks. The professor can replace one\
    \ of the attacks with a use of Spellcasting."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 17 (3d8 + 4) necrotic damage. If the target is a creature,\
    \ it must succeed on a DC 15 Constitution saving throw be [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded)\
    \ until the end of its next turn."
  "name": "Ink Lance"
"source":
- "SCC"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SCC/Silverquill%20Professor%20of%20Shadow.webp"
```
^statblock

```encounter-table
name: Silverquill Professor of Shadow
creatures:
 - 1: Silverquill Professor of Shadow
```