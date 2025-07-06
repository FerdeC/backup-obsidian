---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cm
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Master Sage"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Candlekeep Mysteries p. 9
---
# [Master Sage](2-Mechanics\CLI\bestiary\humanoid/master-sage-cm.md)
*Source: Candlekeep Mysteries p. 9*  

Candlekeep's resident lore experts are master sages and sages who dedicate themselves to scholarship above all.

```statblock
"name": "Master Sage (CM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "54"
"hit_dice": "12d8"
"stats":
- !!int "8"
- !!int "10"
- !!int "10"
- !!int "20"
- !!int "18"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Medicine": !!int "10"
  "Nature": !!int "11"
  "Investigation": !!int "11"
  "Religion": !!int "11"
  "Insight": !!int "7"
  "History": !!int "11"
  "Arcana": !!int "11"
"senses": "passive Perception 14"
"languages": "Common plus any five languages"
"cr": "5"
"traits":
- "desc": "The sage casts one of the following spells, using Intelligence as the spellcasting\
    \ ability (save DC 14, +6 to hit with spell attacks):\n\nAt will: [light](/2-Mechanics/CLI/spells/light.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [mending](/2-Mechanics/CLI/spells/mending.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md), \n\n1/day\
    \ each: [banishment](/2-Mechanics/CLI/spells/banishment.md), [contact other\
    \ plane](/2-Mechanics/CLI/spells/contact-other-plane.md), [Drawmij's instant summons](/2-Mechanics/CLI/spells/drawmijs-instant-summons.md),\
    \ [legend lore](/2-Mechanics/CLI/spells/legend-lore.md), [locate creature](/2-Mechanics/CLI/spells/locate-creature.md),\
    \ [planar binding](/2-Mechanics/CLI/spells/planar-binding.md), [polymorph](/2-Mechanics/CLI/spells/polymorph.md),\
    \ [protection from evil and good](/2-Mechanics/CLI/spells/protection-from-evil-and-good.md),\
    \ [scrying](/2-Mechanics/CLI/spells/scrying.md), [sending](/2-Mechanics/CLI/spells/sending.md),\
    \ [true seeing](/2-Mechanics/CLI/spells/true-seeing.md)\n\n3/day each: [comprehend\
    \ languages](/2-Mechanics/CLI/spells/comprehend-languages.md), [detect magic](/2-Mechanics/CLI/spells/detect-magic.md),\
    \ [dispel magic](/2-Mechanics/CLI/spells/dispel-magic.md), , [identify](/2-Mechanics/CLI/spells/identify.md),\
    \ [levitate](/2-Mechanics/CLI/spells/levitate.md), [locate object](/2-Mechanics/CLI/spells/locate-object.md),\
    \ , [Tenser's Floating Disk](/2-Mechanics/CLI/spells/tensers-floating-disk.md),\
    \ [unseen servant](/2-Mechanics/CLI/spells/unseen-servant.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee Spell Attack: +8 to hit (with advantage if the target is wearing\
    \ armor made of metal), reach 5 ft., one creature. Hit: 13 (3d8) lightning\
    \ damage, and the target can't take reactions until the start of its next turn."
  "name": "Shocking Grasp (Cantrip)"
- "desc": "The sage creates a fiery explosion centered on a point it can see within\
    \ 150 feet of it. Each creature in a 20-foot-radius sphere centered on that point\
    \ must make a DC 14 Dexterity saving throw, taking 28 (8d6) fire damage on a\
    \ failed save, or half as much damage on a successful one. The fire spreads around\
    \ corners and ignites flammable objects in the area that aren't being worn or\
    \ carried."
  "name": "Fireball (3rd-Level Spell; 3/Day)"
"reactions":
- "desc": "When the sage is hit by an attack or targeted by a [magic missile](/2-Mechanics/CLI/spells/magic-missile.md)\
    \ spell, it calls forth an [invisible](/2-Mechanics/CLI/rules/conditions.md#invisible)\
    \ barrier of magical force that protects it. Until the start of its next turn,\
    \ the sage has a +5 bonus to AC, including against the triggering attack, and\
    \ it takes no damage from magic missile."
  "name": "Shield (1st-Level Spell; 3/Day)"
"source":
- "CM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CM/Master%20Sage.webp"
```
^statblock

```encounter-table
name: Master Sage
creatures:
 - 1: Master Sage
```