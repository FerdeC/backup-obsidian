---
AssociatedGroup: 
Gender: Female
Race:
  - Humano
Age: "93"
Class:
  - Commoner
Alignment: Chaotic Evil
Character-Role: Anciana / Espíritu maligno
Location: Depende de quest
NoteIcon: npc
Vitality: Deceased
tags:
  - npc
---



> [!infobox]
> # `=this.file.name`
> ![[Pasted image 20250605232121.png|cover hsmall]]
> [[Pasted image 20250605232121.png|Show To Players]]
> ###### Basic Information
> Type |  Stat |
> ---|---|
> Home | `=this.Location` |
> Group | `=this.AssociatedGroup` |
> Sex | `=this.gender` |
> Race | `=this.race` |
> Age | `=this.age` |
> Condition | `=this.vitality`|
> ###### Rules Info
> Type |  Stat |
> ---|---|
> Alignment | `=this.alignment` |
> Class | `=this.class` |
> Character Role | `=this.character-role` |

# `=this.file.name`
## Profile
**Armelia Serenval** es una anciana humana de 93 años, baja de estatura y de figura redondeada, siempre envuelta en chales de lana y con un andar pausado que no inspira sospecha. Sus mejillas sonrosadas y su risa suave la convierten en una figura querida por algunos pobladores, especialmente por los niños, a quienes suele contar historias al atardecer. Sin embargo, cuando cae la noche, una presencia espectral recorre las cercanías: una **Wight** de lamento desgarrador y mirada vacía. Nadie sospecha que bajo su rostro amable se oculta un alma condenada, atrapada entre la vida y la muerte por una culpa que se niega a confesar.

> [!info] Statblock
> ```statblock
> name: Armelia Serenval
> monster: Wight
> columns: 1
> ```

```encounter-table
name: Armelia Serenval
creatures:
 - 1: Wight
```

