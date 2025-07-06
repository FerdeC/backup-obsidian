---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/cm
- monster/cr/12
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Zikran"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Candlekeep Mysteries p. 145
---
# [Zikran](2-Mechanics\CLI\bestiary\npc/zikran-cm.md)
*Source: Candlekeep Mysteries p. 145*  

Genasi have strong ties to the Inner Planes and the blood of genies flowing through their veins. Like the marids of the Elemental Plane of Water, Zikran is turbulent and unpredictable.

He carries a handheld magic device that controls the elemental cannon. This device, shown in the accompanying illustration, looks like a metal rod with a tip shaped like a bird's head.

On initiative count 20 (losing initiative ties), Zikran uses his handheld device to fire the cannon at one creature he can see, provided the creature is in the basement or on the staircase. Zikran's target must make a DC 17 Dexterity saving throw, taking 24 (`7d6`) cold damage on a failed save, or half as much damage on a successful one. The basement furnishings provide half cover, should a creature wish to hide behind them.

The cannon is a Large object with AC 16, 80 hit points, and immunity to poison and psychic damage. It is mounted atop a swivel and bolted to the dais. The cannon draws power from the crystal in the middle of the room. This crystal sparks with elemental power whenever the cannon is about to fire. If the crystal is destroyed, both Zikran's handheld device and the cannon become powerless. The crystal is a Large object with AC 13, 40 hit points, and immunity to poison and psychic damage.

```statblock
"name": "Zikran (CM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "144"
"hit_dice": "18d8 + 18"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "20"
- !!int "15"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Intelligence": !!int "9"
"skillsaves":
  "History": !!int "13"
  "Arcana": !!int "13"
"damage_resistances": "damage from spells; nonmagical bludgeoning, piercing, slashing\
  \ (from stoneskin); acid"
"senses": "passive Perception 12"
"languages": "Aquan, Common, Primordial, Sahuagin, Undercommon"
"cr": "12"
"traits":
- "desc": "Zikran is an 18th-level spellcaster. Its spellcasting ability is Intelligence\
    \ (spell save DC 17, +9 to hit with spell attacks). Zikran can cast [disguise\
    \ self](/2-Mechanics/CLI/spells/disguise-self.md) and [invisibility](/2-Mechanics/CLI/spells/invisibility.md)\
    \ at will and has the following wizard spells prepared:\n\nAt will: [disguise\
    \ self](/2-Mechanics/CLI/spells/disguise-self.md), [invisibility](/2-Mechanics/CLI/spells/invisibility.md)\n\
    \nCantrips (at will): [fire bolt](/2-Mechanics/CLI/spells/fire-bolt.md), [light](/2-Mechanics/CLI/spells/light.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md),\
    \ [shocking grasp](/2-Mechanics/CLI/spells/shocking-grasp.md)\n\n1st level (4\
    \ slots): [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [identify](/2-Mechanics/CLI/spells/identify.md),\
    \ [mage armor](/2-Mechanics/CLI/spells/mage-armor.md), [magic missile](/2-Mechanics/CLI/spells/magic-missile.md)\n\
    \n2nd level (3 slots): [detect thoughts](/2-Mechanics/CLI/spells/detect-thoughts.md),\
    \ [mirror image](/2-Mechanics/CLI/spells/mirror-image.md), [misty step](/2-Mechanics/CLI/spells/misty-step.md)\n\
    \n3rd level (3 slots): [counterspell](/2-Mechanics/CLI/spells/counterspell.md),\
    \ [fly](/2-Mechanics/CLI/spells/fly.md), [lightning bolt](/2-Mechanics/CLI/spells/lightning-bolt.md)\n\
    \n4th level (3 slots): [banishment](/2-Mechanics/CLI/spells/banishment.md),\
    \ [fire shield](/2-Mechanics/CLI/spells/fire-shield.md), [stoneskin](/2-Mechanics/CLI/spells/stoneskin.md)\n\
    \n5th level (3 slots): [cone of cold](/2-Mechanics/CLI/spells/cone-of-cold.md),\
    \ [conjure elemental](/2-Mechanics/CLI/spells/conjure-elemental.md), [scrying](/2-Mechanics/CLI/spells/scrying.md),\
    \ [wall of force](/2-Mechanics/CLI/spells/wall-of-force.md)\n\n6th level (1\
    \ slots): [globe of invulnerability](/2-Mechanics/CLI/spells/globe-of-invulnerability.md)\n\
    \n7th level (1 slots): [teleport](/2-Mechanics/CLI/spells/teleport.md)\n\n\
    8th level (1 slots): [mind blank](/2-Mechanics/CLI/spells/mind-blank.md)\n\
    \n9th level (1 slots): [time stop](/2-Mechanics/CLI/spells/time-stop.md)\n\
    \nZikran casts these spells on itself before combat."
  "name": "Spellcasting"
- "desc": "Zikran has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Zikran"
  "name": "Amphibious"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "CM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/CM/Zikran.webp"
```
^statblock

```encounter-table
name: Zikran
creatures:
 - 1: Zikran
```