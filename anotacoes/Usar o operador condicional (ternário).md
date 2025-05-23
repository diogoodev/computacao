Tópico::
Links:: #JavaScript 

---

O operador condicional, também chamado de operador ternário, pode ser usado como uma expressão if-else de uma linha.

A sintaxe é `a ? b : c`, onde `a` é a condição, `b` é o código executado quando a condição retorna `true` e `c` é o código executado quando a condição retorna `false`.

A função a seguir usa a instrução `if/else` para verificar uma condição:

```js
function findGreater(a, b) {
  if(a > b) {
    return "a is greater";
  }
  else {
    return "b is greater or equal";
  }
}
```

Isto pode ser reescrito usando o operador condicional:

```js
function findGreater(a, b) {
  return a > b ? "a is greater" : "b is greater or equal";
}
```

---

Use o operador condicional na função `checkEqual` para verificar se dois números são iguais ou não. A função deve retornar ou a string `Equal` ou a string `Not Equal`.

```js
function checkEqual(a, b) {

	return a === b ? "Equal" : "Not Equal"

}

checkEqual(1, 2);
```