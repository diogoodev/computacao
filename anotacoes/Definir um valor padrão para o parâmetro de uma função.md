Tópico::
Links:: #JavaScript 

---

Para nos ajudar a criar funções mais flexíveis, a versão ES6 introduziu os parâmetros padrão para funções.

Confira este código:

```js
const greeting = (name = "Anonymous") => "Hello " + name;

console.log(greeting("John"));
console.log(greeting());
```

O console exibirá as strings `Hello John` e `Hello Anonymous`.

O parâmetro padrão é usado quando o argumento não é especificado (ele não é definido). Como você pode ver no exemplo acima, o parâmetro `name` receberá o valor padrão `Anonymous` quando você não fornecer um valor para o parâmetro. Você pode adicionar valores padrão para quantos parâmetros quiser.

---

Modifique a função `increment` adicionando parâmetros padrão para que ela adicione 1 à variável `number` se o parâmetro `value` não for especificado.

```js
const increment = (number, value = 1) = number + value;


increment(1,2);
```