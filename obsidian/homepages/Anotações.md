[[10-dicas-para-se-tornar-ninja-em-javascript]]
[[CONSTRUINDO NA PRÁTICA UM CONTAINER SOMENTE UTILIZANDO OS NAMESPACES!]]
<br/>

```button
name Adicionar nota
type command
action QuickAdd: Adicionar nota
```

<br/>


```dataview 
TABLE rows.file.link as "Título" 
from "anotacoes"
FLATTEN Tópico
Group by Tópico
```
