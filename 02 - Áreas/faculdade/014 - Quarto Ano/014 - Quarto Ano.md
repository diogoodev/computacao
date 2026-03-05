---
Created: 2024-07-09
---
# Quarto Ano

Links para os semestres do quarto ano do curso

## Semestres
[[014-1-sétimo-semestre | 014-1 Sétimo Semestre]]
[[014-2-oitavo-semestre|014-2 Oitavo Semestre]]

## 📚 Disciplinas do Quarto Ano

```dataview
TABLE WITHOUT ID
  file.link AS "Disciplina",
  professor AS "Professor",
  "**" + dateformat(inicio, "dd/MM") + "** - **" + dateformat(fim, "dd/MM") + "**" AS "Período de Aula",
  exame_final AS "Exame Final"
FROM "02 - Áreas/faculdade" OR "04 - Zettel/Notas Rapidas"
WHERE startswith(file.name, "014-") AND (semestre = 7 OR semestre = 8)
SORT file.name ASC
```

---
tags: [area/faculdade]
 