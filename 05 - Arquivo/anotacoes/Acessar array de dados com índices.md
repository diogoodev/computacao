Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---
Podemos acessar os dados dentro de arrays usando indexes.

Os índices de um array são escritos na mesma notação com colchetes que as strings usam. Porém, **em vez de especificar um caractere, eles estão especificando um item do array**. Assim como ocorre **com as strings, os arrays usam indexação de base zero**, de forma que o primeiro elemento de um array possui índice `0`. 

**Exemplo**

```js
const array = [50, 60, 70];
console.log(array[0]);
const data = array[1];
```

O `console.log(array[0])` exibirá `50` e `data` terá o valor de `60`.

Crie uma variável chamada `myData` e defina-a como igual ao primeiro valor de `myArray` usando notação de colchetes.

```js
const myArray = ["50", "70", "80"];
const myData = myArray[0]; // "50" ira aparacer no console
```

Agora com números: 

```js
const myArray = [50, 70, 80];
const myData = myArray[0]; // "50" ira aparacer no console
```

