---
NoteIcon: journal
aat-render-enabled: true
fc-category:
  - Event Category 1
fc-display-name: 
sessionstatus:
  - Occured
type: Session Journal
sessionDate: 2000-01-01
players: 2
Status:
  - ⏳
OneLiner: 1 Line Summary
timelines:
  - journal
tags:
  - journal
---

<% await tp.file.move("/5-Session Journals/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewJournal");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Título:");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

# Info 
## Players
- [[Kaia]]
- [[Kirue]]
- [[Roglic]]
- [[Thrash]]

## Quest
```dataview
TABLE WITHOUT ID link(file.name) AS "Quest Name", questStatus AS "Status", questGiver AS "Quest Giver", questLocationObtained AS "Location", questSessionObtained AS "Session", questLootAvail AS "Available Rewards", questLookEarned AS "Acquired Rewards" FROM "2-Campaign" AND #quest WHERE questStatus = "Not Started" SORT link(file.name) ASC

```

# Session Overview

%% I like to keep a quick summary of sessions here. %%

This is what happened! 