---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Howling Hatred Priest"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 190
---
# [Howling Hatred Priest](2-Mechanics\CLI\bestiary\humanoid/howling-hatred-priest-pota.md)
*Source: Princes of the Apocalypse p. 190*  

The most fanatical of the air cultists, the priests push their bodies to physical extremes in order to decrease their density and mass and become as light as leaves. Gaunt and sallow faced, with concave bellies, bulging eyes, and taut skin that enunciates every bone, these living skeletons sustain themselves on nothing more than air and fanatical devotion to the teachings of the cult. The wind serves them at a gesture.

Howling Hatred priests see themselves as living extensions of Yan-C-Bin, and they help new recruits cast off the shackles of their old lives and embrace a "higher purpose." Once the new recruits are thus purified, the priests decide whether they are worthy for indoctrination as initiates or would better serve the Howling Hatred cult as sacrifices. The priests also uphold the doctrine of their prophet, inoth, and harshly punish any initiate who strays from the path.

Most other air cultists hate the priests, though none dares to speak out against them. Those that challenge the priests often end up the subjects of rigorous new attempts at purification.

```statblock
"name": "Howling Hatred Priest (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "[studded leather](/2-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "45"
"hit_dice": "10d8"
"stats":
- !!int "12"
- !!int "16"
- !!int "10"
- !!int "14"
- !!int "10"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "4"
  "Religion": !!int "4"
  "Acrobatics": !!int "5"
"senses": "passive Perception 10"
"languages": "Auran, Common"
"cr": "2"
"traits":
- "desc": "The priest is a 5th-level spellcaster. Its spellcasting ability is Charisma\
    \ (spell save DC 12, +4 to hit with spell attacks). It knows the following sorcerer\
    \ spells:\n\nCantrips (at will): [blade ward](/2-Mechanics/CLI/spells/blade-ward.md),\
    \ [gust](/2-Mechanics/CLI/spells/gust-xge.md), [light](/2-Mechanics/CLI/spells/light.md),\
    \ [prestidigitation](/2-Mechanics/CLI/spells/prestidigitation.md), [shocking grasp](/2-Mechanics/CLI/spells/shocking-grasp.md)\n\
    \n1st level (4 slots): [feather fall](/2-Mechanics/CLI/spells/feather-fall.md),\
    \ [shield](/2-Mechanics/CLI/spells/shield.md), [witch bolt](/2-Mechanics/CLI/spells/witch-bolt.md)\n\
    \n2nd level (3 slots): [dust devil](/2-Mechanics/CLI/spells/dust-devil-xge.md),\
    \ [gust of wind](/2-Mechanics/CLI/spells/gust-of-wind.md)\n\n3rd level (2 slots):\
    \ [gaseous form](/2-Mechanics/CLI/spells/gaseous-form.md)"
  "name": "Spellcasting"
- "desc": "The priest can hold its breath for 30 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "The priest makes two melee attacks or two ranged attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Scimitar"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage."
  "name": "Dagger"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Howling%20Hatred%20Priest.webp"
```
^statblock

```encounter-table
name: Howling Hatred Priest
creatures:
 - 1: Howling Hatred Priest
```