---
obsidianUIMode: preview
assa:
---
> [!tip]+ Crear nuevo contenido
> 
> <div style="display: flex; gap: 1em; flex-wrap: wrap;">
> 
> ```meta-bind-button
> label: New Journal Entry
> style: primary
> actions:
>   - type: templaterCreateNote
>     templateFile: "z_Templates/TemplateJournal.md"
>     fileName: NewJournal
> ```
> 
> ```meta-bind-button
> label: New Codex Entry
> style: primary
> actions:
>   - type: templaterCreateNote
>     templateFile: "z_Templates/TemplateCodex.md"
>     fileName: NewCodex
> ```
> 
> ```meta-bind-button
> label: New NPC
> style: primary
> actions:
>   - type: templaterCreateNote
>     templateFile: "z_Templates/TemplateNPC.md"
>     fileName: NewNPC
> ```
> 
> ```meta-bind-button
> label: New City
> style: primary
> actions:
>   - type: templaterCreateNote
>     templateFile: "z_Templates/TemplateCity.md"
>     fileName: NewCity
> ```
> 
> ```meta-bind-button
> label: New Location
> style: primary
> actions:
>   - type: templaterCreateNote
>     templateFile: "z_Templates/TemplateSettlement.md"
>     fileName: NewLocation
> ```
> 
> ```meta-bind-button
> label: New Guild or Group
> style: primary
> actions:
>   - type: templaterCreateNote
>     templateFile: "z_Templates/TemplateGroup.md"
>     fileName: NewGroup
> ```
> 
> ```meta-bind-button
> label: New Magic Item
> style: primary
> actions:
>   - type: templaterCreateNote
>     templateFile: "z_Templates/TemplateMagicItem.md"
>     fileName: NewMagicItem
> ```
> 
> ```meta-bind-button
> label: New Player
> style: primary
> actions:
>   - type: templaterCreateNote
>     templateFile: "z_Templates/TemplatePlayer.md"
>     fileName: NewPlayer
> ```

> `BUTTON[button_quest]`
> 
> </div>


## Afinidades


| Religión   | Favor | Estado      | Favor | 
| ---------- | ----- | ----------- | ----- |
| Ilyareth   | 0     | Varkass     | 0     |
| Nyssara    | 0     | Elkar       | 0     |
| Vharun     | 0     | Vael Torith | 0     |
| Zareth'Kal | 0     | Darran-Kar  | 0     |
|            |       | Aetheryn    | 0     |
|            |       | Seliar      | 0     |
|            |       | Velkaris    | 0     |
|            |       | Myrianor    | 0     |

## Quests

```dataview
TABLE WITHOUT ID link(file.name) AS "Quest Name", questStatus AS "Status", questGiver AS "Quest Giver", questLocationObtained AS "Location", questSessionObtained AS "Session", questLootAvail AS "Available Rewards", questLookEarned AS "Acquired Rewards"
from "2-Campaign" AND #quest SORT link(file.name) ASC

```



# TEST 
## botones old 

```dataview
TABLE WITHOUT ID link(file.name) AS "Character Name", Player, hp, ac, pasperc As "Spells used"
from "1-Party"
where contains(Role, "Player") 
where contains(Status, "Active")
```

```meta-bind-button
label: New Journal Entry
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateJournal.md"
    fileName: NewJournal
```

```meta-bind-button
label: New Codex Entry
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateCodex.md"
    fileName: NewCodex
```

```meta-bind-button
label: New NPC
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateNPC.md"
    fileName: NewNPC
```

```meta-bind-button
label: New City
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateCity.md"
    fileName: NewCity
```

```meta-bind-button
label: New Location
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateSettlement.md"
    fileName: NewLocation
```

```meta-bind-button
label: New Guild or Group
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateGroup.md"
    fileName: NewGroup
```

```meta-bind-button
label: New Magic Item
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplateMagicItem.md"
    fileName: NewMagicItem
```

```meta-bind-button
label: New Player
hidden: false
id: ""
style: primary
actions:
  - type: templaterCreateNote
    templateFile: "z_Templates/TemplatePlayer.md"
    fileName: NewPlayer
```

`BUTTON[button_quest]` 

