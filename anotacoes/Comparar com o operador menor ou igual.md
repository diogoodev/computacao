Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---

O operador menor ou igual (`<=`) compara os valores de dois números. *Se o número à esquerda for menor ou igual ao número à direita*, retornará `true`. Se o número à esquerda for maior que o número a direita, retornará `false`. Assim como o operador de igualdade, o operador de menor ou igual que converte os tipos de dados.

**Exemplos**

```js
4   <= 5 // true
'7' <= 7 // true
5   <= 5 // true
3   <= 2 // false
'8' <= 4 // false
```

---

Adicione o operador menor ou igual que para indicar as linhas para que as instruções de retorno façam sentido.

```js
function testLessOrEqual(val){
	if (val <= 12){
	return "Smaller or Equal to 12"
	}
	
	if(val <= 24){
	return "Smaller or Equal 24"
	}
	
	return "Over 24"
}

testLessOrEqual(24);
```