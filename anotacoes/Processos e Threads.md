Tópico:: #sistemasoperacionais 
Links::

---
## Anotações

### Notas Principais

- [[SO-Aula3_ProcessosEThreads.pdf]]
- ![[Processos e Threads 2024-03-18 10.59.15.excalidraw]]

### Questões-Chave

- Qual a diferença entre processos CPU-bound e I/O-bound?
- Cite as quatro condições que levam ao término de um processo.
- Qual a relação entre programa e processo?
- O que é processo?
	
- No tocante aos sistemas operacionais com múltiplos processadores, qual é o fator chave no desenvolvimento desse tipo de sistemas?
- Nos conceitos de ciência da computação, um processo é um módulo executável que pode conter threads. Um conceito importante sobre threads que estão contidas no mesmo processo é ?
- O que é thread?

### Resumo

- Um processo é um programa que está na memoria ram e está sendo executado.
	- Um processo constitui em uma atividade.
	- Possui programa, entrada, saída e um estado
- Um processo pode alocar recursos, compartilhar dados, trocar informações e sincronizar execução.
- [[Pseudoparalelismo]]
- [[Multiprogramação]]
- [[Multiprocessadores]]
- Para um processo existir o SO cria um contexto de execução e assim rodar o programa:
	- Ram a ser usada
	- Abertura de arquivos acessados
	- Privilégios de segurança
	- Quantum de tempo
	- Prioridade

- Eventos que levam a criação de processos:
	- Inicio de sistema
	- solicitação do usuario
	- inicio de uma tarefa em lote
	- Alguns processo são executados em primeiro plano e outros em segundo plano
	- é possível ter varias janelas abertas ao mesmo tempo e cada uma executar processos diferentes.
	- Todo processo é criado por um processo existente
	- Quando um processo filho é criado o pai e o filho ocupam espaço distintos de endereçamento
		- é possível compartilhar recursos entre eles.

- Eventos que levam ao termino de processos
	- Saída normal - Voluntaria
	- Saída por erro - Voluntaria: Processo descobre erro fatal
	- Erro Fatal - Involuntário  causado pelo processo, erro de programa.
	- Cancelamento por outro processo- Involuntária: Processo aciona o SO para matar outro processo. Necessita de autorização.

Hierarquia de Processo
	No unix é chamado de grupo de processo, o windows não adota esse conceito
	Consiste na possibilidade de um processo pai criar um processo filho e o filho criar o seu próprio processo.

CPU-bound
	Nesse ponto o processo passa a maior parte do temo em estado de execução usando o processador
I/O-bound
	Nesse ponto o processo para a maior parte do tempo em estado bloqueado fazendo E/S.

Um processo pode inciar em CPU-bound e torna-se I/O-bound

Threads

São estruturas de execução paralela dentro de um mesmo processos. Uma Thread compartilha com outras threads o espaço de endereçamento o contexto de software, porem cada thread tem o seu próprio contexto de hardware.








