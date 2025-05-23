Tópico::
Links:: #JavaScript 

---

Suponha que você tem um arquivo e deseja importar todo o conteúdo dele no arquivo atual. Isso pode ser feito com a sintaxe `import * as`. Aqui está um exemplo onde todo o conteúdo de um arquivo chamado `math_function.js` é importado em um arquivo no mesmo diretório:

```js
import * as myMathModule from "./math_functions.js";
```

A instrução `import` acima criará um objeto chamado `myMathModule`. Esse nome é totalmente arbitrário. Você pode escolher qualquer outro nome que seja apropriado para sua aplicação. O objeto conterá todas as exportações do arquivo `math_functions.js`. Dessa forma, você pode acessar as funções exportadas da mesma forma que você acessa as propriedades de um objeto. Aqui está um exemplo de como você pode usar as funções `add` e `subtract` que foram importadas:

```js
myMathModule.add(2,3);
myMathModule.subtract(5,3);
```

---

O código nesse desafio requer o conteúdo do arquivo: `string_functions.js`, o qual está no mesmo diretório que o arquivo atual. Use a sintaxe `import * as` para importar tudo do arquivo em um objeto chamado `stringFunctions`.
```js
import * as stringFunctions from './string_functions.js'

// Altere apenas o código acima desta linha

  

stringFunctions.uppercaseString("hello");

stringFunctions.lowercaseString("WORLD!");
```
