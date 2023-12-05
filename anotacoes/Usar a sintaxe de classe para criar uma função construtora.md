Tópico::
Links:: #JavaScript 

---


ES6 fornece uma nova sintaxe para criar objetos, usando a palavra-chave class.

No ES5, um objeto pode ser criado definindo uma função `constructor` e usando a palavra-chave `new` para instanciar o objeto.

No ES6, uma declaração de `class` tem um método `constructor`, que é invocado com a palavra-chave `new`. Se o método `constructor` não for explicitamente definido, ele será definido implicitamente sem argumentos.

```js
// Explicit constructor
class SpaceShuttle {
  constructor(targetPlanet) {
    this.targetPlanet = targetPlanet;
  }
  takeOff() {
    console.log("To " + this.targetPlanet + "!");
  }
}

// Implicit constructor 
class Rocket {
  launch() {
    console.log("To the moon!");
  }
}

const zeus = new SpaceShuttle('Jupiter');
// prints To Jupiter! in console
zeus.takeOff();

const atlas = new Rocket();
// prints To the moon! in console
atlas.launch();
```

Deve ser notado que a palavra-chave `class` declara uma nova função, para qual um construtor é adicionado. Esse construtor é invocado quando `new` é chamado na criação de um novo objeto.

**Observação:** UpperCamelCase (observe a primeira letra de cada palavra em maiúsculo) deve ser usado por convenção para nomes de classe no ES6, como em `SpaceShuttle` usado acima.

O método `constructor` é um método especial usado para inicializar um objeto criado com uma classe. Você aprenderá mais sobre isso na seção Programação Orientada a Objetos da Certificação de Algoritmos e Estruturas de Dados JavaScript.

---

Use a palavra-chave `class` e declare o método `constructor` para criar a classe `Vegetable`.

A classe `Vegetable` permite criar um objeto vegetal com a propriedade `name` que é passada ao `constructor`

```js
// Altere apenas o código abaixo desta linha

class Vegetable {

	constructor(name){

		this.name = name

	}

}

  

// Altere apenas o código acima desta linha

  

const carrot = new Vegetable('carrot');

console.log(carrot.name); // Deve exibir 'carrot'

```
