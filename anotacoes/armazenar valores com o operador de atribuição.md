[[Usar atribuição de desestruturação para atribuir variáveis de objetos aninhados]]Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---
Em JavaScript, você pode armazenar um valor em uma variável com o operador de atribuição (`=`).

```js
myVariable = 5;
```

Isso atribui um valor do tipo `Number` de `5` para `myVariable`.

Se há qualquer cálculo à direita do operador `=`, esses cálculos são executados antes do valor ser atribuído à variável na esquerda do operador.

```js
var myVar;
myVar = 5;
```

Primeiro, esse código cria uma variável chamada `myVar`. Em seguida, o código atribui `5` para `myVar`. Agora, se `myVar` aparece novamente no código, o programa vai tratá-la como se fosse `5`.

---

Atribua o valor `7` para a variável `a`

```js
var a = 7;

```