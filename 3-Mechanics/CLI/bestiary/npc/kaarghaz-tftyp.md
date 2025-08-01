---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/tftyp
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/troglodyte
aliases: ["Kaarghaz"]
NoteIcon: monster
BestiaryType: humanoid (troglodyte)
SourceType: Bestiary
BookSource: Tales from the Yawning Portal p. 45
---
# [Kaarghaz](2-Mechanics\CLI\bestiary\npc/kaarghaz-tftyp.md)
*Source: Tales from the Yawning Portal p. 45*  

The savage, degenerate troglodytes squat in the shallow depths of the Underdark in a constant state of war against their neighbors and one another. They mark the borders of their territories with cracked bones and skulls, or with pictographs painted in blood or dung.

Perhaps the most loathsome of all humanoids, troglodytes eat anything they can stomach. They dwell in filth. The walls of their cavern homes are smeared with grime, oily secretions, and the debris of their foul feasting.

## Simpleminded Brutes

Troglodytes have a simple, communal culture devoted almost entirely to procuring food. Too simple to plan more than a few days into the future, troglodytes rely on constant raids and hunting to survive. They take sadistic pleasure in hunting intelligent creatures weaker than themselves and show no mercy toward those they capture and drag back to their lairs to be devoured. The largest and toughest troglodytes lead the hunt and become the leaders of their tribes. However, if a leader shows any weakness or hesitation, other troglodytes attack and eat it in a frenzy.

Troglodytes make little and build less, scavenging their possessions from their prey. They understand the value of metal weapons and armor, and fight among one another for the right to have such items. A troglodyte tribe might be torn apart by battles over a single longsword.

## Devotees of Laogzed

Some troglodytes venerate Laogzed, a demonic, monstrously fat toad-lizard that slumbers in the Abyss. Laogzed offers the troglodytes nothing in return except aspiration, for it is the dream of his troglodyte worshipers to become as fat, well-fed, and wearily content as he seems to be.

```statblock
"name": "Kaarghaz (TftYP)"
"size": "Medium"
"type": "humanoid"
"subtype": "troglodyte"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"stats":
- !!int "14"
- !!int "10"
- !!int "14"
- !!int "6"
- !!int "10"
- !!int "15"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "2"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Draconic, Troglodyte"
"cr": "2"
"traits":
- "desc": "Kaarghaz is a 4th-level spellcaster. His spellcasting ability is Charisma\
    \ (spell save DC 12, +4 to hit with spell attacks). He knows the following sorcerer\
    \ spells:\n\nCantrips (at will): [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [poison spray](/2-Mechanics/CLI/spells/poison-spray.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md), [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md)\n\
    \n1st level (6 slots): [burning hands](/2-Mechanics/CLI/spells/burning-hands.md),\
    \ [shield](/2-Mechanics/CLI/spells/shield.md), [sleep](/2-Mechanics/CLI/spells/sleep.md)\n\
    \n2nd level (3 slots): [invisibility](/2-Mechanics/CLI/spells/invisibility.md),\
    \ [scorching ray](/2-Mechanics/CLI/spells/scorching-ray.md)"
  "name": "Spellcasting"
- "desc": "The troglodyte has advantage on Dexterity ([Stealth](/2-Mechanics/CLI/rules/skills.md#Stealth))\
    \ checks made to hide."
  "name": "Chameleon Skin"
- "desc": "Any creature other than a troglodyte that starts its turn within 5 feet\
    \ of the troglodyte must succeed on a DC 12 Constitution saving throw or be [poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ until the start of the creature's next turn. On a successful saving throw, the\
    \ creature is immune to the stench of all troglodytes for 1 hour."
  "name": "Stench"
- "desc": "While in sunlight, the troglodyte has disadvantage on attack rolls, as\
    \ well as on Wisdom ([Perception](/2-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "The troglodyte makes three attacks: one with its bite and two with its\
    \ claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) slashing damage."
  "name": "Claw"
"source":
- "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/TftYP/Kaarghaz.webp"
```
^statblock

```encounter-table
name: Kaarghaz
creatures:
 - 1: Kaarghaz
```