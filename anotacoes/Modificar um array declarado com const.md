Tópico::
Links:: #JavaScript 

---
Variáveis declaradas com `const` têm muitos casos de uso no JavaScript moderno.

Alguns desenvolvedores preferem criar todas suas variáveis usando `const`, a menos que eles saibam que vão precisar reatribuir o valor. Apenas nesse caso, eles usam `let`.

No entanto, é importante entender que objetos (incluindo arrays e funções) atribuídos a uma variável usando `const` ainda são mutáveis. Usar a declaração `const` só impede a reatribuição do identificador (nome) da variável.

```js
const s = [5, 6, 7];
s = [1, 2, 3];
s[2] = 45;
console.log(s);
```

`s = [1, 2, 3]` resultará em um erro. Depois de comentar essa linha, o `console.log` exibirá o valor `[5, 6, 45]`.

Como você pode ver, você pode alterar o objeto `[5, 6, 7]` e a variável `s` ainda apontará para o array alterado `[5, 6, 45]`. Assim como em qualquer outro array, os elementos dentro de `s` também são mutáveis. Mas como `const` foi usado, você não pode usar o identificador da variável `s` para apontar para uma matriz diferente (ou qualquer outro valor) usando o operador de atribuição.

---

Um array é declarado: `const s = [5, 7, 2]`. Modifique o array para `[2, 5, 7]` usando várias atribuições de elementos.

```js
const s = [5, 7, 2];

function editInPlace() {

	// Altere apenas o código abaixo desta linha
	  
	
	// Usar s = [2, 5, 7] seria inválido
	
	s[0] = 2;
	
	s[1] = 5;
	
	s[2] = 7;
	
	// Altere apenas o código acima desta linha

}

editInPlace();
```