Tópico::
Links::

---

Em JavaScript, uma classe é como um modelo para a criação de objetos. Ele permite definir um conjunto de propriedades e métodos e instanciar (ou criar) novos objetos com essas propriedades e métodos.

A palavra-chave `class` é usada para declarar uma classe.

exemplo:

`class ShoppingCart {};`

As classes possuem um método `constructor` especial, que é chamado quando uma nova instância da classe é criada. O método `constructor` é um ótimo lugar para inicializar propriedades da classe. Aqui está um exemplo de classe com um método `constructor` :

```js
class ShoppingCart {
  constructor() {
  }
}
```

A palavra-chave this em JavaScript é usada para se referir ao objeto atual. Dependendo de onde this é usado, o que ele faz referência muda. No caso de uma classe, refere-se à instância do objeto que está sendo construído. Você pode usar a palavra-chave this para definir as propriedades do objeto que está sendo instanciado. Aqui está um exemplo:


```js
class ShoppingCart {
  constructor() {
    this.items = []
    this.total = 0
    this.taxRate = 8.25
  }
};
```

Sua classe `ShoppingCart` precisa da capacidade de adicionar itens. Crie um método `addItem` vazio, que usa dois parâmetros: `id` e `products` . A criação de um método pode ser assim:

```js
class ShoppingCart {
  constructor() {
    this.items = [];
    this.total = 0;
    this.taxRate = 8.25;
  }
  addItem(id, products){
    
  }

};
```

O primeiro parâmetro, `id` , é o `id` do produto que o usuário adicionou ao carrinho. O segundo parâmetro, `products` , é uma matriz de objetos de produto. Ao usar um parâmetro em vez de fazer referência direta ao array `products` existente, esse método será mais flexível se você quiser adicionar listas de produtos adicionais no futuro.