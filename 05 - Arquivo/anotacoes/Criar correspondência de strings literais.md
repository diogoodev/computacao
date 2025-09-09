Tópico::
Links:: #JavaScript 

---

No desafio anterior, você usou a expressão regular `/Hello/` para procurar a palavra `Hello`. Esta regex buscou a string `Hello` literalmente. No exemplo abaixo há outra busca literal, dessa vez pela string `Kevin`:

```js
let testStr = "Hello, my name is Kevin.";
let testRegex = /Kevin/;
testRegex.test(testStr);
```

Essa chamada a `test` retornará `true`.

Qualquer outra forma de escrever `Kevin` não funcionará. Por exemplo, a regex `/Kevin/` não encontrará nem `kevin` e nem `KEVIN`.

```js
let wrongRegex = /kevin/;
wrongRegex.test(testStr);
```

`test` retornará `false`.

Você verá como encontrar estas outras formas em alguns desafios futuros.

---

Complete a regex `waldoRegex` para encontrar `"Waldo"` na string `waldoIsHiding` de forma literal.

```js
let waldoIsHiding = "Somewhere Waldo is hiding in this text.";

let waldoRegex = /Waldo/; // Altere esta linha

let result = waldoRegex.test(waldoIsHiding);
