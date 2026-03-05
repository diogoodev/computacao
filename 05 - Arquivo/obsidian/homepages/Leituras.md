<br>

```button
name Adicionar novo livro
type command
action QuickAdd: Adicionar livro
```

<br>
<br>

```dataview 
TABLE WITHOUT ID 
  ("![coverimg|100](" + Capa + ")") AS Capa, 
  file.link AS Título, 
  Autor, 
  Status, 
  (Páginas + " p.") AS Páginas, 
  Nota, 
  ("![progresso](" + "https://progress-bar.dev/" + (round((default(páginasLidas, 0)/Páginas)*100)) + "/)") AS Progresso
FROM "05 - Arquivo/obsidian/livros" 
SORT file.name ASC
```