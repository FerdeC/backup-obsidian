```dataview
TABLE WITHOUT ID link(file.name) AS "Character Name", Player, Class, Race, level, Role
from "1-Party/Main Party"
where (Role = "Player") 
where (Status = "Active") 
```

<br> %% this forces a break line into the note %%

```dataview
TABLE WITHOUT ID link(file.name) AS "Character Name", Player, hp, ac, modifier As "Iniciativa", pasperc As "+Arcana"
from "1-Party"
where (Role = "Player") 
where (Status = "Active") 
```

