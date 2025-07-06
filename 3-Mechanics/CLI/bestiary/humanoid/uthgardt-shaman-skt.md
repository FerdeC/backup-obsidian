---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/skt
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Uthgardt Shaman"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Storm King's Thunder p. 243
---
# [Uthgardt Shaman](2-Mechanics\CLI\bestiary\humanoid/uthgardt-shaman-skt.md)
*Source: Storm King's Thunder p. 243*  

The Uthgardt are suspicious and resentful of most kinds of magic. Seldom do they choose to become shamans. Instead, the role is thrust upon those who are born with a strong connection to the spirit world. To be a shaman is to stand with one foot in the land of the living and the other in the land of the dead. Those who walk the shadowed path between two lands do so because the spirits of the dead compel them. Other Uthgardt fear and respect a shaman's power.

An Uthgardt shaman must possess a sacred bundle to cast spells. A sacred bundle is made up of sticks, bones, feathers, tufts of fur, and stones that have been "touched" by spirits. It takes a month for a shaman to assemble a sacred bundle, and a shaman can use only one such bundle at a time. A sacred bundle benefits only the shaman who created it, and it doesn't replace the normal components of a spell.

In addition to the spells that all Uthgardt shamans can cast, a shaman of a particular tribe gains additional spells based on tribal affiliation (see the "Uthgardt Sha man Tribal Spells" sidebar).

By communing with their ancestors' spirits, Uthgardt shamans can also learn secret rituals. These rituals almost always require some sort of blood sacrifice, and their effects are usually transformative. For example, some Black Raven shamans know a ritual that allows them to hatch giant ravens from normal raven eggs, and some shamans of the Griffon tribe can transform them selves into griffons by performing a ritual that requires them to drink copious amounts of horse blood.

## Uthgardt Shaman Tribal Spells

Depending on an Uthgardt shaman's tribe, the shaman's Innate Spellcasting feature gains additional spells the shaman can cast once per day.

Black Lion: [chill touch](/2-Mechanics/CLI/spells/chill-touch.md), [feign death](/2-Mechanics/CLI/spells/feign-death.md), [revivify](/2-Mechanics/CLI/spells/revivify.md)

Black Raven: [animal messenger](/2-Mechanics/CLI/spells/animal-messenger.md) (raven only), [polymorph](/2-Mechanics/CLI/spells/polymorph.md) (self only; into a raven only)

Blue Bear: [enhance ability](/2-Mechanics/CLI/spells/enhance-ability.md) (bear's endurance only), [heroism](/2-Mechanics/CLI/spells/heroism.md)

Elk: [find steed](/2-Mechanics/CLI/spells/find-steed.md) (cast as 1 action; elk only), [haste](/2-Mechanics/CLI/spells/haste.md)

Gray Wolf: [beast sense](/2-Mechanics/CLI/spells/beast-sense.md) (wolf or dire wolf only), [moonbeam](/2-Mechanics/CLI/spells/moonbeam.md), [speak with animals](/2-Mechanics/CLI/spells/speak-with-animals.md) (wolf or dire wolf only)

Great Worm: [crusader's mantle](/2-Mechanics/CLI/spells/crusaders-mantle.md), [hypnotic pattern](/2-Mechanics/CLI/spells/hypnotic-pattern.md)

Griffon: [beast sense](/2-Mechanics/CLI/spells/beast-sense.md) (birds only), [fly](/2-Mechanics/CLI/spells/fly.md)

Sky Pony: [gust of wind](/2-Mechanics/CLI/spells/gust-of-wind.md), [witch bolt](/2-Mechanics/CLI/spells/witch-bolt.md)

Red Tiger: [enhance ability](/2-Mechanics/CLI/spells/enhance-ability.md) (cat's grace only), [jump](/2-Mechanics/CLI/spells/jump.md)

Thunderbeast: [enhance ability](/2-Mechanics/CLI/spells/enhance-ability.md) (bull's strength only), [pass without trace](/2-Mechanics/CLI/spells/pass-without-trace.md)

Tree Ghost: [barkskin](/2-Mechanics/CLI/spells/barkskin.md), [speak with plants](/2-Mechanics/CLI/spells/speak-with-plants.md)

```statblock
"name": "Uthgardt Shaman (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[hide armor](/2-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "38"
"hit_dice": "7d8 + 7"
"stats":
- !!int "14"
- !!int "12"
- !!int "13"
- !!int "10"
- !!int "15"
- !!int "12"
"speed": "30 ft."
"skillsaves":
  "Medicine": !!int "4"
  "Nature": !!int "4"
  "Perception": !!int "4"
  "Survival": !!int "6"
"senses": "passive Perception 14"
"languages": "Bothii, Common"
"cr": "2"
"traits":
- "desc": "The shaman casts one of the following spells, using Wisdom as the spellcasting\
    \ ability (spell save DC 12; +4 to hit with spell attacks):\n\nAt will:\
    \ [dancing lights](/2-Mechanics/CLI/spells/dancing-lights.md), [mage hand](/2-Mechanics/CLI/spells/mage-hand.md),\
    \ [message](/2-Mechanics/CLI/spells/message.md), [thaumaturgy](/2-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1/day each: [augury](/2-Mechanics/CLI/spells/augury.md) (cast as 1 action),\
    \ [bestow curse](/2-Mechanics/CLI/spells/bestow-curse.md), [cordon of arrows](/2-Mechanics/CLI/spells/cordon-of-arrows.md),\
    \ [detect magic](/2-Mechanics/CLI/spells/detect-magic.md), [speak with dead](/2-Mechanics/CLI/spells/speak-with-dead.md),\
    \ [spirit guardians](/2-Mechanics/CLI/spells/spirit-guardians.md)"
  "name": "Spellcasting (Requires a Sacred Bundle)"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
    \ damage if wielded with two hands."
  "name": "Spear"
- "desc": "Ranged Weapon Attack: +3 to hit, range 80/320 ft., one target. Hit:\
    \ 4 (1d6 + 1) piercing damage."
  "name": "Shortbow"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SKT/Uthgardt%20Shaman.webp"
```
^statblock

```encounter-table
name: Uthgardt Shaman
creatures:
 - 1: Uthgardt Shaman
```