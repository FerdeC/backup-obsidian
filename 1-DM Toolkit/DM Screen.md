---
obsidianUIMode: preview
assa: 
favor1:: "1"
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


## Tabla de Inestabilidad Mágica (D100)

Tira un d100 cada vez que se lance un hechizo en este reino inestable.

|Tirada (d100)|Efecto de Inestabilidad Mágica|Gasta Slot|Notas / Consecuencias|
|---|---|---|---|
|**1**|**Cataclismo Arcano (Daño Total y al Doble a Todos)**|Sí|El hechizo tiene su **efecto intensificado al máximo**. El daño total se maximiza y se multiplica por **dos a todas las criaturas** en el área o alcance, sin distinción de aliados o enemigos. El lanzador sufre 2d10 de daño psíquico.|
|2-5|**Flujo Inverso**|Sí|El hechizo falla; lanzador sufre el efecto completo del hechizo (daño máximo, control, etc.).|
|6-10|**Drenaje Vital**|Sí|Hechizo exitoso; lanzador sufre 1d4 daño necrótico por nivel del hechizo.|
|11-15|**Eco de Poder**|Sí|Hechizo exitoso; puede relanzarse gratis en el siguiente turno (acción de bonificación o normal).|
|16-20|**Enemigo Común**|Sí|Hechizo afecta a todas las criaturas en el área/alcance (aliados y enemigos). Lanzador CD 15 Carisma o también afectado.|
|21-25|**Explosión Focalizada**|Sí|Hechizo de un solo objetivo impacta a todos los enemigos en 10 pies del objetivo original.|
|26-30|**Toque Fantasma**|Sí|Poder del hechizo reducido a la mitad (daño, duración, CD salvación -2).|
|31-35|**Vínculo Impredecible**|Sí|Objetivo del hechizo cambia aleatoriamente a otro dentro del alcance.|
|36-40|**Esplendor Efímero**|Sí|Funciona normal; ráfaga de luz/sonido inofensivo y colorido (1d4 asaltos). Estético.|
|41-45|**Normal**|Sí|Funciona normal.|
|46-50|**Cambio Cromático**|Sí|Funciona normal; color de energía/efecto cambia aleatoriamente. Estético.|
|51-55|**Cansancio Arcano**|Sí|Funciona normal; lanzador sufre 1d4 agotamiento temporal por nivel de hechizo.|
|56-60|**Normal**|Sí|Funciona normal.|
|61-65|**Rebote Mínimo**|Sí|Funciona normal; lanzador recibe 1d4 daño de fuerza mágica.|
|66-70|**Sin Costo**|No|Hechizo funciona normal.|
|71-75|**Resonancia Mágica**|Sí|Funciona normal; CD del siguiente hechizo del lanzador aumenta en +3 (1d4 asaltos).|
|76-80|**Normal**|Sí|Funciona normal.|
|81-85|**Doble o Nada**|Sí|Si objetivo falla salvación, doble daño/efecto. Si supera, mitad de daño/efecto.|
|86-90|**Sacrificio de Esencia**|Sí|Funciona normal; lanzador recibe 1d6 daño necrótico o aliado cercano 1d4 daño fuerza.|
|91-95|**Golpe Errante**|Sí|Funciona normal; lanzador recibe 1d4 daño del mismo tipo de hechizo.|
|96-99|**Potencia Inesperada**|No|Hechizo potenciado al máximo; daño total x 2.|
|**100**|**Milagro Arcano**|No|Hechizo potenciado al máximo; **daño total x 3 a TODOS los enemigos** en alcance/área.|

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

