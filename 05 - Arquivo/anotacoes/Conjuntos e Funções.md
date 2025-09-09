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
União, interseção, diferença, produto cartesiano e a diferença simétrica.

### União
Dados dois conjuntos A e B, chamamos de união de A e B e denotamos por A ∪ B, ao conjunto C que possui todos os elementos que pertencem a A e todos os elementos que pertencem a B e nenhum outro elemento que não esteja em um dos conjuntos

**A ∪ B = C = {x | x ∈ A ou x ∈ B}.**

![[Conjuntos e Funções 2023-08-10 06.51.57.excalidraw]]
Representações de união no diagrama de Venn
Dados os conjuntos A = {0, 2 ,4, 6, 8} e B = {1, 2, 3, 4}, temos que:
A ∪ B={0, 1, 2, 3, 4, 6, 8}

**Propriedades:** se A, B e C são conjuntos quaisquer, então valem as seguintes
propriedades da união:
• A ∪ A = A (idempotente)
• A ∪ ∅ = A (elemento neutro)
• A ∪ B = B ∪ A (comutativa)
• (A ∪ B) ∪ C = A ∪ (B ∪ C) (associativa).

### Interseção
 Dados dois conjuntos A e B, chamamos de interseção de A e B ao conjunto C que possui todos os elementos que pertencem a A e pertencem a B e nenhum outro elemento que não esteja nos dois conjuntos. Representamos a interseção dos conjuntos A ∩ B por:
 
**A ∩ B = C = {x | x ∈ A e x ∈ B}.**

![[Conjuntos e Funções 2023-08-10 07.09.58.excalidraw]]

Dados os conjuntos A = {0, 2, 4, 6, 8} e B = {1, 2, 3, 4}, temos que:
A ∩ B={2, 4}.

**Propriedades:** se A, B e C são conjuntos quaisquer, então valem as seguintes propriedades da interseção:
• A ∩ A = A (idempotente)
• A ∩ ∅ = ∅ (elemento neutro)
• A ∩ B = B ∩ A (comutativa)
• (A ∩ B) ∩ C = A ∩ (B ∩ C) (associativa)

Além dessas propriedades podemos, verificar que o número de elementos da união de dois conjuntos A e B é dada por:

n(A ∪ B) = n(A) + n(B) − n(A ∩ B).

Para três conjuntos A,B e C, temos que:
n(A ∪ B ∪ C) = n(A) + n(B) + n(C) − n(A ∩ B) − n(A ∩ C) − n(B ∩ C) + n(A ∩ B ∩ C)
complementar
Dos onze jogadores do time de futebol ABC, oito tem pelo menos vinte cinco anos e sete tem no máximo 30 anos. Se A = {x | x é jogador do ABC que tem pelo menos 25 anos} e B = {x | x é jogador do ABC e tem no máximo 30 anos}, podemos determinar o número de jogadores que possuem idade entre 25 e 30 anos. Como A ∪ B= {x | x é jogador do time de futebol ABC}, assim:

	n(A ∪ B) = n(A) + n(B) − n(A ∩ B)
	11 = 8 + 7 − n(A ∩ B)
	n(A ∩ B) = 4.

- **União (A ∪ B):** Contém todos os elementos que pertencem a A, a B ou a ambos.
- **Interseção (A ∩ B):** Contém apenas os elementos que pertencem tanto a A quanto a B.

### Diferença
Considere dois conjuntos A e B, chamamos de diferença entre A e B ao conjunto C dos elementos de A que não pertencem a B. Denotamos por A − B a diferença entre os conjuntos A e B e representamos:

A − B= C ={x | x ∈ A e x ∉ B}

![[Conjuntos e Funções 2023-08-10 07.52.04.excalidraw]]
A diferença não é comutativa e nem associativa

Sejam dados os conjuntos A = {−3, −2, −1, 0, 1, 2} e B = {0, 1,2, 3, 4, 5}. Determinamos os conjuntos A − B e B - A e verificamos que não possuem elementos comuns.

A − B  = {−3, −2, −1} 
B - A  = { 3, 4, 5}
(A − B) ∩ (B − A) = ∅

###  Diferença simétrica
A diferença simétrica entre dois conjuntos A e B, denotada por A ∆ B, é o conjunto C que possui todos os elementos de A que não pertencem a B e todos os elementos de B que não pertencem a A, e nenhum outro elemento, assim: 

A ∆ B = C= {x | (x ∈ A e x ∉ B) ou (x ∉ A e x ∈ B)} = (A − B) ∪ (B − A)

Podemos verificar facilmente que (A − B) ∪ (B − A)=(A ∪ B) − (A ∩ B).

![[Conjuntos e Funções 2023-08-10 08.44.32.excalidraw]]

Considerando os conjuntos A = {1, 2, 3, 4, 5, 6} e B = {2, 3, 5, 7,11, 13}, determinamos a diferença simétrica entre A e B.

A ∆ B = C= {x | (x ∈ A e x ∉ B) ou (x ∉ A e x ∈ B)} = (A − B) ∪ (B − A)
 C= {1,4,6,7,11,13 } 
 
**Propriedades:** Sejam A e B conjuntos quaisquer, valem as seguintes propriedades para a diferença simétrica:
• A ∆ ∅ = A
• A ∆ A = ∅
• A ∆ B = B ∆ A .

Quando A e B são conjuntos com A ⊂ B, chamamos de **complementar** de A
em relação a B ao conjunto formado pelos elementos de B que não pertencem a A, isto é, a diferença B - A, denotado por CAB
A e representado por
C^Ab = {x | x ∉ A e x ∈ B} = B − A

Dados A = {1, 2, 3, 4} e B = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10} podemos
determinar o complementar de A em relação a B
C^AB = B − A = {5,6,7,8,9,10}

### Produto Cartesiano
Dados os conjuntos A e B, chamamos de produto cartesiano, e representamos por A x B, ao conjunto C formado por pares ordenados encontrados combinando cada um dos elementos do conjunto A com todos os elementos do conjunto B, nesta ordem, e nenhum outro elemento.

A x B = C = {(x,y) | x ∈ A e y ∈ B}.

Sejam A = {0, 1, 3, 5} e B = {2, 3}, determinamos A x B, B x A e B x B.

A x B = {(0,1),(0,3),(1,2),(1,3)(3,2),(3,3),(5,2),(5,3)}
B x A = {(2,0),(2,1),(2,3),(2,5),(3,0),(3,1),(3,3),(3,5)}
B x B= {(2,2),(2,3),(3,2),(3,3)}

Observamos que o produto cartesian**o não é comutativo**, ou seja A x B ≠ B ⨯ A. Podemos ainda determinar o número de elementos do produto que é:

n(A⨯B) = n(A) ∙ n(B)

Dados dois conjuntos A com 5 elementos e B com 4 elementos, o número de elementos de A⨯B é:

n(A x B) = n(A) . n(B) = 5 . 4 = 20

1. Dados A = {1, 2, 3, 4}, B = {2, 3, 6, 7, 8} e C = {3, 4, 5, 6}, determine o que se pede:
a) A ∪ B = {1,2,3,4,6,7,8}

b) A ∩ C = {1,2,5,6}

c) A ∪ (B ∪ C)

D = (B ∪ C) = {2,3,4,5,6,7,8}
 A ∪ D = {1,2,3,4,5,6,7,8}
 
d) A - (B ∪ C)
D = (B ∪ C) = {2,3,4,5,6,7,8}
 A - D = {1}
e) A ∆ B = {1,4,6,7,8}

f) A x B = {(1,2),(1,3),(1,6),(1,7)(1,8),(2,2),(2,3),(2,6),(2,7),(2,8),(3,2),(3,3)(3,6),(3,7),(3,8),(4,2),(4,3)(4,6),(4,7),(4,8)}

2. Considere A = {2, 3, 5} e B = {1, 2, 3, 4, 5, 6}. Determine o número de elementos  de:
a) A ∪ B = 6 elementos
b) A x B  = 18 elementos

3. Sejam A e B dois conjuntos distintos. Assinale a sentença verdadeira.
a) A − B = B − A              F
b) (A − B) ⊂ (A ∩ B)       F
c) (A − B) ⊂ (A ∪ B)       V
d) (A − B) ∪ (B − A) = A ∪ B.  F

4. Dados os conjuntos A = {0, 1, 2, 3, 4, 5, 6, 7},B = {4, 5}, C = {1, 2} e D = {2, 3, 4}. Determine:

(A − C)∩(B ∪ D) = {0,3,4,5,6,7} ∩ {2,3,4,5} = {3,4,5}

5. Sejam A = {−2, −1, 0, 1, 2} e B = {0, 1, 2}. Sobre o produto cartesiano, é correto afirmar que:
a) A x B possui 8 elementos   F
b) A x B = B x A                          F
c) A x A possui 25 elementos V
d) B x B possui 15 elementos.  F

6. Dados A, B e C conjuntos quaisquer, verifique se as seguintes propriedades envolvendo união e interseção são verdadeiras ou falsas:
a) A ∪ (A ∩ B) = A    V
b) A ∩ (A ∪ B) = A  V
c) A ∪ (B ∩ C) = (A ∪ B) ∩ (A ∪ C) V
d) A ∩ (B ∪ C) = (A ∩ B) ∪ (A ∩ C).        F

7. Considere que A x B = {(0, −2), (0, −1), (1, −2), (1, −1), (2, −2), (2, −1), (5, −2), (5,−1)}. Determine os conjuntos A e B.
A = {0,1,2,5}
B ={-2,-1}

### Conjuntos Numéricos
Conjunto dos números naturais, formado pelos números 0, 1, 2, 3, 4, … e representado pela letra *N.*
N = {0, 1, 2, 3, 4, …}
N* = {1, 2, 3, 4, …}.

O conjunto dos números inteiros, representado por **Z,** é formado por todos os
números naturais, acrescidos dos números negativos, portanto:
Z = {…,−3, −2, −1, 0, 1, 2, 3, …}.

Notamos que N é um subconjunto de Z, ou seja, **N ⊂ Z**

O  conjunto dos números racionais, representado por Q, é formado por todos
os números que podem ser escritos na forma de fração, desta forma:
*Q = {x | x= a/b ,com a, b ∈ Z e b ≠ 0}*

São exemplos de racionais todos os números naturais, inteiros, decimais exa-
tos, decimais infinitos periódicos.
Exemplos: 1/4 = 0,25 e -5/9 = −0,555 …

Chamaremos de conjunto dos números reais e representaremos por R, ao con-
junto que possui os números racionais e os decimais infinitos não periódicos.

O conjunto formado por todos os números que não podem ser escritos na forma de fração, ou seja, decimais infinitos e não periódicos, será chamado de conjunto dos números irracionais e representado por I.

São exemplos de números irracionais: √2, √3, π = 3,14159265....

Notamos que a união do conjunto dos números racionais com o conjuntos dos irracionais resulta no conjuntos dos números reais, ou seja,
R = Q ∪ I.

o conjunto dos números complexos, representado por C, formado por números da forma:Q = {x | x= a/b ,com a, b ∈ Z e b ≠ 0}Q = {x | x= a/b ,com a, b ∈ Z e b ≠ Q = {x | x= a/b ,com a, b ∈ Z e b ≠ 0}Q = {x | x= a/b ,com a, b ∈ Z e b ≠ 0}0}
c = a + bi, com a, b ∈ R e i é um número complexo que corresponde a √−1.

Este conjunto possui as seguintes operações de soma e produto:
( i ) (a + bi) + (c + di) = (a + c) + (b + d)i
( ii ) (a + bi) ∙ (c + di) = (a ∙ c - b ∙ d) + (b ∙ c + a ∙ d)i.

Atividades
Assinale V para as sentenças verdadeiras e F para as sentenças falsas:
(V ) Z ⊂ R
( V) √2 ∈ R
(F ) I ⊃ Q
( F) - 3/5 ∉ Q

2. Verifique se as equação do segundo grau a seguir possuem raízes reais
ou complexas:
a) x2 − 5 ∙ x + 6 = 0
b) 2x2 + 8 = 0
c) x2 − 4 ∙ x + 5 = 0

### Resumo
Dados dois conjuntos A e B, apresentamos as operações entre conjuntos:
União: A ∪ B = {x | x ∈ A ou x ∈ B}
Interseção: A ∩ B = {x | x ∈ A e x ∈ B}
Diferença: A - B = {x | x ∈ A e x ∉ B}
Diferença simétrica: A ∆ B = (A ∪ B) - (A ∩ B)
Complementar: CBA = B - A = {x | x ∉ A e x ∈ B}, com A ⊂ B.
Definimos o produto cartesiano dos conjuntos A e B como o conjunto
dos pares ordenados encontrados combinando cada um dos elementos do
conjunto A com todos os elementos do conjunto B.
	A ⨯ B = {(x,y) | x ∈ A e y ∈ B}
	
Verificamos que o número de elementos da união de dois A e B conjuntos é dada por:
	n(A ∪ B) = n(A) + n(B) - n(A ∩ B)
	
Para três conjuntos A, B e C, temos que:
	n(A ∪ B ∪ C) = n(A) + n(B) + n(C) − n(A ∩ B)- n(A ∩ C)- n(B ∩ C) + n(A ∩ B ∩ C)
	
Observamos que o produto cartesiano não é comutativo, ou seja A ⨯ B ≠ B ⨯ A
e ainda determinamos o número de elementos do produto que é:
n(A ⨯ B) = n(A) ∙ n(B)