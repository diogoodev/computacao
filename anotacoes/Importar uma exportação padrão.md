Tópico::
Links:: #JavaScript 

---
No último desafio, você aprendeu sobre `export default` e seus usos. Para importar uma exportação padrão, você precisa usar uma sintaxe diferente de `import`. No exemplo a seguir, `add` é a exportação padrão do arquivo `math_functions.js`. Veja como importá-la:

```js
import add from "./math_functions.js";
```

A sintaxe é diferente em apenas um ponto. O valor importado, `add`, não está rodeado por chaves (`{}`). Aqui, `add` é simplesmente uma palavra qualquer que vai ser usada para identificar a variável sendo exportada do arquivo `math_functions.js`. Você pode usar qualquer nome ao importar algo que foi exportado como padrão.

---

No código a seguir, importe a exportação padrão do arquivo `math_functions.js` encontrado no mesmo diretório do arquivo que foi usado como exemplo. Dê a importação o nome `subtract`


```js
import subtract from "./math_functions.js"

// Altere apenas o código acima desta linha

  

subtract(7,4);

```
