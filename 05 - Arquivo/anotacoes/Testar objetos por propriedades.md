Tópico:: #JavaScript 
Links::[[Javascript - FCC]]

---

Para verificar se uma propriedade em um determinado objeto existe ou não, você pode usar o método `.hasOwnProperty()`. `someObject.hasOwnProperty(someProperty)` retorna `true` ou `false`, dependendo de a propriedade ser encontrada no objeto ou não.

**Exemplo**

```js
function checkForProperty(object, property) {
  return object.hasOwnProperty(property);
}

checkForProperty({ top: 'hat', bottom: 'pants' }, 'top'); // true
checkForProperty({ top: 'hat', bottom: 'pants' }, 'middle'); // false
```

A primeira função `checkForProperty` retorna `true`, enquanto a segunda retorna `false`.

---

Modifique a função `checkObj` para testar se um objeto passado para o parâmetro da função `obj` contém a propriedade específica passada para o parâmetro da função `checkProp`. Se a propriedade passada para `checkProp` for encontrada em `obj`, retorne o valor dessa propriedade. Se não, retorne `Not Found`.

```js
function checkObj(obj, checkProp) {

// Altere apenas o código abaixo desta linha

  

if(obj.hasOwnProperty(checkProp)){

return obj[checkProp];

};

return "Not Found";

// Altere apenas o código acima desta linha

}

checkObj({city: "Seatle", whether: "summer"}, "city")

```