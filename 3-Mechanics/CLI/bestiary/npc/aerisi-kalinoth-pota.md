---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/7
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Aerisi Kalinoth"]
NoteIcon: monster
BestiaryType: humanoid (elf)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 192
---
# [Aerisi Kalinoth](2-Mechanics\CLI\bestiary\npc/aerisi-kalinoth-pota.md)
*Source: Princes of the Apocalypse p. 192*  

Aerisi Kalinoth is the air prophet of the Elder Elemental Eye and leader of the Cult of the Howling Hatred. Tall and slender, with dark hair and (illusory) feathered wings that gently fan the air, Aerisi Kalinoth speaks to her people in a whisper that belies her violent temper, which reveals itself whenever she is denied.

Aerisi was a sheltered moon elf princess named Dara Algwynenn Kalinoth who grew up in a remote Faerie realm. Her parents had wished to protect her from the harsh realities of the world, but they only succeeded in spoiling her. When they tried to discipline their wilful daughter, she used the power of elemental air against them. Soon after, her dreams led her to the ancient dwarven ruins where the spear Windvane awaited her.

Dara changed her name to Aerisi and pretended to be an avariel (winged elf) princess like the ones from her storybooks. Then Aerisi used her talents for enchantment magic to sway mortals into joining her cult. She has convinced all her followers that she is in fact an avariel, and believes it herself even though she must cast [seeming](/2-Mechanics/CLI/spells/seeming.md) each day to "reveal" her wings.

Aerisi is prone to deluded flights of fancy and impulsive decadence. She sees herself as a beautiful, fierce, and just ruler who wields elemental power because she deserves it.

## In the Air Node

When danger threatens the Temple of Howling Hatred, Aerisi retreats to the Howling Caves, the air node. Within this node, Aerisi gains one additional use of her Legendary Resistance trait.

```statblock
"name": "Aerisi Kalinoth (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "16 with [mage armor](/2-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"stats":
- !!int "8"
- !!int "16"
- !!int "12"
- !!int "17"
- !!int "10"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "3"
  "History": !!int "6"
  "Arcana": !!int "6"
"damage_resistances": "lightning"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Auran, Common, Elvish"
"cr": "7"
"traits":
- "desc": "Aerisi is a 12th-level spellcaster. Her spellcasting ability is Intelligence\
    \ (spell save DC 14, +6 to hit with spell attacks). Aerisi has the following\
    \ wizard spells prepared:\n\nCantrips (at will): [gust](/2-Mechanics/CLI/spells/gust-xge.md),\
    \ [mage hand](/2-Mechanics/CLI/spells/mage-hand.md), [message](/2-Mechanics/CLI/spells/message.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md), [ray of frost](/2-Mechanics/CLI/spells/ray-of-frost.md),\
    \ [shocking grasp](/2-Mechanics/CLI/spells/shocking-grasp.md)\n\n1st level (4\
    \ slots): [charm person](/2-Mechanics/CLI/spells/charm-person.md), [feather\
    \ fall](/2-Mechanics/CLI/spells/feather-fall.md), [mage armor](/2-Mechanics/CLI/spells/mage-armor.md),\
    \ [thunderwave](/2-Mechanics/CLI/spells/thunderwave.md)\n\n2nd level (3 slots):\
    \ [dust devil](/2-Mechanics/CLI/spells/dust-devil-xge.md), [gust of wind](/2-Mechanics/CLI/spells/gust-of-wind.md),\
    \ [invisibility](/2-Mechanics/CLI/spells/invisibility.md)\n\n3rd level (3 slots):\
    \ [fly](/2-Mechanics/CLI/spells/fly.md), [gaseous form](/2-Mechanics/CLI/spells/gaseous-form.md),\
    \ [lightning bolt](/2-Mechanics/CLI/spells/lightning-bolt.md)\n\n4th level (3\
    \ slots): [ice storm](/2-Mechanics/CLI/spells/ice-storm.md), [storm sphere](/2-Mechanics/CLI/spells/storm-sphere-xge.md)\n\
    \n5th level (2 slots): [cloudkill](/2-Mechanics/CLI/spells/cloudkill.md),\
    \ [seeming](/2-Mechanics/CLI/spells/seeming.md) (cast each day)\n\n6th level\
    \ (1 slots): [chain lightning](/2-Mechanics/CLI/spells/chain-lightning.md)"
  "name": "Spellcasting"
- "desc": "Aerisi has advantage on saving throws against being [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed),\
    \ and magic can't put her to sleep."
  "name": "Fey Ancestry"
- "desc": "When Aerisi drops to 0 hit points, her body disappears in a howling whirlwind\
    \ that disperses quickly and harmlessly. Anything she is wearing or carrying is\
    \ left behind."
  "name": "Howling Defeat"
- "desc": "If Aerisi fails a saving throw, she can choose to succeed instead."
  "name": "Legendary Resistance (2/Day)"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +9 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 9 (1d6 + 6) piercing damage, or 10 (1d8 + 6) piercing\
    \ damage if used with two hands to make a melee attack, plus 3 (1d6) lightning\
    \ damage."
  "name": "Windvane"
"lair_actions":
- "desc": "If Aerisi is in the air node while [Yan-C-Bin](/2-Mechanics/CLI/bestiary/npc/yan-c-bin-pota.md)\
    \ isn't, Aerisi can take lair actions. On initiative count 20 (losing initiative\
    \ ties), Aerisi uses a lair action to cast one of her spells, up to 3rd level,\
    \ without using components or a spell slot. She can't cast the same spell two\
    \ rounds in a row, although she can continue to concentrate on a spell she previously\
    \ cast using a lair action. Aerisi can take no other lair actions while concentrating\
    \ on a spell cast as a lair action."
  "name": ""
- "desc": "If Aerisi casts [invisibility](/2-Mechanics/CLI/spells/invisibility.md)\
    \ using this lair action, she also draws the power of the air node into herself.\
    \ By doing so, she regains 15 (3d8 + 2) hit points."
  "name": ""
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Aerisi%20Kalinoth.webp"
```
^statblock

```encounter-table
name: Aerisi Kalinoth
creatures:
 - 1: Aerisi Kalinoth
```