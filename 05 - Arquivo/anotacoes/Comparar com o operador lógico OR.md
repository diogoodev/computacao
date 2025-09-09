Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---

O operador lógico OR (`||`) retorna `true` se qualquer um dos operandos for `true`. Caso contrário, retorna `false`.

O operador lógico ou é composto por dois símbolos de pipe: (`||`). Normalmente, ele pode ser encontrado entre as teclas Backspace e Enter.

O padrão abaixo deve parecer familiar a partir de pontos de passagem anteriores.

```js
if (num > 10) {
  return "No";
}
if (num < 5) {
  return "No";
}
return "Yes";
```

O código retornará `Yes` se `num` estiver entre `5` e `10` (`5` e `10` inclusive). A mesma lógica pode ser escrita com o operador lógico OR.

```js
if (num > 10 || num < 5) {
  return "No";
}
return "Yes";
```

---

Combine as duas instruções `if` em uma mesma instrução a qual retorna a string `Outside` se `val` não estiver entre `10` e `20`, inclusos 10 e 20. Caso contrário, retorna a string `Inside`

```js
function testLogicalOr(val){
	
	if(val < 10 || val > 20){
		return "Outside"
}
	
	return "Inside"
}

testLogicalOr(2);
```