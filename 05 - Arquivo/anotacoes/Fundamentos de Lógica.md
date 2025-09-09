Tópico::
Links:: [[Fluxogramas e Tabela Verdade]]

---
## Lógica Proposicional

- Uma **proposição** é uma sentença declarativa que pode ser verdadeira ou falsa, mas não ambas simultaneamente;
	1- Princípio da Identidade: todo elemento é idêntico a si mesmo. Exemplo carro é igual  a carro; pedra é igual a pedra; flor é igual a flor;  
	2- Princípio da não contradição: duas informação contraditórias não podem ser  verdadeiras ou falsas ao mesmo tempo, uma delas deve ser verdadeira e a outra falsa;  
	3- Princípio do terceiro excluído: toda proposição pode assumir apenas dois valores VERDADEIRO ou FALSO, não existe uma terceira opção.

## Conectivos

- [[Conectivo Not (¬) ]]
- [[Conectivo AND ( ∧)]]
- [[Conectivo OR ( v )]]

### Exemplos:


**Exercício 1:** Sejam as proposições:  

- p = hoje é sábado.  
- q = hoje está chovendo. 

Como seria a Conjunção p ∧ q ?

hoje é sábado e está chovendo

**Exercício 2:** Sejam as proposições:  
- p = hoje é sábado.  
- q = hoje está chovendo.

- Como seria a Conjunção p ∧ q ?  
Hoje é sábado ou hoje está chovendo.

**Exercício 3:**  Sejam as proposições:

- p = hoje é sábado.  
- q = hoje está chovendo. 

Como seria a expressão p v ¬ q ?
Hoje é sábado ou não está chovendo 

**Exercício 4:**  Decida se o professor vai pescar no final de semana. Sejam as  proposições:  

- p = hoje é domingo.  
- q = hoje está fazendo Sol
  
O professor pesca se a expressão p v q for verdadeira. Leve em conta que hoje é sábado e o dia está ensolarado.

Hoje é domigo ou está fazendo Sol

**Exercício 5:**   Decida se o professor vai pescar no final de semana. Sejam as  proposições:

-  p = hoje é domingo.  
- q = hoje está fazendo Sol.

O professor pesca se a expressão p ∧q for verdadeira. Leve em conta que hoje é sábado e o dia está ensolarado.

Hoje é domingo e está fazendo Sol.
Professor não vai pescar.

**Exercício 6 :** Dadas duas proposições p, q podemos apresentar todas as  possíveis saídas de qualquer expressão contendo essas duas proposições através de uma tabela verdade com 2n linhas,  onde n é o número de proposições presentes na expressão.  
- Construir a tabela verdade para as seguintes expressões  
lógicas:

(¬ p v q ) v (p ∧ q )

|  p  |  q  | ( |¬  |p  |v  |q  |)  | v |(  |p  |∧  | q | ) |
|:---:|:---:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|  V  |  V  |   | F |   | V | V |   | V |   | V | V | V |   |
|  V  |  F  |   | F |   | F | F |   | F |   | V | F | F |   | 
|  F  |  V  |   | V |   | V | V |   | V |   | F | F | V |   |    
|  F  |  F  |   | V |   | V | F |   | V |   | F | F | F |   | 



(¬ p v ¬q) ∧(¬p ∧ q)

|  p  |  q  | ( |¬  |p  |v  |¬ | q |)  | v |(  |¬ |p |∧  | q | ) |
|:---:|:---:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|  V  |  V  |   | F |  V | F | F | V |  | F  |   | F | V | F | V  |
|  V  |  F  |   | F |  V | V | V | F |  | V  |   | F | V | F | F  | 
|  F  |  V  |   | V |  F | V | F | V |  | V  |   | V | F | V | V  |    
|  F  |  F  |   | V |  F | V | V | F |  | V  |   | V | F | F | F  | 

**Exercício 7:** Dadas as seguintes proposições:  
- q = o dia está ensolarado.  
- q = o mar está calmo.  
- Eu vou andar de barco se: ( p ∧q ) v (¬ q)

|  p  |  q  | ( |p  | ∧ | q |)  | v |(  |¬ | q | ) |
|:---:|:---:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|  V  |  V  |   | v | V  | v |  | V |  | f |  v |  |  |      
|  V  |  F  |   | v | F  | f |  | V |  | v  |  f |  |  |    
|  F  |  V  |   | f | F  | v |  | F |  | f |  v |  |  |        
|  F  |  F  |   | f | F  | f |  | V |  | v |  f |  |  |  

Dadas as seguintes proposições:  
	- p = o dia está ensolarado.   F
	- q = terminei todas minhas obrigações.   V

- Sabendo que o dia está chuvoso e eu terminei minhas  
obrigações. 

Qual das expressões a seguir está correta?

( p ∧ q ) v (¬ q) = TRUE  
( p ∧q ) v q = FALSE 

**( p ∧¬ q) = FALSE** 

|  p  |  q  | ( |p  | ∧ | ¬ | q |)  |  
|:---:|:---:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|  V  |  V  |   | v | F |  f | v |  |     
|  V  |  F  |   | v | V |   v | f |  |  
|  F  |  V  |   | f | F |  f  | v |  |       
|  F  |  F  |   | f | F |  v  | f |  | 

( ¬ p ∧¬ q) = TRUE

|  p  |  q  | ( | ¬ |p  | ∧ | ¬ | q |)  |  
|:---:|:---:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|  V  |  V  |   | f | v |  F | f | v |     
|  V  |  F  |   | f | v |  F | v | f |  
|  F  |  V  |   | v | f |  F | f | v |       
|  F  |  F  |   | v | f |  V | v | f | 

