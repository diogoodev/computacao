Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---
Você pode não apenas usar **`shift`** *para remover elementos do início* de um array, como também pode usar **`unshift`** *para adicionar elementos ao início* de um array, ou seja, adicionar elementos na posição inicial do array.

`.unshift()` funciona exatamente como `.push()`, mas, ao invés de adicionar o elemento ao final do array, `unshift()` adiciona o elemento no início do array.

Exemplo:

```js
const ourArray = ["Stimpson", "J", "cat"];
ourArray.shift();
ourArray.unshift("Happy");
```

Após o `shift`, `ourArray` teria o valor `["J","cat"]`. Após o `unshift`, `ourArray` teria o valor `["Happy","J","cat"]`.

---

Adicione `["Paul", 35]` ao início da variável `myArray` usando `unshift()`.

```js
const myArray = [["Melissa", 10], "Diogo", 20]
myArray.unshift(["Paul", 35])
```

Outro exemplo

```js
const myArray = [10, 20, 30, 40, 50]
myArray.unshift(0)
// após isso o myArray fica assim:  
// [0, 10, 20, 30, 40, 50]
```