Tópico::  #estrutura_de_dados #algoritmos_de_seleção
Links::

---

 bubble sort: Começa no início do array e 'aumenta'/"bubbles up" valores não classificados no final, iterando pelo array até que esteja completamente classificado.

Como você precisa comparar elementos, precisará usar um loop `for` aninhado. Este loop deve percorrer todos os elementos da matriz, exceto o último. Use `j` como variável iteradora do seu loop interno.

Para obter o resultado de "bubble up", você precisa verificar se o elemento atual é maior que o próximo elemento. Você pode fazer isso acessando `array` em `j` e `j+1` .

exemplo:

```js
const bubbleSort = (array) => {

	for (let i = 0; i < array.length; i++) {

		for (let j = 0; j < array.length - 1; j++) {

  

			if (array[j] > array[j + 1]) {

				const temp = array[j];

				array[j] = array[j + 1];

				array[j + 1] = temp;

			}
	
		}

	}

  

return array;

}
```