[[10-dicas-para-se-tornar-ninja-em-javascript]]
<br/>

```button
name Adicionar nota
type command
action QuickAdd: Adicionar nota
```

<br/>


```dataview 
TABLE rows.file.link as "Título" 
from "anotações"
FLATTEN Tópico
Group by Tópico
```
