```dataview
TABLE WITHOUT ID link(file.name) AS "Character Name", Player, Class, Race, level, Role
from "1-Party/Other players"
where (Role = "Player") 
where (Status = "Active") 
```