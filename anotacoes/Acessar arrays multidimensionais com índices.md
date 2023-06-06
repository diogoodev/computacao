Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---

Uma maneira de pensar em um array multidimensional é como um _array de arrays_. Quando você usa colchetes para acessar seu array, o primeiro conjunto de colchetes se refere às entradas no array mais exterior (o primeiro nível), e cada par adicional de colchetes refere-se ao próximo nível de entradas interno.

**Exemplo**

```js
const arr = [
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9],
  [[10, 11, 12], 13, 14]
];

const subarray = arr[3];
const nestedSubarray = arr[3][0];
const element = arr[3][0][1];
```

Neste exemplo, `subarray` tem o valor de `[[10, 11, 12], 13, 14]`, `nestedSubarray` tem o valor de `[10, 11, 12]` e `element` tem o valor de `11` .

**Observação:** não deve haver nenhum espaço entre o nome do array e os colchetes como `array [0][0]` e até mesmo `array [0] [0]` não é permitido. Embora JavaScript seja capaz de processar isso corretamente, isso pode confundir outros programadores lendo seu código.

---

Utilizando notação de colchetes, selecione um elemento de `myArray` de forma que `myData` seja igual a `8`.

``` js
const myArray = [
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9],
  [[10, 11, 12], 13, 14]
];

const myData = myArray[2][1]
// acessando o 14
const myData = myArray[3][2]
// acessando o 6
const myData = myArray[1][2]
```