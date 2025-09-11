---
tags: [area/english, moc]
alias: [English MOC, MOC Inglês]
---
# 🗺️ MOC: English Studies

Painel de controle central para o aprendizado de inglês. Todos os recursos, anotações e projetos relacionados a este idioma serão organizados e acessados a partir daqui.

---

## 🚀 Painel de Acesso Rápido

> [!multi-column]
>
>> [!todo]+ Tarefas de Inglês
>> ```tasks
>> not done
>> tags include #area/english 
>> sort by priority
>> limit 5
>> ```
>
>> [!note]+ Últimas Anotações
>> ```dataview
>> LIST
>> FROM #recurso AND #area/english 
>> SORT file.mtime DESC
>> LIMIT 5
>> ```
>
>> [!example]+ Palavra do Dia
>> 
>> - Work

---

## 📚 Pilares do Aprendizado

Recursos e anotações por habilidade.

### 🎧 Listening & Speaking
*(Recursos, técnicas e anotações para melhorar a audição e a fala)*

- [[podcast-series-for-english-learners]]
- [[phrasal-verbs-for-meetings]]

### 📖 Reading & Writing
*(Artigos, livros, e dicas para melhorar a leitura e a escrita)*

- [[how-to-write-a-formal-email-in-english]]

### 🧠 Grammar & Vocabulary
*Notas atômicas sobre regras gramaticais e vocabulário.

**Últimas Notas de Vocabulário e Gramática:**
```dataview
TABLE WITHOUT ID
  file.link AS "Tópico",
  conceito AS "Conceito Chave"
FROM #zeta/permanent AND #area/english 
SORT file.mtime DESC
LIMIT 10

```

## 📚 Cursos relacioandos

[[Ingles IFPA]]