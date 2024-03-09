**Linguagem**::  #JavaScript 
**Links**::

---

# Código
```js
// 1. Qual é o caso base?
// 2. Qual é a menor quantidade de trabalho que você precisa fazer para se aproximar do caso base?

// função countdown

const countdown = (number) => {

	console.log(number);


	if (number === 0) {

		return;

	} else {

		countdown(number - 1);

	}

};
```