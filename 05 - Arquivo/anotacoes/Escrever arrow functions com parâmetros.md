Tópico::
Links:: #JavaScript 

---

Assim como uma função normal, você pode passar argumentos para uma arrow function.

```js
const doubler = (item) => item * 2;
doubler(4);
```

`doubler(4)` retornaria o valor `8`.

Se uma arrow function tiver um único parâmetro, os parênteses envolvendo o parâmetro podem ser omitidos.

```js
const doubler = item => item * 2;
```

É possível passar mais de um argumento para uma arrow function.

```js
const multiplier = (item, multi) => item * multi;
multiplier(4, 2);
```

`multiplier(4, 2)` retornaria o valor `8`.

---

Reescreva a função `myConcat` que anexa conteúdo de `arr2` para `arr1` para que a função use sintaxe de arrow function.

---

```js
const myConcat = (arr1, arr2) => arr1.concat(arr2)

myConcat([1,2],[3,4,5])
```