Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---

Você pode se lembrar de [[Comparação com o operador de igualdade]], em que todos os operadores de comparação retornam um valor booleano `true` ou `false`.

Às vezes, as pessoas usam uma instrução `if/else` para fazer uma comparação, dessa forma:

```js
function isEqual(a, b) {
  if (a === b) {
    return true;
  } else {
    return false;
  }
}
```

Mas há uma forma melhor de fazer isso. Já que `(===)` retorna `true` ou `false`, podemos *retornar o resultado da comparação*:

```js
function isEqual(a, b) {
  return a === b;
}
```

---

Corrija a função `isLess` para remover as instruções `if/else`.

```js 
function isLess(a, b) {

// Altere apenas o código abaixo desta linha

if (a < b) {

return true;

} else {

return false;

}

// Altere apenas o código acima desta linha

}

  

isLess(10, 15);
```

Modo corrigido

```js 
function isLess(a, b){
return a < b;
}

isLess(10, 15)
```