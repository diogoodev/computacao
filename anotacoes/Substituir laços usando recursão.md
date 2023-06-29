Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---
Recursão é o conceito de que uma função pode ser chamada por ela mesma. Para ajudar a entender isso, comece a pensar sobre a seguinte tarefa: multiplique os primeiros `n` elementos de um array para criar o produto desses elementos. Usando um laço `for`, você poderia fazer isso:

```js
  function multiply(arr, n) {
    let product = 1;
    for (let i = 0; i < n; i++) {
      product *= arr[i];
    }
    return product;
  }
```

No entanto, note que `multiply(arr, n) == multiply(arr, n - 1) * arr[n - 1]`. Isso significa que você pode reescrever `multiply` dentro da própria função e nunca precisar usar um laço.

```js
  function multiply(arr, n) {
    if (n <= 0) {
      return 1;
    } else {
      return multiply(arr, n - 1) * arr[n - 1];
    }
  }
```

A versão recursiva de `multiply` fica dessa forma. No caso de base, onde `n <= 0`, ele retorna 1. *Para valores maiores de n, a função chama a si mesma,* mas com `n - 1`. Essa chamada da função é avaliada da mesma forma, chamando `multiply` novamente até que `n <= 0`. Nesse ponto, todas as funções podem retornar e a função `multiply` original retorna a resposta.

**Observação:** funções recursivas *precisam ter um caso de base quando elas retornam sem chamar a função novamente* (nesse exemplo, quando `n <= 0`), caso contrário, elas nunca vão parar de executar.

---

Escreva uma função recursiva, `sum(arr, n)`, que retorna a soma dos primeiros `n` elementos de um array `arr`.

```js
function sum(arr, n){
	if(n <=0 ){
		return 0;
	}else{
		return sum(arr, [n-1]) + arr[n-1]
	}
}

sum([1,2,3], 2)
```

Exercícios sobre recurção

1. Soma de Números: Escreva uma função recursiva que recebe um número inteiro positivo `n` e retorna a soma de todos os números inteiros de 1 a `n`.

  ```js
function sum(n){
	if(n <= 0){
		return 0;
	}else{
		return sum(n-1) + n
	}
}

sum(3) // retorna 6  ou seja 3 + 2 +1

sum(4) // retorma 10 ou seja 4 + 3 + 2 + 1
```
2. Fatorial: Escreva uma função recursiva que recebe um número inteiro positivo `n` e retorna o fatorial desse número. O fatorial de um número é o produto de todos os números inteiros positivos de 1 a `n`.
      ```js
// Fatorial
function fatorial(n){
	if(n <= 0){
		return 0;
	}else{
		return fatorial(n-1) * n
	}
}
```
3. Fibonacci: Escreva uma função recursiva que recebe um número inteiro `n` e retorna o `n`-ésimo número na sequência de Fibonacci. A sequência de Fibonacci é uma sequência em que cada número é a soma dos dois números anteriores na sequência, começando com 0 e 1.
      ```js
function fibonacci(n){

	if(n === 0) {
		return 0;
  }else if(n === 1) {
		return 1;
	}else{   							

		return fibonacci(n-1) + fibonacci(n-2)
	}
}

fibonacci(5)
```
4. Contagem Regressiva: Escreva uma função recursiva que recebe um número inteiro positivo `n` e imprime os números de `n` até 1 em ordem decrescente.
      ```js

```
5. Potência: Escreva uma função recursiva que recebe dois números inteiros `base` e `expoente` e retorna a potência de `base` elevada a `expoente`.
	  ```js

```
