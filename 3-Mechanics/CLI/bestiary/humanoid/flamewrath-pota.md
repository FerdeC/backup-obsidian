---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/6
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Flamewrath"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 201
---
# [Flamewrath](2-Mechanics\CLI\bestiary\humanoid/flamewrath-pota.md)
*Source: Princes of the Apocalypse p. 201*  

A flamewrath is a spellcaster that has earned the favor of Imix, the Prince of Elemental Fire, through a series of painful rites. A flamewrath's skin is burned and scarred. Inured to pain, the flamewrath revels in battle, using an array of fire spells to incinerate enemies who would try to douse the power of elemental fire. Melee combatants who draw too close face fires that can dance across the flamewrath's skin and burn attackers.

```statblock
"name": "Flamewrath (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "105"
"hit_dice": "14d8 + 42"
"stats":
- !!int "10"
- !!int "14"
- !!int "16"
- !!int "11"
- !!int "10"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Religion": !!int "3"
  "Arcana": !!int "3"
"damage_immunities": "fire"
"senses": "passive Perception 10"
"languages": "Common, Ignan"
"cr": "6"
"traits":
- "desc": "The flamewrath is a 7th-level spellcaster. Its spellcasting ability is\
    \ Charisma (spell save DC 14, +6 to hit with spell attacks). It knows the following\
    \ sorcerer spells:\n\nCantrips (at will): [control flames](/2-Mechanics/CLI/spells/control-flames-xge.md),\
    \ [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md), [friends](/2-Mechanics/CLI/spells/friends.md),\
    \ [light](/2-Mechanics/CLI/spells/light.md), [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md)\n\
    \n1st level (4 slots): [burning hands](/2-Mechanics/CLI/spells/burning-hands.md),\
    \ [color spray](/2-Mechanics/CLI/spells/color-spray.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)\n\
    \n2nd level (3 slots): [scorching ray](/2-Mechanics/CLI/spells/scorching-ray.md),\
    \ [suggestion](/2-Mechanics/CLI/spells/suggestion.md)\n\n3rd level (3 slots):\
    \ [fireball](/2-Mechanics/CLI/spells/fireball.md), [hypnotic pattern](/2-Mechanics/CLI/spells/hypnotic-pattern.md)\n\
    \n4th level (1 slots): [fire shield](/2-Mechanics/CLI/spells/fire-shield.md)\
    \ (see Wreathed in Flame)"
  "name": "Spellcasting"
- "desc": "For the flamewrath, the warm version of the [fire shield](/2-Mechanics/CLI/spells/fire-shield.md)\
    \ spell has a duration of \"until dispelled.\" The fire shield burns for 10 minutes\
    \ after the flamewrath dies, consuming its body."
  "name": "Wreathed in Flame"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Flamewrath.webp"
```
^statblock

```encounter-table
name: Flamewrath
creatures:
 - 1: Flamewrath
```