Tópico::
Links::

---
## Anotações

### Notas Principais

- [[SO-Aula5_EscalonamentoDeProcessos.pdf]]
- ![[Gerenciamento de Processos 2024-04-01 12.10.41.excalidraw]]

### Questões-Chave

- Defina Escalonador
- Quando escalonar?
- Qual a diferença de  um algoritmo de escalonamento não preemptivo e de um algoritmo de escalonamento preemptivo ?
- Quais as categorias de algoritmos de escalonamento?
- Quais os objetivos do algoritmo de escalonamento?
### Resumo

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=83&selection=76,1,77,36&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.64]]
> >  escalonamento, isto é, decidir qual processo deve ser executado, quando e por quanto tempo
> 
> 



> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=122&selection=47,17,55,0&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.103]]
> > A parte do sistema operacional que faz a escolha é chamada de escalonador, e o algoritmo que ele usa é chamado de algoritmo de escalonamento

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=122&selection=60,0,62,55&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.103]]
> > Quando o núcleo gerencia threads, o escalonamento é geralmente feito por thread, com pouca ou nenhuma consideração sobre o processo ao qual o thread pertence

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=123&selection=75,0,78,24&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.104]]
> > Além de escolher o processo certo a ser executado, o escalonador também tem de se preocupar em fazer um uso eficiente da CPU, pois o chaveamento de processos é algo caro


> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=124&selection=32,36,46,1&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.105]]
> > como o mostrado na Figura 2.39(a), passam a maior do tempo computando, enquanto outros, como o mostrado na Figura 2.39(b), passam a maior parte do tempo esperando pela E/S. Os primeiros são chamados limitados pela computação ou limitados pela CPU; os segundos são chamados limitados pela E/S.

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=124&selection=65,22,68,54&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.105]]
> > A ideia básica aqui é que se um processo limitado pela E/S quiser executar, ele deve receber uma chance rapidamente para que possa emitir sua solicitação de disco e manter o disco ocupado.

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=124&selection=78,29,81,13&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.105]]
> >  Primeiro, quando um novo processo é criado, uma decisão precisa ser tomada a respeito de qual processo, o pai ou o filho, deve ser executado

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=124&selection=85,3,87,33&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.105]]
> > Segundo, uma decisão de escalonamento precisa ser tomada ao término de um processo.

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=124&selection=92,0,94,43&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.105]]
> > Terceiro, quando um processo bloqueia para E/S, em um semáforo, ou por alguma outra razão, outro processo precisa ser selecionado para executar

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=124&selection=118,0,119,39&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.105]]
> > Quarto, quando ocorre uma interrupção de E/S, uma decisão de escalonamento pode ser feita

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=125&selection=5,0,11,29&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.106]]
> > Se um hardware de relógio fornece interrupções periódicas a 50 ou 60 Hz ou alguma outra frequência, uma decisão de escalonamento pode ser feita a cada interrupção ou a cada k-ésima interrupção de relógio


> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=125&selection=14,17,24,28&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.106]]
> > Um algoritmo de escalonamento não preemptivo escolhe um processo para ser executado e então o deixa ser executado até que ele seja bloqueado (seja em E/S ou esperando por outro processo), ou libera voluntariamente a CPU


> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=125&selection=32,16,41,31&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.106]]
> > um algoritmo de escalonamento preemptivo escolhe um processo e o deixa executar por no máximo um certo tempo fixado. Se ele ainda estiver executando ao fim do intervalo de tempo, ele é suspenso e o escalonador escolhe outro processo para executar (se algum estiver disponível). 


> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=125&selection=57,0,65,11&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.106]]
> > 1. Lote. 2. Interativo. 3. Tempo real.
> 
> 


 Em sistemas em lote onde não há usuários esperando
 
> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=125&selection=73,32,76,14&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.106]]
> > algoritmos não preemptivos, ou algoritmos preemptivos com longos períodos para cada processo são muitas vezes aceitáveis


> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=125&selection=82,0,84,44&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.106]]
> > Em um ambiente com usuários interativos, a preempção é essencial para evitar que um processo tome conta da CPU e negue serviço para os outros.


> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=125&selection=93,0,97,34&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.106]]
> > Em sistemas com restrições de tempo real, a preempção às vezes, por incrível que pareça, não é necessária, porque os processos sabem que eles não podem executar por longos períodos e em geral realizam o seu trabalho e bloqueiam rapidamente. 


Algumas metas do algoritmo de escalonamento
```
Todos os sistemas 
	Justiça — dar a cada processo uma porção justa da CPU
	Aplicação da política — verificar se a política estabelecida é cumprida 
	Equilíbrio — manter ocupadas todas as partes do sistema
	
Sistemas em lote
	Vazão (throughput) — maximizar o número de tarefas por hora
	Tempo de retorno — minimizar o tempo entre a submissão e o término 
	Utilização de CPU — manter a CPU ocupada o tempo todo 

Sistemas interativos
	Tempo de resposta — responder rapidamente às requisições
	Proporcionalidade — satisfazer às expectativas dos usuários

Sistemas de tempo real 
	Cumprimento dos prazos — evitar a perda de dados
	Previsibilidade — evitar a degradação da qualidade em sistemas multimídia.

```

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=126&selection=34,0,37,54&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.107]]
> > Os gerentes de grandes centros de computadores que executam muitas tarefas em lote costumam observar três métricas para ver como seus sistemas estão desempenhando: vazão, tempo de retorno e utilização da CPU.

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=126&selection=38,0,43,8&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.107]]
> > A vazão é o número de tarefas por hora que o sistema completa


> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=126&selection=45,6,51,36&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.107]]
> > O tempo de retorno é estatisticamente o tempo médio do momento em que a tarefa em lote é submetida até o momento em que ela é concluída


> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=126&selection=67,10,69,47&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.107]]
> > a. O que de fato importa é quantas tarefas por hora saem do sistema (vazão) e quanto tempo leva para receber uma tarefa de volta (tempo de retorno).


> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=126&selection=75,0,81,11&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.107]]
> > Para sistemas interativos, aplicam-se metas diferentes. A mais importante é minimizar o tempo de resposta, isto é, o tempo entre emitir um comando e receber o resultado


Sistemas de tempo real:
> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=127&selection=22,21,24,9&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.108]]
> >  Eles são caracterizados por ter prazos que devem — ou pelo menos deveriam —, ser cumpridos

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=127&selection=36,47,37,59&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.108]]
> > o escalonamento de processos deve ser altamente previsível e regular.

