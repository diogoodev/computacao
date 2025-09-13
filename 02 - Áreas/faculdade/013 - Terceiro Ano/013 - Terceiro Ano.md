---
Created: 2024-07-09
sticker: emoji//0033-fe0f-20e3
---
# Terceiro Ano

Links para os semestres do terceiro ano do curso

## Semestres

- [[013-1 Quinto Período]]
- [[013-2 Sexto Período]]
  
  
  
  
---
tags: [area/faculdade]
alias:  
---


---
## 📚 Disciplinas do Módulo II (2º Sem/2025)

 

```dataview
TABLE WITHOUT ID
  file.link AS "Disciplina",
FROM "02 - Áreas/faculdade"
SORT file.name ASC
```

## 🎯 Projetos Ativos do Curso

Projetos criados na pasta para/projects com a tag #area/tecnico aparecerão aqui.

```dataview
TABLE
  status AS "Status",
  due-date AS "Prazo"
FROM #projeto AND #area/faculdade
WHERE status != "Concluído"
SORT due-date ASC
```

