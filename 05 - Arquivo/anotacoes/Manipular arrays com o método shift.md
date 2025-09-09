Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---

`pop()` sempre remove o último elemento de um array. E se você quiser remover o primeiro?

É aí que o `.shift()` vem a ser útil. Ele funciona da mesma forma que `.pop()`, exceto que ele remove o primeiro elemento ao invés do último.

Exemplo:

```js
const ourArray = ["Stimpson", "J", ["cat"]];
const removedFromOurArray = ourArray.shift();
```

`removedFromOurArray` teria o valor da string `Stimpson` e `ourArray` teria o valor de `["J", ["cat"]]`.

---

Use a função `.shift()` para remover o primeiro item de `myArray` e atribuir o valor removido para uma nova variável, `removedFromMyArray`.

```js
const myArray = [["Diogo", 23], ["Melissa", 10]]
const removeFromMyArray = myArray.shift();
```

Outro exemplo

```js
const myArray = ["Cafe", "Biscoito", "leite", ["Maçã"]]
const removedFromMyArray = myArray.shift();
```