---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/toa
- monster/cr/4
- monster/size/medium
- monster/type/monstrosity/shapechanger
- monster/type/monstrosity/yuan-ti
aliases: ["Fenthaza"]
NoteIcon: monster
BestiaryType: monstrosity (shapechanger, yuan-ti)
SourceType: Bestiary
BookSource: Tomb of Annihilation p. 113
---
# [Fenthaza](2-Mechanics\CLI\bestiary\npc/fenthaza-toa.md)
*Source: Tomb of Annihilation p. 113*  

```statblock
"name": "Fenthaza (ToA)"
"size": "Medium"
"type": "monstrosity"
"subtype": "shapechanger, yuan-ti"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "71"
"hit_dice": "13d8 + 13"
"stats":
- !!int "16"
- !!int "14"
- !!int "13"
- !!int "14"
- !!int "12"
- !!int "16"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Wisdom": !!int "3"
"skillsaves":
  "Deception": !!int "5"
  "Stealth": !!int "4"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/2-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft. (penetrates magical darkness), passive Perception 11"
"languages": "Abyssal, Common, Draconic"
"cr": "4"
"traits":
- "desc": "Fenthaza's innate spellcasting ability is Charisma (spell save DC 13).\
    \ Fenthaza can innately cast the following spells, requiring no material components:\n\
    \nAt will: [animal friendship](/2-Mechanics/CLI/spells/animal-friendship.md)\
    \ (snakes only)\n\n3/day: [suggestion](/2-Mechanics/CLI/spells/suggestion.md)"
  "name": "Innate Spellcasting (Yuan-ti Form Only)"
- "desc": "Fenthaza is a 6th-level spellcaster. Its spellcasting ability is Charisma\
    \ (spell save DC 13, +5 to hit with spell attacks). It regains its expended\
    \ spell slots when it finishes a short or long rest. It knows the following warlock\
    \ spells:\n\nCantrips (at will): [chill touch](/2-Mechanics/CLI/spells/chill-touch.md),\
    \ [eldritch blast](/2-Mechanics/CLI/spells/eldritch-blast.md) (range 300 ft.,\
    \ +3 bonus to each damage roll), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [message](/2-Mechanics/CLI/spells/message.md), [poison spray](/2-Mechanics/CLI/spells/poison-spray.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\n1st-3rd\
    \ level (2 slots): [arms of Hadar](/2-Mechanics/CLI/spells/arms-of-hadar.md),\
    \ [darkness](/2-Mechanics/CLI/spells/darkness.md), [fear](/2-Mechanics/CLI/spells/fear.md),\
    \ [hex](/2-Mechanics/CLI/spells/hex.md), [hold person](/2-Mechanics/CLI/spells/hold-person.md),\
    \ [hunger of Hadar](/2-Mechanics/CLI/spells/hunger-of-hadar.md), [witch bolt](/2-Mechanics/CLI/spells/witch-bolt.md)"
  "name": "Spellcasting (Yuan-ti Form Only)"
- "desc": "Fenthaza can use its action to polymorph into a Medium snake or back into\
    \ its true form. Its statistics are the same in each form. Any equipment it is\
    \ wearing or carrying isn't transformed. If it dies, it stays in its current form."
  "name": "Shapechanger"
- "desc": "The first time Fenthaza hits with a melee attack on its turn, it can deal\
    \ an extra 16 (3d10) necrotic damage to the target."
  "name": "Death Fangs (2/Day)"
- "desc": "Fenthaza has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Fenthaza makes one constrict attack and one scimitar attack."
  "name": "Multiattack (Yuan-ti Form Only)"
- "desc": "Melee Weapon Attack: +5 to hit, reach 10 ft., one target. Hit: 10\
    \ (2d6 + 3) bludgeoning damage, and the target is [grappled](/2-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 14) if it is a Large or smaller creature. Until this grapple ends,\
    \ the target is [restrained](/2-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and Fenthaza can't constrict another target."
  "name": "Constrict"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Scimitar (Yuan-ti Form Only)"
- "desc": "Fenthaza taps into the nightmares of a creature it can see within 60 feet\
    \ of it and creates an illusory, immobile manifestation of the creature's deepest\
    \ fears, visible only to that creature. The target must make a DC 13 Intelligence\
    \ saving throw. On a failed save, the target takes 11 (2d10) psychic damage\
    \ and is [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened) of the\
    \ manifestation, believing it to be real. Fenthaza must concentrate to maintain\
    \ the illusion (as if concentrating on a spell), which lasts for up to 1 minute\
    \ and can't be harmed. The target can repeat the saving throw at the end of each\
    \ of its turns, ending the illusion on a success, or taking 11 (2d10) psychic\
    \ damage on a failure."
  "name": "Invoke Nightmare (Recharges after a Short or Long Rest)"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToA/Fenthaza.webp"
```
^statblock

```encounter-table
name: Fenthaza
creatures:
 - 1: Fenthaza
```