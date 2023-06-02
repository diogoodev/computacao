Tópico::
Links:: [[Javascript - FCC]]

---

Observe que as aspas não são os únicos caracteres que podem ser escapados dentro de uma string. As sequências de escape permitem que **você use caracteres que você não poderia usar** em uma string em outras situações.

|Código|Saída|
|---|---|
|`\'`|aspas simples|
|`\"`|aspas duplas|
|`\\`|barra invertida|
|`\n`|nova linha|
|`\t`|tab|
|`\r`|retorno de carro|
|`\b`|retroceder|
|`\f`|quebra de página|

_Note que a própria zbarra invertida deve ser escapada para ser exibida como uma barra invertida._

alguns exemplos

```js
const myStr = "FirstLine\n\t\\SecondLine\nThirdLine";
const ourStr = " teste \t \\ \' \" \r"
```