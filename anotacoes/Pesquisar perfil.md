Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---

Temos um *array de objetos representando pessoas diferentes* nas nossas listas de contatos.

Uma função `lookUpProfile`, que recebe `name` e uma propriedade (`prop`) como argumentos, foi pré-escrita para você.

A função deve *verificar* se `name` é o `firstName` (primeiro nome) de um contato *e se a propriedade passada* (`prop`) é uma propriedade daquele contato.

*Se ambos forem verdadeiros*, então retorne o "valor" daquela propriedade.

Se `name` *não corresponder a nenhum dos contato*s, então retorne a string `No such contact`.

Se `prop` *não corresponder a nenhuma propriedade válida* de um contato encontrado para coincidir com `name` então retorne a string `No such property`.

---

```js
for(let i = 0; i <= contacts.length; i++ ){

	if((name === contacts[i]["firstName"] ) && (contacts[i].hasOwnProperty(prop))){

		return contacts[i][prop]

	}

  }
```

