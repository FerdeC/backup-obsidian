`BUTTON[button_encounter]`

```dataview
TABLE WITHOUT ID link(file.name) AS "Encuentro", level, tipo, enemigos
from "2-Campaign/Encounters" AND #encounter SORT link(file.name) ASC

```