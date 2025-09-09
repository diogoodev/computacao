
Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---
O operador de desigualdade estrito (`!==`) é o oposto lógico do operador de igualdade estrito. Significa que "não é estritamente igual" e retorna `false` onde a igualdade estrita retornaria `true` e _vice-versa_. O operador de desigualdade estrita não converterá tipos de dados.

**Exemplos**

```js
3 !==  3  // false
3 !== '3' // true
4 !==  3  // true
```

---

Adicione o operador de desigualdade estrita ao comando `if` para que a função retorne a string `Not Equal` quando `val` não é estritamente igual a `17`