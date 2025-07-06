---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/vgm
- monster/cr/6
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Booyahg Slave of the Great Old One"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Volo's Guide to Monsters p. 42
---
# [Booyahg Slave of the Great Old One](2-Mechanics\CLI\bestiary\humanoid/booyahg-slave-of-the-great-old-one-vgm.md)
*Source: Volo's Guide to Monsters p. 42*  

This goblin warlock serves a patron who can extract payment in flesh if the goblin doesn't do as promised. Often this patron is a coven of hags serving as the tribe's boss, a fiend that has made its way into the world, or an undying lord such as a lich or a vampire. (For more information on undying lord patrons, see the "Sword Coast Adventurer's Guide").

## Booyahgs

Spellcasters of any sort among the goblins are rare. Goblins typically lack the intelligence and patience needed to learn and practice wizardry, and they fare poorly even when given access to the necessary training and knowledge. Sorcerers are less prevalent among them than in many other races, and Khurgorbaeyag seems to dislike sharing his divine power with his followers. And although many goblins would readily offer anything to have the abilities of a warlock, the patrons that grant such power know a goblin is unlikely to be able to uphold its end of any bargain.

Even when a goblin is born with the ability to become a spellcaster, the knowledge and talent necessary to carry on the tradition rarely persists for more than a couple of generations. Because they have so little experience with magic, goblins make no distinction between its forms. To them all magic is "booyahg," and the word is part of the name they give to any of its practitioners.

A goblin with access to booyahg becomes a member of the lashers and can often rise to the role of boss.

```statblock
"name": "Booyahg Slave of the Great Old One (VGM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "91"
"hit_dice": "14d8 + 28"
"stats":
- !!int "9"
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
  "History": !!int "4"
  "Arcana": !!int "4"
"damage_resistances": "psychic"
"senses": "darkvision 60 ft., darkvision 60 ft., passive Perception 11"
"languages": "any two languages, telepathy 30 ft., Goblin"
"cr": "6"
"traits":
- "desc": "The goblin's innate spellcasting ability is Charisma. It can innately cast\
    \ the following spells (spell save DC 15), requiring no material components:\n\
    \nAt will: [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [jump](/2-Mechanics/CLI/spells/jump.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)\
    \ (self only), [speak with dead](/2-Mechanics/CLI/spells/speak-with-dead.md)\n\
    \n1/day each: [arcane gate](/2-Mechanics/CLI/spells/arcane-gate.md), [true\
    \ seeing](/2-Mechanics/CLI/spells/true-seeing.md)"
  "name": "Innate Spellcasting"
- "desc": "The goblin is a 14th-level spellcaster. Its spellcasting ability is Charisma\
    \ (spell save DC 15, +7 to hit with spell attacks). It regains its expended\
    \ spell slots when it finishes a short or long rest. It knows the following warlock\
    \ spells:\n\nCantrips (at will): [chill touch](/2-Mechanics/CLI/spells/chill-touch.md),\
    \ [eldritch blast](/2-Mechanics/CLI/spells/eldritch-blast.md), [guidance](/2-Mechanics/CLI/spells/guidance.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [minor illusion](/2-Mechanics/CLI/spells/minor-illusion.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md), [shocking grasp](/2-Mechanics/CLI/spells/shocking-grasp.md)\n\
    \n1st-5th level (3 slots): [armor of Agathys](/2-Mechanics/CLI/spells/armor-of-agathys.md),\
    \ [arms of Hadar](/2-Mechanics/CLI/spells/arms-of-hadar.md), [crown of madness](/2-Mechanics/CLI/spells/crown-of-madness.md),\
    \ [clairvoyance](/2-Mechanics/CLI/spells/clairvoyance.md), [contact other plane](/2-Mechanics/CLI/spells/contact-other-plane.md),\
    \ [detect thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md), [dimension door](/2-Mechanics/CLI/spells/dimension-door.md),\
    \ [dissonant whispers](/2-Mechanics/CLI/spells/dissonant-whispers.md), [dominate\
    \ beast](/2-Mechanics/CLI/spells/dominate-beast.md), [telekinesis](/2-Mechanics/CLI/spells/telekinesis.md),\
    \ [vampiric touch](/2-Mechanics/CLI/spells/vampiric-touch.md)"
  "name": "Spellcasting"
- "desc": "At the start of each of the goblin's turns, each creature of its choice\
    \ within 5 feet of it must succeed on a DC 15 Wisdom saving throw or take 10 (3d6)\
    \ psychic damage, provided that the goblin isn't [incapacitated](/2-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Whispering Aura"
- "desc": "The goblin"
  "name": "Nimble Escape"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "VGM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/VGM/Booyahg%20Slave%20of%20the%20Great%20Old%20One.webp"
```
^statblock

```encounter-table
name: Booyahg Slave of the Great Old One
creatures:
 - 1: Booyahg Slave of the Great Old One
```