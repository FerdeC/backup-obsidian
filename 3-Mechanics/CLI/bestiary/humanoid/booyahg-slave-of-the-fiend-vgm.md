---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/vgm
- monster/cr/7
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Booyahg Slave of the Fiend"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Volo's Guide to Monsters p. 42
---
# [Booyahg Slave of the Fiend](2-Mechanics\CLI\bestiary\humanoid/booyahg-slave-of-the-fiend-vgm.md)
*Source: Volo's Guide to Monsters p. 42*  

This goblin warlock serves a patron who can extract payment in flesh if the goblin doesn't do as promised. Often this patron is a coven of hags serving as the tribe's boss, a fiend that has made its way into the world, or an undying lord such as a lich or a vampire. (For more information on undying lord patrons, see the "Sword Coast Adventurer's Guide").

## Booyahgs

Spellcasters of any sort among the goblins are rare. Goblins typically lack the intelligence and patience needed to learn and practice wizardry, and they fare poorly even when given access to the necessary training and knowledge. Sorcerers are less prevalent among them than in many other races, and Khurgorbaeyag seems to dislike sharing his divine power with his followers. And although many goblins would readily offer anything to have the abilities of a warlock, the patrons that grant such power know a goblin is unlikely to be able to uphold its end of any bargain.

Even when a goblin is born with the ability to become a spellcaster, the knowledge and talent necessary to carry on the tradition rarely persists for more than a couple of generations. Because they have so little experience with magic, goblins make no distinction between its forms. To them all magic is "booyahg," and the word is part of the name they give to any of its practitioners.

A goblin with access to booyahg becomes a member of the lashers and can often rise to the role of boss.

```statblock
"name": "Booyahg Slave of the Fiend (VGM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"stats":
- !!int "10"
- !!int "14"
- !!int "15"
- !!int "12"
- !!int "12"
- !!int "18"
"speed": "30 ft."
"saves":
  "Charisma": !!int "7"
  "Wisdom": !!int "4"
"skillsaves":
  "Deception": !!int "7"
  "Religion": !!int "4"
  "Arcana": !!int "4"
  "Persuasion": !!int "7"
"damage_resistances": "slashing from nonmagical attacks not made with silvered weapons"
"senses": "darkvision 60 ft., darkvision 60 ft., passive Perception 11"
"languages": "any two languages (usually Abyssal or Infernal), Goblin"
"cr": "7"
"traits":
- "desc": "The goblin's innate spellcasting ability is Charisma. It can innately cast\
    \ the following spells (spell save DC 15), requiring no material components:\n\
    \nAt will: [alter self](/2-Mechanics/CLI/spells/alter-self.md), [false life](/2-Mechanics/CLI/spells/false-life.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md) (self only), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)\
    \ (self only), [silent image](/2-Mechanics/CLI/spells/silent-image.md)\n\n1/day\
    \ each: [feeblemind](/2-Mechanics/CLI/spells/feeblemind.md), [finger of death](/2-Mechanics/CLI/spells/finger-of-death.md),\
    \ [plane shift](/2-Mechanics/CLI/spells/plane-shift.md)"
  "name": "Innate Spellcasting"
- "desc": "The goblin is a 17th-level spellcaster. Its spellcasting ability is Charisma\
    \ (spell save DC 15, +7 to hit with spell attacks). It regains its expended\
    \ spell slots when it finishes a short or long rest. It knows the following warlock\
    \ spells:\n\nCantrips (at will): [eldritch blast](/2-Mechanics/CLI/spells/eldritch-blast.md),\
    \ [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md), [friends](/2-Mechanics/CLI/spells/friends.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md), [shocking grasp](/2-Mechanics/CLI/spells/shocking-grasp.md)\n\
    \n1st-5th level (4 slots): [banishment](/2-Mechanics/CLI/spells/banishment.md),\
    \ [burning hands](/2-Mechanics/CLI/spells/burning-hands.md), [flame strike](/2-Mechanics/CLI/spells/flame-strike.md),\
    \ [hellish rebuke](/2-Mechanics/CLI/spells/hellish-rebuke.md), [magic circle](/2-Mechanics/CLI/spells/magic-circle.md),\
    \ [scorching ray](/2-Mechanics/CLI/spells/scorching-ray.md), [scrying](/2-Mechanics/CLI/spells/scrying.md),\
    \ [stinking cloud](/2-Mechanics/CLI/spells/stinking-cloud.md), [suggestion](/2-Mechanics/CLI/spells/suggestion.md),\
    \ [wall of fire](/2-Mechanics/CLI/spells/wall-of-fire.md)"
  "name": "Spellcasting"
- "desc": "When the goblin makes an ability check or saving throw, it can add a d10\
    \ to the roll. It can do this after the roll is made but before any of the roll's\
    \ effects occur."
  "name": "Dark One's Own Luck (Recharges after a Short or Long Rest)"
- "desc": "The goblin"
  "name": "Nimble Escape"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d6)\
    \ bludgeoning damage plus 10 (3d6) fire damage."
  "name": "Mace"
"source":
- "VGM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/VGM/Booyahg%20Slave%20of%20the%20Fiend.webp"
```
^statblock

```encounter-table
name: Booyahg Slave of the Fiend
creatures:
 - 1: Booyahg Slave of the Fiend
```