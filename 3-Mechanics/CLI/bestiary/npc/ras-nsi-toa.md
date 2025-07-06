---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/7
- monster/size/medium
- monster/type/monstrosity/shapechanger
- monster/type/monstrosity/yuan-ti
aliases: ["Ras Nsi"]
NoteIcon: monster
BestiaryType: monstrosity (shapechanger, yuan-ti)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 230
---
# [Ras Nsi](2-Mechanics\CLI\bestiary\npc/ras-nsi-toa.md)
*Source: Tomb of Annihilation p. 230*  

The word "ras" is a noble title akin to "duke." Ras Nsi was once a Chultan paladin, a Chosen of Ubtao and sworn protector of the city of Mezro. He betrayed his oaths and was banished from the city. Becoming a vengeful warlord, Ras Nsi attempted to conquer Mezro with an undead army but was defeated. Rather than seek redemption, he sought revenge and was stripped of his god-given powers. The undead horde, no longer under his control, spread throughout the jungles of Chult.

Withdrawing to Omu, Nsi clung to his noble title, joined forces with the yuan-ti living there, and underwent a horrible ritual to become a powerful yuan-ti malison-retaining his human head and torso and gaining a serpentine lower body. With Ubtao gone from the world, Ras Nsi and his new yuan-ti followers began searching for a way to bring forth Dendar the Night Serpent. Acererak has promised to help this effort, in exchange for Ras Nsi's pledge to defend the Tomb of the Nine Gods. In truth, Acererak has no intention of honoring his bargain, and Ras Nsi is beginning to suspect as much.

## Strange Collection

Ras Nsi has a sizable collection of apparel and accouterments from distant lands, most of which were taken from dead explorers. The collection includes a fine Cormyrean cloak, a Sembian wine flask, and a bejeweled Amnian doublet and matching money pouch. He also bears a flame tongue longsword.

## Slow Death

Ras Nsi has died and been brought back from the dead more than once. Consequently, he is suffering from the effects of the Soulmonger's death curse. His hit point maximum has been reduced, and leprous wounds cover his flesh. In a fitting irony, Ras Nsi is unaware that Acererak is the cause of the curse, for neither he nor the yuan-ti are aware of what lies within the Tomb of the Nine Gods, other than the dead gods for which it is named. If the characters can make him understand that their efforts will help him, Ras Nsi might be tempted not to stand in their way.

## Ras Nsi's Traits

### Ideal

"I seek to bring about the end of this world and rule the next one."

### Bond

"The yuan-ti of Chult are mine to command. They will help me rule an empire."

### Flaw

"I will do anything and betray anyone to save myself."

```statblock
"name": "Ras Nsi (ToA)"
"size": "Medium"
"type": "monstrosity"
"subtype": "shapechanger, yuan-ti"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "[bracers of defense](/2-Mechanics/CLI/items/bracers-of-defense.md)"
"stats":
- !!int "17"
- !!int "16"
- !!int "17"
- !!int "18"
- !!int "18"
- !!int "21"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "7"
  "Constitution": !!int "6"
"skillsaves":
  "Deception": !!int "8"
  "Stealth": !!int "6"
  "Religion": !!int "7"
  "Persuasion": !!int "8"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Abyssal, Common, Draconic"
"cr": "7"
"traits":
- "desc": "Ras Nsi's innate spellcasting ability is Charisma (spell save DC 16). He\
    \ can innately cast the following spells, requiring no material components:\n\n\
    At will: [animal friendship](/2-Mechanics/CLI/spells/animal-friendship.md)\
    \ (snakes only)\n\n3/day: [suggestion](/2-Mechanics/CLI/spells/suggestion.md)"
  "name": "Innate Spellcasting"
- "desc": "Ras Nsi is an 11th-level spellcaster. His spellcasting ability is Intelligence\
    \ (spell save DC 15, +7 to hit with spell attacks).\n\nRas Nsi has the following\
    \ wizard spells prepared:\n\nCantrips (at will): [chill touch](/2-Mechanics/CLI/spells/chill-touch.md),\
    \ [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [mending](/2-Mechanics/CLI/spells/mending.md), [poison spray](/2-Mechanics/CLI/spells/poison-spray.md)\n\
    \n1st level (4 slots): [expeditious retreat](/2-Mechanics/CLI/spells/expeditious-retreat.md),\
    \ [false life](/2-Mechanics/CLI/spells/false-life.md), [magic missile](/2-Mechanics/CLI/spells/magic-missile.md),\
    \ [shield](/2-Mechanics/CLI/spells/shield.md)\n\n2nd level (3 slots): [blindness/deafness](/2-Mechanics/CLI/spells/blindness-deafness.md),\
    \ [hold person](/2-Mechanics/CLI/spells/hold-person.md), [misty step](/2-Mechanics/CLI/spells/misty-step.md)\n\
    \n3rd level (3 slots): [animate dead](/2-Mechanics/CLI/spells/animate-dead.md),\
    \ [counterspell](/2-Mechanics/CLI/spells/counterspell.md), [fireball](/2-Mechanics/CLI/spells/fireball.md)\n\
    \n4th level (3 slots): [blight](/2-Mechanics/CLI/spells/blight.md), [polymorph](/2-Mechanics/CLI/spells/polymorph.md)\n\
    \n5th level (2 slots): [contact other plane](/2-Mechanics/CLI/spells/contact-other-plane.md),\
    \ [geas](/2-Mechanics/CLI/spells/geas.md)\n\n6th level (1 slots): [create\
    \ undead](/2-Mechanics/CLI/spells/create-undead.md)"
  "name": "Spellcasting"
- "desc": "Ras Nsi wears [bracers of defense](/2-Mechanics/CLI/items/bracers-of-defense.md),\
    \ wields a [flame tongue longsword](/2-Mechanics/CLI/items/flame-tongue.md), and\
    \ carries a [sending stone](/2-Mechanics/CLI/items/sending-stones.md) matched\
    \ to the one carried by the guide Salida (see chapter 1)."
  "name": "Special Equipment"
- "desc": "Ras Nsi can use his action to polymorph into a Medium snake or back into\
    \ his yuan-ti form. His statistics are the same in each form. Any equipment he\
    \ is wearing or carrying isn't transformed. He doesn't change form if he dies."
  "name": "Shapechanger"
- "desc": "Ras Nsi has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Ras Nsi makes three melee attacks, but can use Constrict only once."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 5 (1d4\
    \ + 3) piercing damage plus 7 (2d6) poison damage."
  "name": "Bite (Snake Form Only)"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. Hit: 10\
    \ (2d6 + 3) bludgeoning damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 14). Until this grapple ends, the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and Ras Nsi can't constrict another target."
  "name": "Constrict"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage when used with two\
    \ hands, plus 7 (2d6) fire damage."
  "name": "Flame Tongue Longsword (Yuan-ti Form Only)"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Ras%20Nsi.webp"
```
^statblock

```encounter-table
name: Ras Nsi
creatures:
 - 1: Ras Nsi
```