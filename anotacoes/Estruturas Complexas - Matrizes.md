Tópico:: 
Links:: [[011-1-7 Fundamentos de Lógica de Programação]]

---

## Textos
- [[Slides Semana 07 - FLP]]

## Links

Somar e subtrair Matrizes:

[https://estudos.rededecisao.com.br/](https://estudos.rededecisao.com.br/como-somar-matrizes/#:~:text=A%20adi%C3%A7%C3%A3o%20de%20matriz%20%C3%A9,o%20elemento%20correspondente%20da%20outra.&text=Lembrando%20que%20as%20matrizes%20envolvidas,outra%20matriz%20de%20mesma%20ordem.)  

Multiplicação de Matrizes:  
[https://pt.wikipedia.org/wiki/Produto_de_matrizes](https://pt.wikipedia.org/wiki/Produto_de_matrizes)  

Aula Araguaína StreamYard:
[https://streamyard.com/a9zf3rnpuwxv](https://streamyard.com/a9zf3rnpuwxv)

## Matrizes

- Uma Matriz é um agregado homogêneo *multidimensional; * 
-  Se diferencia do vetor que é um agregado de *dados unidimensional;*  
- Dessa forma, *as matrizes nada mais são do que vetores  
multidimensionais*;  
-  As matrizes são úteis quando *desejamos relacionar conjuntos  
de dados homogêneos.*

Assim como os vetores possuem cada célula indexada por um  
índice, também a Matriz possui cada célula indexada por índices  
que indicam a posição de cada elemento;  

| colunas | colunas | colunas                                    |
|--------|--------|--------------------------------------------|
|linhas    | linhas  | linhas                 |
| linhas   | linhas   | linhas            |
| linhas   | linhas   |linhas          |

Matriz 3x3, primeiro índice designa a linha, o segundo a coluna.

`Acessando o último elemento da matriz Mat[2][2]`
| colunas `[0]`| colunas `[1]` | colunas `[2]  `                     |
|--------|--------|--------------------------------------------|
|linhas  `[0] ` | linhas  | linhas                 |
| linhas `[1]`   | linhas   | linhas            |
| linhas `[2]`  | linhas   |`Mat[2][2] `   |
## Exercícios
1) Manipulação de Matrizes

Em matemática, o produto de duas matrizes é definido somente quando o número de colunas da primeira matriz é igual ao número de linhas da segunda matriz. `Se A[m][n] é uma matriz de ordem m x n; e B[n][p] é uma matriz de ordem n x p, então seu produto é uma matriz C[m][p] de ordem m x p, definida como AB.`

Escreva um programa no Portugol Studio que leia duas matrizes, A e B, de tamanhos predefinidos, e calcule o produto entre as duas matrizes. Ao final, apresente as matrizes A, B e a matriz do produto, C = AB.
