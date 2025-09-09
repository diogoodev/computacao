Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---

Quando uma instrução `return` é alcançada, a execução da função atual para e retorna o código para o local da chamada da função.

**Exemplo**

```js
function myFun() {
  console.log("Hello");
  return "World";
  console.log("byebye")
}
myFun();
```

O código acima exibirá no console a string `Hello`, e retorna a string `World`. A string `byebye` nunca vai ser exibida no console, porque a função termina na instrução `return`.

---

Modifique a função `abTest` para que se `a` ou `b` forem menores que `0` a função irá imediatamente terminar retornando o valor de `undefined`.

**Dica**  
Lembre-se de que [`undefined` é uma palavra-chave](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/understanding-uninitialized-variables) e não uma string.

```js 
function abTest(a, b) {


if (a < 0 || b < 0){
return undefined;
}
  
return Math.round(Math.pow(Math.sqrt(a) + Math.sqrt(b), 2));

}

  

abTest(2,2);
```