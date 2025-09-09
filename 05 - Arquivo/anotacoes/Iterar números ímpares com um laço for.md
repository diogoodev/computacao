Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---
Laços for não tem de iterar um de cada vez. Ao alterar nossa `final-expression`, nós podemos contar os números pares.

Começaremos em `i = 0` e um laço while `i < 10`. Incrementaremos `i` em 2 a cada iteração com `i += 2`.

```js
const ourArray = [];

for (let i = 0; i < 10; i += 2) {
  ourArray.push(i);
}
```

`ourArray` agora conterá `[0, 2, 4, 6, 8]`. Vamos mudar nossa `initialization` para que possamos contar por números ímpares.

---

Adicione (push) os números ímpares de 9 até 1 para `myArray` usando um laço `for`.
```js
const myArray = [];

for( let i = 1; i < 11; i +=2){
	myArray.push(i);
}
```