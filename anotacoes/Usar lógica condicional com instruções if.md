Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---
Instruções `if` são *usadas para tomar decisões no código*. A palavra-chave `if` diz ao JavaScript para executar o código nas chaves sob certas condições, definidas nos parênteses. Essas condições são conhecidas como condições `Boolean` e elas só podem ser `true` ou `false`.

Quando a condição for `true`, o programa executará as instruções dentro das chaves. Quando a condição booleana for `false`, as instruções dentro das chaves não serão executadas.

**Pseudocódigo**

> if (_condição é verdadeira_) {  
> _instrução é executada_  
> }


**Exemplo**

```js
function test (myCondition) {
  if (myCondition) {
    return "It was true";
  }
  return "It was false";
}

test(true);
test(false);
```

`test(true)` retorna a string `It was true` e `test(false)` retorna a string `It was false`.

Quando `test` é chamado com o valor `true`, a instrução `if` avalia `myCondition` para verificar se é `true` ou não. Já que é `true`, a função retorna `It was true`. Quando chamamos `test` com um valor de `false`, `myCondition` _não é_ `true`, a instrução nas chaves não é executada e a função retorna `It was false`.

---

Crie uma instrução `if` dentro da função para retornar `Yes, that was true` se o parâmetro `wasThatTrue` for `true` e retorne `No, that was false` caso contrário.

```js
funtion trueOrFalse(wasThatTrue){
	if(wasThatTrue){
		return "Yes, that was true";
	}
	return "No, that was false";
}
```