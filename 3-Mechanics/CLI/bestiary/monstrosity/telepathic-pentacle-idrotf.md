---
obsidianUIMode: preview
cssclass: json5e-monster
statblock: inline
tags:
- compendium/src/5e/idrotf
- monster/cr/8
- monster/size/huge
- monster/type/monstrosity
aliases: ["Telepathic Pentacle"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Icewind Dale: Rime of the Frostmaiden p. 244
---
# [Telepathic Pentacle](2-Mechanics\CLI\bestiary\monstrosity/telepathic-pentacle-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 244*  

Months before Ythryn's fall, a circle of mages known as the Telepathic Pentacle tried to fuse their minds together to become a conjoined telepathic force. The procedure went terribly wrong, and their bodies and minds melded into a single monstrosity. Iriolarthas imprisoned the thing in this empty well so that its latent telepathic powers could be tapped by the city's elite. A short obituary is engraved around the lip of the well in Draconic: "Herein lie the immortal remains of the Telepathic Pentacle. Sit, meditate, and learn."

```statblock
"name": "Telepathic Pentacle (IDRotF)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "172"
"hit_dice": "15d12 + 75"
"stats":
- !!int "20"
- !!int "12"
- !!int "20"
- !!int "2"
- !!int "10"
- !!int "7"
"speed": "30 ft., climb 30 ft., swim 30 ft."
"skillsaves":
  "Perception": !!int "6"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": ""
"cr": "8"
"traits":
- "desc": "The Telepathic Pentacle can hold its breath for 1 hour."
  "name": "Hold Breath"
- "desc": "The Telepathic Pentacle has five heads. While it has more than one head,\
    \ the Telepathic Pentacle has advantage on saving throws against being [blinded](/2-Mechanics/CLI/rules/conditions.md#blinded),\
    \ [charmed](/2-Mechanics/CLI/rules/conditions.md#charmed), [deafened](/2-Mechanics/CLI/rules/conditions.md#deafened),\
    \ [frightened](/2-Mechanics/CLI/rules/conditions.md#frightened), [stunned](/2-Mechanics/CLI/rules/conditions.md#stunned),\
    \ and knocked [unconscious](/2-Mechanics/CLI/rules/conditions.md#unconscious).\n\
    \nWhenever the Telepathic Pentacle takes 25 or more damage in a single turn, one\
    \ of its heads dies. If all its heads die, the Telepathic Pentacle dies.\n\nAt\
    \ the end of its turn, it grows two heads for each of its heads that died since\
    \ its last turn, unless it has taken fire damage since its last turn. The Telepathic\
    \ Pentacle regains 10 hit points for each head regrown in this way."
  "name": "Multiple Heads"
- "desc": "For each head the Telepathic Pentacle has beyond one, it gets an extra\
    \ reaction that can be used only for opportunity attacks."
  "name": "Reactive Heads"
- "desc": "While the Telepathic Pentacle sleeps, at least one of its heads is awake."
  "name": "Wakeful"
"actions":
- "desc": "The Telepathic Pentacle makes as many bite attacks as it has heads."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 10\
    \ (1d10 + 5) piercing damage."
  "name": "Bite"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/IDRotF/Telepathic%20Pentacle.webp"
```
^statblock

```encounter-table
name: Telepathic Pentacle
creatures:
 - 1: Telepathic Pentacle
```