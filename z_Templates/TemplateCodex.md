---
NoteIcon: journal
tags:
  - codex
---

<% await tp.file.move("/4-Codex Entry/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewCodex");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Título");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

# Contenido

placeholder