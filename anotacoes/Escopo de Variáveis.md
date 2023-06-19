Tópico::
Links:: [[011-1-7 Fundamentos de Lógica de Programação]]

---

```timestamp-url 
 https://www.youtube.com/watch?v=7zok7bpvXGU
 ```

Variáveis existem dentro do escopo em que foram declaradas;  
-  Não podem ser "enxergadas" fora deste escopo.  

O que é escopo da variável?  
- É o nome dado à propriedade que determina onde cada variável é  visível ou não dentro do meu código.  

O escopo pode ser local ou global.

**- Variáveis Globais** - são aquelas declaradas no início de um  
algoritmo. São visíveis, ou seja, podem ser acessadas em todo  
corpo do algoritmo.  

|Vantagens|Desvantagens|
|---|---|
|Variáveis globais são muito úteis quando você está lidando com várias funções no programa que manipulam os mesmos dados. |Pode dificultar a depuração|
|As mudanças que precisavam ser aplicadas em todo o programa seriam mais fáceis através da implementação de uma variável global |Pode levar a efeitos colaterais indesejáveis|
|Podemos acessar de qualquer lugar ou através de qualquer função aleatória do programa.| Refatoração de código se torna extensa|

**- Variáveis Locais** - são aquelas declaradas dentro de um bloco de  
código ou de um subalgoritmo. São visíveis, ou seja, podem ser  
acessadas somente dentro do bloco de código onde foram  
declaradas.

|Vantagens|Desvantagens|
|---|---|
|O principal benefício de uma variável local é que não há alteração acidental dos dados. | Escopo limitado a um bloco de código|
|A variável é declarada dentro de um bloco e esse bloco de código usa a variável e evita efeitos colaterais indesejáveis |Proíbe o compartilhamento de dados |
|A variável local consome memória por um período limitado do período, somente quando o bloco que contém a variável é executado.|Não retém os dados entre as chamadas, porque variáveis locais são geradas e removidas a cada entrada e saída do bloco.|

