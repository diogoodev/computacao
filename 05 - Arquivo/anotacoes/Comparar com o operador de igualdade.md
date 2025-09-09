Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---

Há muitos *operadores de comparação* em JavaScript. *Todos esses operadores retornam um valor boolean*o `true` ou `false`.

```js
O operador mais básico é o operador de igualdade `==`. O operador de igualdade compara dois valores e retorna `true` se eles são equivalentes ou `false` se não são. Observe que o operador de igualdade é diferente do operador de atribuição (`=`), que atribui o valor à direita do operador para uma variável à esquerda.

function equalityTest(myVal) {
  if (myVal == 10) {
    return "Equal";
  }
  return "Not Equal";
}
```

Se `myVal` é igual a `10`, o operador de igualdade retorna `true`, assim o código nas chaves será executado e a função retornará `Equal`. Caso contrário, a função retornará `Not Equal`. Para que o JavaScript possa comparar dois tipos de dados diferentes (por exemplo, `numbers` e `strings`), deve converter um tipo para outro. Isto é conhecido como *coerção de tipo (casting ou type coercion)*. No entanto, uma vez que a faça, você pode comparar os termos da seguinte forma:

```js
1   ==  1  // true
1   ==  2  // false
1   == '1' // true
"3" ==  3  // true
```

---

Adicione o operador de igualdade à linha indicada para que a função retorne a string `Equal` quando `val` for equivalente a `12`.

```js
// Configuração

function testEqual(val) {

if (val == 12) { // Altere esta linha

return "Equal";

}

return "Not Equal";

}

testEqual(10);
```