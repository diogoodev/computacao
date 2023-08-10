Tópico::
Links::

---

- [Livro 01: Matemática Discreta, 2017. (Raquel, Cabral)](livro01-Raquel-Cabral.pdf)

# Objetivos
- Conhecer a noção e a representação de conjuntos;
- Reconhecer os símbolos que permitem relacionar elementos a conjuntos e conjuntos a conjuntos;
- Operar com conjuntos e conhecer as principais propriedades das operações.

# Exercícios
[Lista de exercícios](exerc-01-med-2023.pdf)
## Noções de conjuntos
Definição: Um conjunto é uma coleção de objetos distintos. Os objetos que fazem parte do conjunto são chamados de elementos, não importando a ordem em que se apresentam.

Representação:

![[Conjuntos e Funções 2023-08-10 05.29.38.excalidraw]]
Diagrama de Venn

A = {1,2,3,4}
Conjunto vazio:  { } ou ∅

Quando não deixar dúvidas, podemos escrever os conjuntos utilizando reticências ou uma condição.

P = {x | x é um número primo} e lemos: conjunto de elementos x
tal que x é um número primo, ou seja, P = {2, 3, 5, 7, 11, ...}.

Cardinalidade = quantidade de elementos

O conjunto A = {1, 3, 5, 7} tem cardinalidade 4 e o conjunto
P = {2, 3, 5, 7, 11, ...} tem cardinalidade infinita.

Descreva os elementos dos conjuntos e indique sua cardinalidade:
a) A = {x | x é mês do ano} 
	A = {1,2,3,4,5,6,7,8,9,10,11,12}  
	Cardinalidade 12
b) B = {x | x é dia da semana}
	B = {1,2,3,4,5,6,7}
	Cardinalidade 7
c) C = {x | x é múltiplo positivo de 6}
	C = {6,12,18,24,30,36 ...}
	cardinalidade infinita
d) D = {x | x é divisor positivo de 12}
	D = { 1,2,3,4,6, 12}
	cardinalidade 6

## Relações de pertinência e inclusão

Relacionamos elementos com conjuntos utilizando a condição de estarem presentes no conjunto ou não, essa relação é chamada de pertinência e utilizamos os símbolos **∈ e lemos que o elemento pertence ao conjunto ou ∉ e lemos não pertence.**

A = {x | x é par}, então podemos dizer que 2 ∈ A e 5 ∉ A.

Dados dois conjuntos A e B, dizemos que A é um subconjunto de B se todo elemento que pertence ao conjunto A também pertence ao conjunto B, utilizamos a notação **A ⊂ B, lemos A está contido em B, ou B ⊃ A, lemos B contém A**.

Se existir um elemento do conjunto A que não pertença ao conjunto B dize-
mos que A não é subconjunto de B e denotamos por A ⊄ B , lemos que A não
está contido em B, ou B ⊅ A, lemos que B não contém A.

A = {0,2,4,6} e B = {0,1,2,3,4,5}, podemos dizer que A ⊄ B ou que B ⊅ A.

>[!tip]
>∅ é subconjunto de qualquer conjunto.


O conjunto P(A) formado por todos os subconjuntos de um conjunto A é chamado de conjunto das partes de A ou conjunto potência e tem cardinalidade 2n, onde n é o número de elementos do conjunto A.

Considere o conjunto A ={ 2, 3, 5, 7} o conjunto das partes de A possui 
n(P(A)) = 24 = 16 elementos, que são:
P(A) = {∅, {2}, {3}, {5}, {7}, {2, 3}, {2, 5}, {2, 7},{3, 5}, {3, 7}, {5, 7}, {2, 3, 5}, {2, 3, 7},
{2, 5, 7}, {3, 5, 7}, A}

Dados dois conjuntos A e B dizemos que eles são iguais se A ⊂ B e B ⊂ A

Os conjuntos A = {1, 2, 3} e B = {2, 1, 3} possuem os mesmos elementos, ou seja, A= B
A = {a, e, i, o, u} e B = {x | x é vogal} podemos dizer que A = B.

Analisando cada item a seguir, classifique as sentenças em verdadeiro (V) ou falso (F):
( V) 2 ∈ {0, 1, 2, 3, 4}
( V) {4} ∈ {0, 2, 4, 6}
( V) {2, 8} ⊄ {0, 2, 4, 6}
( V) ∅ ∈ {1, 2, 3}
( F) {1, 3, 5} ⊃ ∅
( V) {0} ⊂ {0, 1, 2}
2. Dado o conjunto A, que possui 7 elementos, determine o número de elementos do conjunto das partes de A, que contém pelo menos dois elementos.
P(A) = 2⁷ = 128
Como a questão pede pelo menos 2 elementos: P(A) = 120 elementos
3. Considerando os conjuntos A = {5, 7, 9, 11, 13} e B = {1, 3, 5, 7, 9, 11, 13, 15}, assinale a alternativa correta:
a) ∅ ⊄ A F
b) A ⊂ B V
c) A ⊃ B F
d) B ⊅ A F
e) 15 ∉ B F

## Operações entre conjuntos
