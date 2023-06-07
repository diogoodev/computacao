[[Passar valores para funções com argumentos]]Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---
Em JavaScript, nós podemos dividir nosso código em partes reutilizáveis chamadas de funções.

Aqui está um exemplo de uma função:

```js
function functionName() {
  console.log("Hello World");
}
```

Você pode *chamar ou invocar* essa função ao usar seu nome seguido de parênteses, da seguinte forma: `functionName();` Cada vez que a função é chamada, imprimirá no console a mensagem `Hello World`. *Todo o código entre as chaves será executado toda vez que uma função for chamada*.

---

1. Crie uma função chamada `reusableFunction` que imprime a string `Hi World` no console.
2. Chame a função.

```js 
function reusableFunction(){
console.log("Hello World");
}

reusableFunction();
```