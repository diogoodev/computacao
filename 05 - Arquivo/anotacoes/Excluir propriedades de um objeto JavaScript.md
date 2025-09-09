Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---
Podemos também excluir propriedades de objetos dessa forma:

```js
delete ourDog.bark;
```

Exemplo:

```js
const ourDog = {
  "name": "Camper",
  "legs": 4,
  "tails": 1,
  "friends": ["everything!"],
  "bark": "bow-wow"
};

delete ourDog.bark;
```

Após a última linha mostrada acima, `ourDog` se parece com:

```js
{
  "name": "Camper",
  "legs": 4,
  "tails": 1,
  "friends": ["everything!"]
}
```

---

Exclua a propriedade `tails` de `myDog`. Você pode usar tanto notação de ponto quanto notação de colchetes.



```js 
const myDog ={
"name": "Melissa"
"legs": 4,
"tails": 1,
"friends": ["Diogo", "Jenifer"]
};

delete myDog["tails"];
```

outra forma 

```js
const myDog = {

"name": "Happy Coder",
"legs": 4,
"tails": 1,
"friends": ["freeCodeCamp Campers"],
"bark": "woof"

};
  

delete myDog.tails;
```