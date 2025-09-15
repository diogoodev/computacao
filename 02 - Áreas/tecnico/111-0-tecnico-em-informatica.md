---
tags: [moc, area/tecnico]
alias: ["MOC Curso Técnico", "Técnico IFSuldeMinas", "Técnico em Informatica"]
summary: "Painel de controle central para o Curso Técnico em Informática EaD."
---

# 🗺️  Técnico em Informática  

 Todas as disciplinas, tarefas, projetos e recursos relacionados são gerenciados a partir daqui.

---
## 📚 Disciplinas do Módulo I (2º Sem/2025)


```dataview
TABLE WITHOUT ID
  file.link AS "Disciplina",
  professor AS "Professor",
  ch AS "C.H.",
  "**" + dateformat(inicio, "dd/MM") + "** - **" + dateformat(fim, "dd/MM") + "**" AS "Período de Aula",
  reavaliacao AS "Reavaliação",
  exame_final AS "Exame Final"
FROM "02 - Áreas/tecnico"
WHERE professor
SORT file.name ASC
```

## 🎯 Projetos Ativos do Curso

Projetos criados na pasta para/projects com a tag #area/tecnico aparecerão aqui.

```dataview
TABLE
  status AS "Status",
  due-date AS "Prazo"
FROM #projeto AND #area/tecnico
WHERE status != "Concluído"
SORT due-date ASC
```


## 📜 Documentos Fundamentais do Curso

- [[Matriz_Curricular_-_2023.pdf|Matriz Curricular]]
- [[Resolução_CAMEN_006_2023.pdf|PPC do Curso]]
- [[Cronograma de Execução Curso Técnico em Informática EaD - 2 sem2025 v2.pdf|Cronograma do Curso]]
