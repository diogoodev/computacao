Tópico::
Links:: #JavaScript 

---

ES6 adiciona alguns suportes legais para facilmente definir literais de objetos.

Considere o seguinte código:

```js
const getMousePosition = (x, y) => ({
  x: x,
  y: y
});
```

`getMousePosition` é uma função simples que retorna um objeto contendo duas propriedades. ES6 fornece o açúcar sintático para eliminar a redundância de ter de escrever `x: x`. Você pode simplesmente escrever `x` uma vez, e será convertido para `x: x` (ou algo equivalente). Aqui está a mesma função que acima rescrita para usar a nova sintaxe:

```js
const getMousePosition = (x, y) => ({ x, y });
```

---

Use a abreviação de propriedade de objeto com literais de objeto para criar e retornar um objeto com as propriedades `name`, `age` e `gender`.

```js
const createPerson = (name, age, gender) => {

// Altere apenas o código abaixo desta linha

return {

name,

age,

gender

};

// Altere apenas o código acima desta linha

};
```