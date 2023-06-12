Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---
Às vezes, você precisará testar mais de uma coisa de cada vez. O *operador lógico AND*(`&&`) retornará `true` apenas *se os operadores à esquerda e à direita forem verdadeiros*.

O mesmo efeito pode ser alcançado aninhando uma instrução `if` dentro de outro `if`.

```js
if (num > 5) {
  if (num < 10) {
    return "Yes";
  }
}
return "No";
```

O código retornará `Yes` se `num` for maior que `5` e menor que `10`. A mesma lógica pode ser escrita com o operador lógico AND.

```js
if (num > 5 && num < 10) {
  return "Yes";
}
return "No";
```

---

Substitua as duas instruções if por uma declaração, usando o operador `&&`, que vai retornar a string `Yes` se `val` for menor ou igual a `50` e maior ou igual a `25`. Caso contrário, retornará a string `No`.
```js
function testLogical (val){

	if(val >= 25 && val <= 50){
	return "yes"
	}

return "No"
}

testLogical(50);
```

Outros exemplos

```js 

function testLogical (val1, val2, val3){

	if(val1 >= val2 && val2 <= val3){
	return "yes"
	}

return "No"
}

testLogical(1,2,3);
```