---
obsidianUIMode: preview
EXP: "0"
---


> [!cards|4]
> **[[Eliaran]]**
> ![[Pasted image 20250604195616.png|sban htiny ctr]]
> 
> **[[Journey]]**
> [![[JourneyBoard.png\|sban htiny ctr]]](Journey%20Board)
>
> **[[Greece]]**
> ![[AdventureIcon.png\|sban htiny ctr]]
> 
> **[[Main Party]]**
> [![[PartyLogo.jpg\|sban htiny ctr p+t]]](Main%20Party)

---
> [!infobox]+
> # Session Journals
> ```dataview
TABLE WITHOUT ID link(file.name) AS "Session", Status
from "5-Session Journals"
where (type = "Session Journal")
SORT file.name DESC


```dataview  
TABLE WITHOUT ID link(file.name) AS "Character Name", Player, Class, Race, level,hp, pasperc AS "Arcana"  
from "1-Party"  
where (Role = "Player")  
where (Status = "Active")  
```

# Recently Modified NPCs

```dataview  
TABLE WITHOUT ID link(file.name) AS "NPC Name", Gender, Race, Age, Location, AssociatedGroup  
FROM "3-Mechanics/NPCs"
WHERE (NoteIcon = "npc") 
SORT file.mtime DESC
LIMIT 10
```

# Recently Modified Locations

```dataview  
TABLE WITHOUT ID link(file.name) AS "Location Name", type, Government, Community-Size, size, population  
FROM "2-World"
WHERE (NoteIcon = "settlement")  
SORT file.mtime DESC
LIMIT 10
```


# Recently Modified Notes
```dataview
TABLE WITHOUT ID
    link(file.path, file.folder + " / " + file.name) AS "Note",
    file.mtime AS "Last modified"
FROM "/"
WHERE file.mtime >= date(today) - dur(30 days)
AND file.name != this.file.name
    AND !contains(file.path, "z_Assets")
    AND !contains(file.path, "Inline Scripts")
    AND !contains(file.path, "z_Templates")
    AND !contains(file.path, "daily notes")
    AND !contains(file.path, "BRAT")
SORT file.mtime DESC
LIMIT 10
```


## Non-active characters.
```dataview  
TABLE WITHOUT ID link(file.name) AS "Character Name", Player, Class, Race, level,hp, Role  
from "1-Party"  
where (Role = "Player")  
where (Status = "Inactive")  
```