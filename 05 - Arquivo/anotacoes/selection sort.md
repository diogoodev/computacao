Tópico:: #estrutura_de_dados #algoritmos_de_seleção 
Links::

---
Uma algoritmo de selection sort funciona encontrando o menor valor na matriz e, em seguida, trocando-o pelo primeiro valor da matriz. Em seguida, ele encontra o próximo menor valor na matriz e o troca pelo segundo valor na matriz. Ele continua iterando pelo array até que esteja completamente classificado.

Uma classificação por seleção depende do rastreamento do índice do menor valor na matriz. Declare uma variável `minIndex` e defina-a como `i` - isso garante que se o seu valor atual for o menor, ele será trocado consigo mesmo e não será movido. Você precisará reatribuir o valor de `minIndex` à medida que itera pela matriz.

exemplo:

```js
const selectionSort = (array) => {

	for (let i = 0; i < array.length; i++) {

		let minIndex = i;

  

		for (let j = i + 1; j < array.length; j++) {

			console.log(array, array[j], array[minIndex]);

			if (array[j] < array[minIndex]) {

				minIndex = j;

			}

}

  

	const temp = array[i];

	array[i] = array[minIndex];

	array[minIndex] = temp;

}

  

return array;

}
```