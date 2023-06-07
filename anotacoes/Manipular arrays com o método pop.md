Tópico:: #JavaScript 
Links::[[Javascript - FCC]]

---
Outra forma de *alterar os dados em um array* é com a função `.pop()`.

`.pop()` é usado para *remover um valor do final do array*. Nós podemos armazenar esse valor removido atribuindo-o a uma variável. Em outras palavras, `.pop()` remove o último elemento de um array e retorna aquele elemento.

Qualquer tipo de entrada pode ser removida de um array - *numbers, strings e até mesmo arrays aninhados*.

```js
const threeArr = [1, 4, 6];
const oneDown = threeArr.pop();
console.log(oneDown);
console.log(threeArr);
```

O primeiro `console.log` exibirá o valor `6` e o segundo exibirá o valor `[1, 4]`.

---

Use a função `.pop()` para remover o último item de `myArray` e atribuir o valor removido para uma nova variável, `removedFromMyArray`.

```js
const myArray = [["John", 23], ["cat", 2]];
const removedFromMyArray = myArray.pop();
```

Agora um exemplo removendo strings:

```js
const myName = ["D","i","o","g","o"]
const removeStr = myName.pop()
// Removera a letra o.
```