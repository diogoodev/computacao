Tópico::
Links:: [[Javascript - FCC]]

---
Ao definirmos uma sequência de caracteres podemos iniciar e terminar com uma aspa simples ou dupla. O que acontece **quando precisamos de uma aspa literal:** `"` ou `'`  **dentro de sua string?**

Em JavaScript, você pode escapar uma aspa para que não seja considerada como o fim de uma string ao colocar a barra invertida (`\`) na frente da aspa.

```js
const sampleStr = "Alan said, \"Peter is learning JavaScript\".";
```

Isso sinaliza ao JavaScript que a aspa seguinte não é o fim de uma string, mas que deve aparecer dentro da string. Então, se você fosse imprimir isso no console, você obteria:

```js
Alan said, "Peter is learning JavaScript".
```

outros exemplos

```js
const diogo = "Diogo disse /"estou apredendo muito javascript no FCC/"." 

Diogo disse "estou apredendo muito javascript no FCC".
```