Tópico::
Links:: #JavaScript 

---

Atribuição de desestruturação é uma sintaxe especial introduzida na ES6, para atribuir nitidamente valores retirados diretamente de um objeto.

Considere o seguinte código ES5:

```js
const user = { name: 'John Doe', age: 34 };

const name = user.name;
const age = user.age;
```

`name` teria o valor da string `John Doe` e `age` teria o número `34`.

Aqui está uma instrução de atribuição equivalente usando a sintaxe de desestruturação ES6:

```js
const { name, age } = user;
```

Novamente, `name` teria o valor da string `John Doe` e `age` teria o número `34`.

Aqui, as variáveis `name` e `age` serão criadas e atribuídas a elas os valores de seus respectivos valores do objeto `user`. Você pode ver que fica muito mais limpo.

Você pode extrair quantos valores do objeto quanto você quer.

---

Substitua as duas atribuições com a atribuição de desestruturação equivalente. Ainda deve ser atribuído às valores `today` e `tomorrow` os valores de `today` e `tomorrow` do objeto `HIGH_TEMPERATURES`.

```js
const HIGH_TEMPERATURES = {

yesterday: 75,

today: 77,

tomorrow: 80

};

  

// Altere apenas o código abaixo desta linha

  

const { today, tomorrow } = HIGH_TEMPERATURES;

  

// Altere apenas o código acima desta linha

```