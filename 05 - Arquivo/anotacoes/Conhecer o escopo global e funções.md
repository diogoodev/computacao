[[Conhecer o escopo local e funções]]Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---

Em JavaScript, *escopo refere-se à visibilidade de variáveis*. Variáveis que são definidas fora de um bloco de função tem o escopo Global. Isso significa que elas podem ser vistas em qualquer lugar no seu código JavaScript.

Variáveis que são declaradas sem a palavra-chave `let` ou `const` são automaticamente criadas no escopo `global`. Isso pode criar consequências indesejadas em outro lugar no seu código ou quando executar uma função novamente. Você sempre deve declarar suas variáveis com `let` ou `const`.

---

Usando `let` ou `const`, declare uma variável global chamada `myGlobal` fora de qualquer função. Inicialize-a com o valor de `10`.

Dentro da função `fun1`, atribua `5` para `oopsGlobal` _**sem**_ usar as palavras-chave `var`, `let` ou `const`.

```js
let myGlobal = 10; // Uma varivel de escopo global é visivel para todo o nosso codigo.

function fun1(){
oopsGlobal = 5;
// ao delacrarmos uma variavel sem tipala dentro de uma função essa varivel se torna global, o que pode ocasionar muitos erros.
}

```