Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---

Podemos usar o mesmo princípio que usamos para recuperar o último caractere em uma string, para recuperar o enésimo caractere antes do último caractere.

Por exemplo, você pode pegar o valor da antepenúltima letra da string :
`const firstName = "Augusta"`
usando 
`firstName[firstName.length - 3]`

Exemplo:

```js
const firstName = "Augusta";
const thirdToLastLetter = firstName[firstName.length - 3];
```

`thirdToLastLetter` teria o valor da string `s`.

---

Use notação de colchetes para descobrir o penúltimo caractere na string `lastName`.

```js
const lastName = "Moura"
const thirdToLastLetter = lastName[lastName.lengh - 3]

// thirdToLastLeeter ='u' 
```