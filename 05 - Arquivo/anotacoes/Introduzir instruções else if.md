Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---
Se você tem *múltiplas condições que precisam ser resolvidas*, você pode encadear as instruções `if` junto com instruções `else if`.

```js
if (num > 15) {
  return "Bigger than 15";
} else if (num < 5) {
  return "Smaller than 5";
} else {
  return "Between 5 and 15";
}
```

---

Converta a lógica para usar instruções `else if`

```js
function testElseIf(val){
	if(val > 10) {
		return "Maior que dez"
	}else if(val < 5){
		return "Menor que 5"
	}else{
		return "Entre 5 e 10"
	}
}

testElseIf(10);
```