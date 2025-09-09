Tópico::
Links:: [[011-1-1 Pensamento Computacional]]

---

## Conteúdo

- [[Slides da aula 05]]

- [[Conteúdo base 05]]

- [[Conteúdo complementar 05]]


## Pontos Principais

- [[Algoritmos]]

### Anotações
- Descrever em passos uma atividade a ser executada, quando mais bem detalhada melhor.
- Os passos/etapas são chamados de comandos/instruções e quando sistematizamos de modo que façam sentido para a resolução do problema é o foco de um algorítimo.
- [[Algoritmos]] é o pilar que de fato traz a programação para o pensamento computacional.
- Na programação para que o computador/maquina entenda um algoritmo deve ser transcrito para código ([[Código fonte]]), por meio de uma [[Linguagem de programação]].
-  Duas de se trabalhar algoritmo com crianças
	- Usando a linguagem de programação Scratch.
	- Ou ainda por meio da computação desplugada. [[Atividades desplugadas]]

#### Exemplo:

Um dos meus colegas de quarto tinha várias dúzias de pares de meias, cada  par de uma cor ou modelo ligeiramente diferentes. Como ele costumava adiar   a lavagem até que nenhuma meia estivesse limpa, toda vez que ele as lavava  enfrentava uma tarefa nada desprezível de combiná-las novamente em seus  devidos pares. Eis como meu colega fazia isso:]
	1. Primeiro, ele puxava uma meia qualquer da pilha de meias lavadas,  
	2. Depois, tirava outra aleatoriamente, para ver se combinavam.  
	3. Se não combinavam, ele coloca a segunda meia de volta e puxava outra,  aleatoriamente.  
	4. Ele continuava esse processo até que encontrasse um par que combinasse.  
	5. Depois ele prosseguia, até que todos os pares estivessem formados

Resolvi  usar um algoritmo melhor para combinar minhas meias’. O que ele quis  
d i z e r  e r a  q u e  i a  u t i l i z a r  u m  p r o c e d i m e n t o  d e  n a t u r e z a  
fundamentalmente diferente.  
1. Ele tirou a primeira meia e colocou sobre a mesa.  
2. Tirou mais uma e comparou com a primeira meia;  
3. Como não combinavam, colocou ao lado da outra.


Podemos melhorar o algoritmo de organização das meias sendo mais preciso nas  
instruções.  
1. Pegar uma meia e colocar sobre a mesa  
2.  **Repetir** a sequência de passos abaixo até que não tenha meias na pilha de meias lavadas  
3. Pegar uma meia  
4. **Se** a meia formar par (for igual) a uma das meias sobre a mesa então  
5. Combinar meias  
6. **Se** a meia não formar um par, então  
7. Colocar sobre a mesa

