Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---

Notação de colchetes é uma forma de pegar um caractere no *índice especificado* dentro de uma *string*.

A maioria das linguagens de programação modernas, como JavaScript, não *começa contando* do 1 como humanos fazem. *Elas começam no 0*.Isso é referido como indexação baseada em zero.

Por exemplo, o caractere no índice 0 da palavra `Charles` é `C`. Então, se `const firstName = "Charles"`, você pode *pegar o valor da primeira letra da string* usando `firstName[0]`.

Exemplo:

```js
const firstName = "Charles";
const firstLetter = firstName[0];
```

`firstLetter` teria o valor da string `C`.

---

Use notação de colchetes para encontrar o primeiro caractere na variável `lastName` e atribua a letra para a variável `firstLetterOfLastName`.

```js
let lastName = "Rodrigues"
let firstLetterOfLastName = lastname[0]
```

Outro exemplo: Pegar a ultima letra de uma palavra

```js
// Pegar a ultima letra de uma palavra
const lastName = "Oliveira"
const lastLetter = lastName[lastName.legth - 1] 
```