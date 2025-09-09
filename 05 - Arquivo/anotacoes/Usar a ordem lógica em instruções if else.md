Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---

A ordem é importante em instruções `if` e `else if`.

A função é executada de cima para baixo, então você deve ser cuidadoso com qual instrução vem primeiro.

Tomemos como exemplo estas duas funções.

Aqui está a primeira:

```js
function foo(x) {
  if (x < 1) {
    return "Less than one";
  } else if (x < 2) {
    return "Less than two";
  } else {
    return "Greater than or equal to two";
  }
}
```

A segunda apenas altera a ordem das instruções if e else if:

```js
function bar(x) {
  if (x < 2) {
    return "Less than two";
  } else if (x < 1) {
    return "Less than one";
  } else {
    return "Greater than or equal to two";
  }
}
```

Embora as duas funções pareçam praticamente idênticas, se passarmos um número para ambas, teremos saídas diferentes.

```js
foo(0)
bar(0)
```

`foo(0)` retornará a string `Less than one` e `bar(0)` retornará a string `Less than two`.

---

Altere a ordem lógica na função para que retorne as instruções corretas em todos os cenários.

```js
function myLogical(val){
	if(val < 5){
		return "Menor que 5";
	}else if(val < 10){
		return "Menor que 10";
	}else{
		return "Maior que 10";
	}
}

myLogical(5);
```