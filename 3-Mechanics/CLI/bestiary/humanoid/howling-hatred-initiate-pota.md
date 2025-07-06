---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/pota
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Howling Hatred Initiate"]
NoteIcon: monster
BestiaryType: humanoid (human)
SourceType: Bestiary
BookSource: Princes of the Apocalypse p. 190
---
# [Howling Hatred Initiate](2-Mechanics\CLI\bestiary\humanoid/howling-hatred-initiate-pota.md)
*Source: Princes of the Apocalypse p. 190*  

Howling Hatred initiates are attracted by the cult's philosophy of non-attachment and the rejection of material things, unaware of the cult's true nature. The cult attracts adherents of all kinds, from dreamy-eyed youths with little property to world-weary folk eager to put their faith in something as tangible and powerful as an elemental force.

Initiates live on little but air for a month, believing that this regimen purifies them of bodily needs. In truth it makes their bodies so desperate for sustenance that they become susceptible to indoctrination. Soon, they can justify heinous acts within the context of the cult: Human sacrifice isn't an act of murder, but a freeing of the soul from the limitations of a physical shell; conjuring a whirlwind to destroy unbelievers isn't an act of terror but a demonstration of true faith.

```statblock
"name": "Howling Hatred Initiate (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "[leather armor](/2-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "10"
- !!int "15"
- !!int "10"
- !!int "10"
- !!int "9"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "2"
  "Stealth": !!int "4"
  "Religion": !!int "2"
"senses": "passive Perception 9"
"languages": "Common"
"cr": "1/8"
"traits":
- "desc": "As a bonus action, the initiate gains advantage on the next ranged attack\
    \ roll it makes before the end of its next turn."
  "name": "Guiding Wind (Recharges after a Short or Long Rest)"
- "desc": "The initiate can hold its breath for 30 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/PotA/Howling%20Hatred%20Initiate.webp"
```
^statblock

```encounter-table
name: Howling Hatred Initiate
creatures:
 - 1: Howling Hatred Initiate
```