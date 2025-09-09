Tópico::
Links:: [[Programação de Computadores - PC]]

---
## Vídeos

- **AULA 2 - PARTE 1**: [Link do vídeo - Parte 1](https://drive.google.com/file/d/1BF6_9DKxquiXHtT_CCNn87CdORSlB3uc/view?usp=sharing)
- **AULA 2 - PARTE 2**: [Link do vídeo - Parte 2](https://drive.google.com/file/d/1HDGTPdG25yYLY4ZWC8WNERPZ_dPyi_W2/view?usp=sharing)

- **AULA 2 - Material de Leitura e Lista de Exercícios**
- Slides - Aula 2 [Slides - Aula 2](Aula2_ConstanteseVariaveis.pptx.pdf)
- [Lista de Exercícios](Capitulo2-ProgramacaodeComputadores-EAD.pdf)

- Extras
  - [Variáveis em Python](https://www.youtube.com/watch?v=ii4tVqL49wY)
  - [VARIÁVEIS E CONSTANTES EM PYTHON](https://www.youtube.com/watch?v=wzoyul4z4kw)

## Atividades

- [📅]Avaliação Semanal 02 (12 a 20/08)  
- 
  ### Resumo
O Python oferece um conjunto abrangente de funções auxiliares para cálculo com números de ponto flutuante, e elas estão agrupadas no módulo de matemática (math). Para utilizar esse módulo, é necessário importá-lo no início do programa utilizando a instrução import math. Por exemplo, se desejamos encontrar o valor máximo inteiro para um número x, ou seja, o menor inteiro não menor que x, podemos chamar a função adequada do módulo de matemática:

```python
math.ceil(x).
```

A sintaxe para chamar funções de módulos é sempre a mesma: nome_do_módulo.nome_da_função(argumento_1, argumento_2, ...)

Outra forma de utilizar as funções dos módulos é importá-las individualmente, atribuindo-lhes um nome específico:
```Python
from math import ceil, sqrt
```

Dessa forma, podemos utilizar diretamente as funções ceil e sqrt sem precisar referenciar o módulo.

#### Expressões Lógicas
As expressões lógicas desempenham um papel importante na programação, permitindo que avaliemos condições e tomemos decisões com base em seus resultados. Vamos explorar alguns exemplos práticos que ilustram a utilização dos operadores lógicos e a combinação de expressões lógicas em Python.

**Operadores Lógicos:**
```python 
a = 5
b = 3
c = 7
resultado = (a > b) and (b < c)
print("Resultado da expressão 'and':", resultado) 
# Resultado:
True
```
Operador "and" (e): retorna True se ambas as expressões forem verdadeiras, caso contrário, retorna False


Operador "or" (ou): retorna True se pelo menos uma das expressões for verdadeira, caso contrário, retorna False.
```python
a = 5
b = 3
resultado = not (a == b)
print("Resultado da expressão 'not':", resultado)
# Resultado: True
```


Operador "not" (não): inverte o valor de uma expressão lógica, retornando True se a expressão for falsa e False se a expressão for verdadeira.
```python
a = 5
b = 3
resultado = not (a == b)
print("Resultado da expressão 'not':", resultado) 
# Resultado: True
```

**Combinação de Expressões Lógicas:**
É possível combinar expressões lógicas utilizando parênteses e operadores de comparação, como 
```
igual a(==), 
diferente de (!=), 
maior que (>), 
menor que (<), 
maior ou igual a (>=) e 
menor ou igual a (<=)
```
Vejamos alguns exemplos
```python
a = 5
b = 3
c = 7
resultado = ((a > b) and (b < c)) or (a == c)
print("Resultado da combinação de expressões lógicas:",
resultado) # Resultado: True
resultado = not ((a > b) or (b < c))
print("Resultado da combinação de expressões lógicas:",
resultado) # Resultado: False
```