Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---
Uma forma fácil de *adicionar dados no final de um array* é através da função `push()`.

`.push()` recebe um ou mais parâmetros e "empurra" eles no final do array.

Exemplos:

```js
const arr1 = [1, 2, 3];
arr1.push(4);

const arr2 = ["Stimpson", "J", "cat"];
arr2.push(["happy", "joy"]);
```

`arr1` agora tem o valor de `[1, 2, 3, 4]` e `arr2` tem o valor de `["Stimpson", "J", "cat", ["happy", "joy"]]`.

---

Empurre `["dog", 3]` para o final da variável `myArray`.

```js
const myArray = ["cat", 1 , "hourse", 2];
myArray.push("dog", 3)
// aqui temos 1 array com 6 elementos apos o push

//outro exemplo

const myArray = [["Diogo", 27], ["Jenifer", 24]]
myArray.push(["Melissa", 0.1])
// aqui temos 3 arrays, cada array contém 2 elementos.

```
