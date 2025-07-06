---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Vellynne Harpell"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 273
---
# [Vellynne Harpell](2-Mechanics\CLI\bestiary\npc/vellynne-harpell-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 273*  

Vellynne Harpell is a member of the prestigious Harpell family, based in the town of Longsaddle. Cold and dispassionate, she took to magic only a decade ago in her late forties and is skilled in the arcane tradition of necromancy. She has a lifelong struggle—a nervous disorder that manifests as trembling. It can affect her balance and her stride, but she has learned to cast her spells unimpeded by it.

Despite her firm grasp of the dark arts, she would not have been admitted into the Arcane Brotherhood without her family connections—a fact that sticks in her craw.

Vellynne brought a family heirloom with her to Icewind Dale: a [professor orb](/2-Mechanics/CLI/items/professor-orb-wdmm.md) (see appendix D) that she refers to by its proper name, [Professor Skant](/2-Mechanics/CLI/items/professor-skant-idrotf.md). This orb has knowledge about Netheril that could be important if Vellynne locates the lost Netherese city buried under the Reghed Glacier. The orb was recently stolen by Nass Lantomir, one of Vellynne's rivals in the Arcane Brotherhood. Vellynne intends to get it back before resuming her quest to find Ythryn.

## Companions

Since arriving in Icewind Dale, Vellynne has secured the services of six [Icewind kobolds](/2-Mechanics/CLI/bestiary/humanoid/icewind-kobold-idrotf.md) that act as her valets and guides. Two of them were killed by a [Melf's acid arrow](/2-Mechanics/CLI/spells/melfs-acid-arrow.md) spell (cast by Vellynne's rival, Nass Lantomir), but Vellynne animated their corpses, turning them into zombies.

If she is wounded, Vellynne can cast [vampiric touch](/2-Mechanics/CLI/spells/vampiric-touch.md) and use the spell to regain hit points at the kobolds' expense.

## Familiar

Vellynne's familiar is a snowy owl, which the wizard uses as a scout. It uses the [owl](/2-Mechanics/CLI/bestiary/beast/owl.md) stat block in the "Monster Manual" but is a celestial instead of a beast.

## Spellbook

Vellynne's spellbook has black leather covers around pages of ragged parchment, all wrapped in a crimson sash. The necromancer's personal sigil is written in goat's blood on the title page. The tome contains the spells Vellynne has prepared plus the following additional spells: [bestow curse](/2-Mechanics/CLI/spells/bestow-curse.md), [blindness/deafness](/2-Mechanics/CLI/spells/blindness-deafness.md), [false life](/2-Mechanics/CLI/spells/false-life.md), [find familiar](/2-Mechanics/CLI/spells/find-familiar.md), [magic weapon](/2-Mechanics/CLI/spells/magic-weapon.md), [polymorph](/2-Mechanics/CLI/spells/polymorph.md), [protection from evil and good](/2-Mechanics/CLI/spells/protection-from-evil-and-good.md), [remove curse](/2-Mechanics/CLI/spells/remove-curse.md), [shield](/2-Mechanics/CLI/spells/shield.md), and [Tenser's floating disk](/2-Mechanics/CLI/spells/tensers-floating-disk.md).

```statblock
"name": "Vellynne Harpell (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral"
"ac": !!int "13"
"ac_class": "[bracers of defense](/2-Mechanics/CLI/items/bracers-of-defense.md)"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"stats":
- !!int "10"
- !!int "12"
- !!int "17"
- !!int "18"
- !!int "15"
- !!int "13"
"speed": "20 ft."
"saves":
  "Wisdom": !!int "4"
  "Intelligence": !!int "6"
"skillsaves":
  "History": !!int "6"
  "Arcana": !!int "6"
"senses": "passive Perception 12"
"languages": "Common, Draconic, Dwarvish, Elvish, Orc"
"cr": "4"
"traits":
- "desc": "Vellynne is an 8th-level spellcaster. Her spellcasting ability is Intelligence\
    \ (spell save DC 14, +6 to hit with spell attacks). She has the following wizard\
    \ spells prepared:\n\nCantrips (at will): [chill touch](/2-Mechanics/CLI/spells/chill-touch.md)\
    \ (see \"Actions\" below), [light](/2-Mechanics/CLI/spells/light.md), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [message](/2-Mechanics/CLI/spells/message.md), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md)\n\
    \n1st level (4 slots): [comprehend languages](/2-Mechanics/CLI/spells/comprehend-languages.md),\
    \ [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [ray of sickness](/2-Mechanics/CLI/spells/ray-of-sickness.md),\
    \ [Tasha's hideous laughter](/2-Mechanics/CLI/spells/tashas-hideous-laughter.md)\n\
    \n2nd level (3 slots): [darkvision](/2-Mechanics/CLI/spells/darkvision.md),\
    \ [hold person](/2-Mechanics/CLI/spells/hold-person.md), [ray of enfeeblement](/2-Mechanics/CLI/spells/ray-of-enfeeblement.md)\n\
    \n3rd level (3 slots): [animate dead](/2-Mechanics/CLI/spells/animate-dead.md),\
    \ [Leomund's tiny hut](/2-Mechanics/CLI/spells/leomunds-tiny-hut.md), [vampiric\
    \ touch](/2-Mechanics/CLI/spells/vampiric-touch.md) (see \"Actions\" below)\n\n\
    4th level (2 slots): [arcane eye](/2-Mechanics/CLI/spells/arcane-eye.md),\
    \ [blight](/2-Mechanics/CLI/spells/blight.md)"
  "name": "Spellcasting"
- "desc": "Vellynne wears [bracers of defense](/2-Mechanics/CLI/items/bracers-of-defense.md)\
    \ and carries a [wand of magic missiles](/2-Mechanics/CLI/items/wand-of-magic-missiles.md)\
    \ (see \"Actions\" below)."
  "name": "Special Equipment"
"actions":
- "desc": "Melee Spell Attack: +6 to hit, reach 5 ft., one creature. Hit: 10\
    \ (3d6) necrotic damage, and Vellynne regains hit points equal to half the necrotic\
    \ damage dealt. If Vellynne casts this spell using a spell slot of 4th level or\
    \ higher, the necrotic damage increases by 1d6 for each slot level above 3rd."
  "name": "Vampiric Touch (3rd-Level Spell; Requires a Spell Slot)"
- "desc": "Ranged Spell Attack: +6 to hit, range 120 ft., one creature. Hit:\
    \ 9 (2d8) necrotic damage, and the target can't regain hit points until the\
    \ start of Vellynne's next turn."
  "name": "Chill Touch (Cantrip)"
- "desc": "While holding this wand, Vellynne can expend 1 or more of its 7 charges\
    \ to cast the [magic missile](/2-Mechanics/CLI/spells/magic-missile.md) spell\
    \ from it. She can expend 1 charge to cast the 1st-level version of the spell.\
    \ She can increase the spell slot level by one for each additional charge she\
    \ expends. The wand regains 1d6 + 1 expended charges daily at dawn. If the wand's\
    \ last charge is expended, roll a d20; on a 1, the wand crumbles into ashes\
    \ and is destroyed."
  "name": "Wand of Magic Missiles"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Vellynne%20Harpell.webp"
```
^statblock

```encounter-table
name: Vellynne Harpell
creatures:
 - 1: Vellynne Harpell
```