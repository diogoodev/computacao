Tópico::
Links:: [[Javascript - FCC]]

---
É comum usarmos atribuições para modificar o conteúdo de uma variável. Lembre-se de que tudo à direita do sinal de igual é avaliado primeiro, para que possamos dizer:

```js
myVar = myVar + 5;
```

para adicionar `5` a `myVar`. Como este é um padrão tão comum, existem operadores que realizam uma operação matemática e atribuição em um passo.

Um desses operadores é o operador `+=`.

```js
let myVar = 1;
myVar += 5;
console.log(myVar);
```

`6` seria exibido no console.

Outros exemplos

```js
let diogo = 26;
diogo += 1;
console.log(diogo); // exibira 27

let jenifer = 24;
jenifer += 5;
console.log(jenifer)// exibira 29

```