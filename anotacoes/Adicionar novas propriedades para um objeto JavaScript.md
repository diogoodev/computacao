Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---
Você pode adicionar novas propriedades para um objeto JavaScript existente da mesma forma pela qual você os modificaria.

Aqui está como adicionaríamos uma propriedade `bark` para `ourDog`:

```js
ourDog.bark = "bow-wow";
```

ou

```js
ourDog["bark"] = "bow-wow";
```

Agora, quando acessamos `ourDog.bark`, nós teremos o seu latido, `bow-wow`.

Exemplo:

```js
const ourDog = {
  "name": "Camper",
  "legs": 4,
  "tails": 1,
  "friends": ["everything!"]
};

ourDog.bark = "bow-wow";
```

---

Adicione a propriedade `bark` para `myDog` e defina-a para um som de um cachorro, como "woof". Você pode usar tanto notação de ponto quando de colchetes.

```js
const myDog = {
"name": "Melissa",
"legs": 4,
"tails": 1,
"friends": ["Diogo", "Jenifer"]
};

myDog.bark= ["woof"]

myDog.bark2 = "auau"

myDog["bark3"] = "au"
```