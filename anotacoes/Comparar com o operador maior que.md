Tópico:: #JavaScript 
Links:: [[Javascript - FCC]]

---

O operador maior que (`>`) *compara os valores* de dois números. *Se o número à esquerda for maior que o número à direita*, ele retorna `true`. Caso contrário, ele retorna `false`.

Tal como o operador de igualdade, o operador maior que converterá os tipos de dados de valores enquanto compara.

**Exemplos**

```js
5   >  3  // true
7   > '3' // true
2   >  3  // false
'1' >  9  // false
```

---

Adicione o operador maior que para indicar as linhas indicadas para que as instruções de retorno façam sentido.

```js
function greatherThan(val){
if (val > 100){
return "Over than 100"
}
if (val > 10){
return "Over than 10"
}
return "10 or Under "
}

greatherThan(10)

```