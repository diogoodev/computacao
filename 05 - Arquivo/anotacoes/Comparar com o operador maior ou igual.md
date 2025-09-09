Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---

O operador maior ou igual que (`>=`) compara os valores de dois números. *Se o número à esquerda é maior ou igual ao número à direita*, ele retorna `true`. Caso contrário, ele retornará `false`.

Tal como o operador de igualdade, o operador maior que *converterá os tipos de dados* de valores enquanto compara.

**Exemplos**

```js
6   >=  6  // true
7   >= '3' // true
2   >=  3  // false
'7' >=  9  // false
```

---

Adicione o operador maior ou igual que às linhas indicadas para que as instruções de retorno façam sentido.

```JS
function testGreatherOrEqual(val){
	if (val >= 20){
	return "20 or over"
	}
	
	if (val >= 10){
	return "10 or over"
	}
	
	return "Less than 10"
}

testGreatherOrEqual(10);
```