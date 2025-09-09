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

// Representação visual completa:

Chamada inicial: countDownAndUp(3)
    3
    Condição base não satisfeita
        Chamada recursiva: countDownAndUp(2)
            2
            Condição base não satisfeita
                Chamada recursiva: countDownAndUp(1)
                    1
                    Condição base não satisfeita
                        Chamada recursiva: countDownAndUp(0)
                            0
                            Condição base satisfeita
                            Retorno da recursão
                        Retorno da recursão
                    1
                    Retorno da recursão
                Retorno da recursão
            2
            Retorno da recursão
        Retorno da recursão
    3
    Fim da execução

Call Stack:
    countDownAndUp(3)
    countDownAndUp(2)
    countDownAndUp(1)
    countDownAndUp(0)

```