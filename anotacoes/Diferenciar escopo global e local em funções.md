Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---

É possível ter as variáveis local e global com o mesmo nome. Quando você faz isso, *a variável local tem precedência sobre a variável global.*

Neste exemplo:

```js
const someVar = "Hat";

function myFun() {
  const someVar = "Head";
  return someVar;
}
```

A função `myFun` retornará a string `Head` porque a versão local da variável está presente.

---

Adicione uma variável local para a função `myOutfit` para sobrescrever o valor de `outerWear` com a string `sweater`.

```js
const outerWear = "T-shirt"

function myOutfit(){
const outerWear = "Jeans"
retuns outerWear;

}

myOutfit();
```