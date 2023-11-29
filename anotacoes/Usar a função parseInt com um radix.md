Tópico::
Links:: #JavaScript 

---

A função `parseInt()` analisa uma string e retorna um inteiro. É preciso um segundo argumento para o radix, que especifica a base do número na string. O radix pode ser um inteiro entre 2 e 36.

A chamada da função se parece com:

```js
parseInt(string, radix);
```

Exemplo:

```js
const a = parseInt("11", 2);
```

A variável radix diz que `11` está no sistema binário, ou base 2. Esse exemplo converte a string `11` para um inteiro `3`.

Obs:  Caso a base não seja informada, o JavaScript vai assumir que:
	Se a string começa com “0x”, a base é 16 (hexadecimal);
	Se a string começa com qualquer outro valor, a base é 10 (decimal);
	Se a string começa com um caractere que não pode ser convertido em número, a função irá retornar NaN (Not a Number).

---

Use `parseInt()` na função `convertToInteger` para que ela converta um número binário em um inteiro e o retorne.

```js
function convertToInteger(str) {

	return parseInt(str, 2)

}

  
convertToInteger("10011");
```