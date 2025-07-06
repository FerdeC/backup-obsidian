---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/wbtw
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/dwarf
aliases: ["Elkhorn"]
NoteIcon: monster
BestiaryType: humanoid (dwarf)
SourceType: Bestiary
BookSource: The Wild Beyond the Witchlight p. 224
---
# [Elkhorn](2-Mechanics\CLI\bestiary\npc/elkhorn-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 224*  

Elkhorn has been Strongheart's most stalwart companion over the years—unflinchingly loyal, tirelessly optimistic, and fiercely devoted to the destruction of evil in all its forms. He's not especially bright, so he fights with his heart rather than his wits.

Age has drained much of the strength from Elkhorn's body. Strongheart has urged Elkhorn to retire, but the old dwarf stubbornly refuses to do so.

```statblock
"name": "Elkhorn (WBtW)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Lawful Good"
"ac": !!int "18"
"ac_class": "[chain mail](/2-Mechanics/CLI/items/chain-mail.md), [shield](/2-Mechanics/CLI/items/shield.md)"
"hp": !!int "52"
"hit_dice": "7d8 + 21"
"stats":
- !!int "9"
- !!int "13"
- !!int "16"
- !!int "9"
- !!int "10"
- !!int "11"
"speed": "25 ft."
"saves":
  "Strength": !!int "1"
  "Constitution": !!int "5"
"skillsaves":
  "Perception": !!int "2"
  "Survival": !!int "2"
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Dwarvish"
"cr": "2"
"traits":
- "desc": "Elkhorn wields a [+1 longsword](/2-Mechanics/CLI/items/1-weapon.md)."
  "name": "Special Equipment"
"actions":
- "desc": "Elkhorn makes two Dagger or +1 Longsword attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 3 (1d4 + 1) piercing damage. If the target is a creature\
    \ that is Large or bigger, it takes an extra 5 (1d10) piercing damage."
  "name": "Dagger"
- "desc": "Melee Weapon Attack:  +2 to hit, reach 5 ft., one target. Hit: 4\
    \ (1d8) slashing damage, or 5 (1d10) slashing damage when used with two hands.\
    \ If the target is a creature that is Large or bigger, it takes an extra 5 (1d10)\
    \ slashing damage."
  "name": "+1 Longsword"
"bonus_actions":
- "desc": "Elkhorn targets one creature that he can see within 5 feet of him. Elkhorn\
    \ has advantage on the next attack roll he makes against that target before the\
    \ end of his turn. If that attack hits, the target takes an extra 7 (2d6) damage\
    \ of the weapon's type."
  "name": "Feint (Recharge 5-6)"
- "desc": "Elkhorn regains 12 hit points."
  "name": "Second Wind (Recharges after a Short or Long Rest)"
"source":
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/WBtW/Elkhorn.webp"
```
^statblock

```encounter-table
name: Elkhorn
creatures:
 - 1: Elkhorn
```