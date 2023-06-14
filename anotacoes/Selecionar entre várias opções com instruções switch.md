Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---
Se você precisar corresponder um valor a muitas opções, pode usar uma instrução switch. Uma instrução `switch` compara o valor a uma instrução de caso, que define os diversos valores possíveis. Quaisquer instruções JavaScript válidas podem ser executadas dentro de um bloco de caso (case) e serão executadas a partir do primeiro valor de `case` correspondente até que um `break` seja encontrado.

Aqui está um exemplo de uma instrução `switch`:

```js
switch (fruit) {
  case "apple":
    console.log("The fruit is an apple");
    break;
  case "orange":
    console.log("The fruit is an orange");
    break;
}
```

Valores `case` são testados com o operador de igualdade estrita (`===`). O `break` diz ao JavaScript parar interromper a execução das instruções. Se o `break` for omitido, a próxima instrução case será executada.

---

Escreva uma instrução switch que testa `val` e define `answer` para as seguintes condições:  
`1` - `alpha`  
`2` - `beta`  
`3` - `gamma`  
`4` - `delta`