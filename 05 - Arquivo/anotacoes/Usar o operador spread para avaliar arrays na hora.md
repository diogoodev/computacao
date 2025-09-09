Tópico::
Links:: #JavaScript 

---

ES6 introduz o operador spread, o qual nos permite expandir arrays e outras expressões no lugar aonde é esperado diversos parâmetros ou elementos.

O código em ES5 abaixo usa `apply()` para calcular o valor máximo de um array:

```js
var arr = [6, 89, 3, 45];
var maximus = Math.max.apply(null, arr);
```

`maximus` teria o valor de `89`.

Tivemos de usar `Math.max.apply(null, arr)` porque `Math.max(arr)` retorna `NaN`. `Math.max()` espera argumentos separados por vírgula, mas não um array. O operador spread torna essa sintaxe muito mais legível e mais fácil de manter.

```js
const arr = [6, 89, 3, 45];
const maximus = Math.max(...arr);
```

`maximus` teria o valor de `89`.

`...arr` retorna um array descompactado. Em outras palavras, ele espalha (spreads) o array. No entanto, o operador spread apenas funciona no local, como em um argumento para uma função ou em um array literal. Por exemplo:

```js
const spreaded = [...arr];
```

No entanto, o código a seguir não funcionará:

```js
const spreaded = ...arr;
```

---

Copie todo o conteúdo de `arr1` em outro array `arr2` usando o operador spread.

```js
const arr1 = ['JAN', 'FEB', 'MAR', 'APR', 'MAY'];

let arr2;

arr2 = [...arr1]; // Altere esta linha
 

console.log(arr2);
```