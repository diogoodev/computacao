Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---
Assim como podemos construir uma *string em várias linhas através das strings literais*, nós também podemos *adicionar as variáveis* para a string usando o operador mais igual (`+=`).

Exemplo:

```js
const anAdjective = "awesome!";
let ourStr = "freeCodeCamp is ";
ourStr += anAdjective; // a varivel está sendo atualizada, caso inverta e tente atualizar a constante ocorrera o erro TypeError: Assignment to constant variable.
```

`ourStr` teria o valor `freeCodeCamp is awesome!`.

---

Defina `someAdjective` para uma string de pelo menos 3 caracteres e adicione para `myStr` usando o operador `+=`

```js
 const someAdjective = "Incrivel"
 let myStr = "Diogo é "
 myStr += someAdjective
```