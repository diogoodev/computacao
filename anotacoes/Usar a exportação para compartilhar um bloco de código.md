Tópico::
Links:: #JavaScript 

---

Imagine um arquivo chamado `math_functions.js` que contém várias funções relacionadas a operações matemáticas. Uma delas é armazenada em uma variável, `add`, que recebe dois números e retorna a soma deles. Você quer usar essa função em diversos arquivos JavaScript diferentes. Para compartilhá-las com esses outros arquivos, você primeiro precisa exportá-las (`export`).

```js
export const add = (x, y) => {
  return x + y;
}
```

Acima está uma forma comum de exportar uma única função, mas você pode alcançar a mesma coisa da seguinte forma:

```js
const add = (x, y) => {
  return x + y;
}

export { add };
```

Quando você exporta uma variável ou função, você pode importá-las em outro arquivo e usá-las sem ter de rescrever o código. Você pode exportar várias coisas ao repetir o primeiro exemplo para cada coisa que você queira exportar, ou ao colocar todas elas em uma instrução de export do segundo exemplo, da seguinte forma:

```js
export { add, subtract };
```

---

Há duas funções relacionadas a string no editor. Exporte ambas usando o método de sua escolha.

```js
const uppercaseString = (string) => {

	return string.toUpperCase();

}
  

const lowercaseString = (string) => {

	return string.toLowerCase()

}


export {uppercaseString, lowercaseString}
