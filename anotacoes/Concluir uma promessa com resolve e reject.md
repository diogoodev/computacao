Tópico::
Links:: #JavaScript 

---

Uma promessa possui três estados: pendente (`pending`), cumprida (`fulfilled`) e rejeitada (`rejected`). A promessa que você criou no desafio anterior está presa no estado `pending` para sempre porque você não adicionou uma forma de concluir a promessa. Os parâmetros `resolve` e `reject` passados para o argumento da promessa servem para este propósito. `resolve` é utilizado quando a promessa for bem-sucedida, enquanto `reject` é utilizado quando ela falhar. Ambos são métodos que recebem apenas um argumento, como no exemplo abaixo.

```js
const myPromise = new Promise((resolve, reject) => {
  if(condition here) {
    resolve("Promise was fulfilled");
  } else {
    reject("Promise was rejected");
  }
});
```

O exemplo acima usa strings como argumento desses métodos, mas você pode passar qualquer outro tipo de dado. Geralmente, é passado um objeto para esses métodos. Assim você pode acessar as propriedades deste objeto e usá-las em seu site ou em qualquer outro lugar.

---

Adapte a promessa para ambas as situações de sucesso e fracasso. Se `responseFromServer` for `true`, chame o método `resolve` para completar a promessa com sucesso. Passe a string `We got the data` como argumento para o método `resolve`. Se `responseFromServer` for `false`, passe a string `Data not received` como argumento para o método `reject`.

```js
const makeServerRequest = new Promise((resolve, reject) => {

// responseFromServer representa uma resposta de um servidor

let responseFromServer;

  

if(responseFromServer) {

resolve ("We got the data")// Altere esta linha

} else {

reject ("Data not received")// Altere esta linha

}

});
