Tópico::
Links:: #JavaScript 

---
Uma promessa em JavaScript é exatamente o que parece - você faz a promessa de que vai fazer uma tarefa, geralmente de forma assíncrona. Quando a tarefa é finalizada, ou você cumpriu a promessa ou falhou ao tentar. Por ser uma função construtora, você precisa utilizar a palavra-chave `new` para criar uma `Promise`. Ela recebe uma função, como seu argumento, com dois parâmetros - `resolve` e `reject`. Esses métodos são usados para determinar o resultado da promessa. A sintaxe se assemelha a:

```js
const myPromise = new Promise((resolve, reject) => {

});
```

---

Crie uma nova promessa chamada `makeServerRequest`. No construtor da promessa, passe uma função com os parâmetros `resolve` e `reject`.

```js
const makeServerRequest = new Promise((resolve, reject) => {

})
