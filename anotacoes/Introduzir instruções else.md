Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---
Quando uma condição para uma instrução `if` for verdadeira, o bloco de código seguinte será executado. E quando a condição for falsa? Normalmente, nada aconteceria. Com uma instrução `else`, um bloco de código alternativo pode ser executado.

```js
if (num > 10) { // se o numero for maior que 10
  return "Bigger than 10"; // entra aqui
} else { // se for menor
  return "10 or Less"; //entra aqui
}
```

---

Combine as instruções `if` em uma única instrução `if/else`.

```js
function testELse(val){
	let result = "";
	
	if( val < 5){
		result = "Menor que Cinco";
	}else{
		result = "Maior que cinco";
	}
	return result;
}
```