Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---
Em JavaScript, valores `String` são *imutáveis*, o que significa que elas não podem ser alteradas após serem criadas.

Por exemplo, o código a seguir produzirá um erro porque a letra `B` na cadeia de caracteres `Bob` não pode ser alterada para a letra `J`:

```js
let myStr = "Bob";
myStr[0] = "J";
```

Observe que isso _não_ significa que `myStr` não possa ser reatribuída. A única forma de alterar `myStr` seria atribuindo a ela um novo valor, deste modo:

```js
let myStr = "Bob";
myStr = "Job";
```

---

Corrija a atribuição para `myStr` para que contenha o valor `Hello World` (string) usando a abordagem mostrada no exemplo acima.

```js
let myStr ="Jello World"

myStr = "Hello World"  // lembrando que pelo principio da imutabilidade não conseguimos  alterar apenas uma letra de uma string. Precisamos atribuir um novo valor a variavel
```