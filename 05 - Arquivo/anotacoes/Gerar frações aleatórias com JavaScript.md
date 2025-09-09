Tópico::
Links:: #JavaScript 

---

Números aleatórios são úteis para criar comportamento aleatório.

JavaScript tem a função `Math.random()` que gera um número decimal aleatório entre `0` (incluso) e `1` (excluso). Assim, `Math.random()` pode retornar um `0` mas nunca retornará `1`.

**Observação:** de modo semelhante ao que usamos ao [[armazenar valores com o operador de atribuição]], todas as chamadas de função serão resolvidas antes da execução da instrução `return`. Assim, poderemos usar a instrução `return` para devolver o valor da função `Math.random()`.

```js
function randomFraction() {

  

// Altere apenas o código abaixo desta linha

  

return Math.random(10);

  

// Altere apenas o código acima desta linha

}
```