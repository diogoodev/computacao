Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---

Na Ciência da Computação, uma *fila é* uma estrutura de dados abstrata *onde itens são mantidos em ordem.* Novos itens podem ser adicionados no final da fila e itens mais antigos são removidos do início da fila.

---

Escreva a função `nextInLine`, que recebe um array (`arr`) e um número (`item`) como argumentos.

Adicione o número no final do array e então remova o primeiro elemento do array.

A função `nextInLine` deve, em seguida, retornar o elemento que foi removido.

```js
const arr = [1,2,3,4,5]
const item = 1
function nextInline(arr, item){
arr.push(item)
item = arr.shift();
return item;
}

nextInlline([1,2,3,4], 9)
```