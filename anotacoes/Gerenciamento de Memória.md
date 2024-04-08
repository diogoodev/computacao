Tópico::
Links::

---

## Anotações

### Notas Principais

- [[SO-Aula6_GerenciamentoDeMemoria.pdf]]
- ![[Gerenciamento de Memória 2024-04-08 15.51.35.excalidraw]]

### Questões-Chave

-  Defina Gerenciador de Memoria
- O que são espaços de endereçamento?
- O que a Relocação dinamica faz?
- Cite uma desvantagem fazer realocação usando registradores base e limite.
- Com o que o swapping lida?
- O que é swapping?
- Defina reentrância

### Resumo

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=144&selection=24,0,34,29&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.125]]
> > hierarquia de memórias, em que os computadores têm alguns megabytes de memória cache volátil, cara e muito rápida, alguns gigabytes de memória principal volátil de velocidade e custo médios, e alguns terabytes de armazenamento em disco em estado sólido ou magnético não volátil, barato e lento, sem mencionar o armazenamento removível, com DVDs e dispositivos USB. É função do sistema operacional abstrair essa hierarquia em um modelo útil e então gerenciar a abstração
> 


> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=144&selection=35,0,40,0&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.125]]
> > A parte do sistema operacional que gerencia (parte da) hierarquia de memórias é chamada de gerenciador de memória
> 

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=145&selection=12,34,20,46&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.126]]
> > O sistema operacional pode estar na parte inferior da memória em RAM (Random Access Memory — memória de acesso aleatório), como mostrado na Figura 3.1(a), ou pode estar em ROM (Read-Only Memory — memória apenas para leitura) no topo da memória, como mostrado na Figura 3.1(b), ou os drivers do dispositivo talvez estejam no topo da memória em um ROM e o resto do sistema em RAM bem abaixo, como mostrado na Figura 3.1(c)


> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=145&selection=49,0,51,21&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.126]]
> > Uma maneira de se conseguir algum paralelismo em um sistema sem abstração de memória é programá-lo com múltiplos threads
> 
> 

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=146&selection=77,16,82,19&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.127]]
> > O que o IBM 360 utilizou como solu- ção temporária foi modificar o segundo programa dinamicamente enquanto o carregava na memória, usando uma técnica conhecida como realocação estática
> 

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=147&selection=84,43,88,21&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.128]]
> > Da mesma forma que o conceito de processo cria uma espécie de CPU abstrata para executar os programas, o espaço de endereçamento cria uma espécie de memória abstrata para abrigá-los

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=147&selection=88,23,93,25&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.128]]
> > Um espaço de endereçamento é o conjunto de endereços que um processo pode usar para endereçar a memória.
> 

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=148&selection=26,1,31,16&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.129]]
> > Realocação dinâmica mapeia o espaço de endereçamento de cada processo em uma parte diferente da memória física de uma maneira simples.
> 

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=148&selection=36,2,47,5&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.129]]
> >  registradores base e registradores limite. Quando esses registradores são usados, os programas são carregados em posições de memória consecutivas sempre que haja espaço e sem realocação durante o carregamento
> 

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=148&selection=85,2,90,53&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.129]]
> > stradas na Figura 3.3. Usar registradores base e limite é uma maneira fácil de dar a cada processo seu próprio espaço de endereçamento privado, pois cada endereço de memória gerado automaticamente tem o conteúdo do registrador base adicionado a ele antes de ser enviado para a memória.
> 

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=148&selection=100,0,102,49&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.129]]
> > Uma desvantagem da realocação usando registradores base e limite é a necessidade de realizar uma adi- ção e uma comparação em cada referência de memóri
> 

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=149&selection=32,0,37,1&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.130]]
> > Duas abordagens gerais para lidar com a sobrecarga de memória foram desenvolvidas ao longo dos anos. A estratégia mais simples, chamada de swapping 
> 

> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=149&selection=35,1,41,19&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.130]]
> > swapping (troca de processos), consiste em trazer cada processo em sua totalidade, executá-lo por um tempo e então colocá-lo de volta no disco. 


> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=149&selection=47,0,51,40&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.130]]
> >  memória virtual, permite que os programas possam ser executados mesmo quando estão apenas parcialmente na memória principal
> 
> 


> [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=721&selection=45,0,92,26&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.702]]
> > A reentrância se caracteriza pela possibilidade de o código ser executado duas ou mais vezes simultaneamente. Em um multiprocessador, existe sempre o perigo de que, enquanto uma CPU executa alguma rotina, outra CPU inicialize a execução da mesma rotina também, antes que a primeira tenha acabado. Nesse caso, dois (ou mais) threads em diferentes CPUs podem estar executando o mesmo código ao mesmo tempo. Essa situação deve ser evitada usando mutexes ou outros mecanismos que protejam regiões críticas. No entanto, o problema também existe em um monoprocessador. Em particular, a maior parte de qualquer sistema operacional trabalha com as interrupções habilitadas. Para trabalhar de outro modo, muitas interrupções seriam perdidas e o sistema não se mostraria confiável. Enquanto o sistema operacional está ocupado executando alguma rotina, P, é totalmente possível que uma interrupção ocorra e que o tratador de interrupção também chame P. Se as estruturas de dados de P estiverem em um estado inconsistente no momento da interrupção, o tratador verá esse estado inconsistente e falhará. Um outro caso claro dessa ocorrência é se P for o escalonador. Suponha que algum processo tenha usado seu quantum e o sistema operacional o tenha movido para o final de sua fila. Enquanto o sistema realiza a manipulação da lista, a interrupção ocorre, tornando algum processo pronto, e, com isso, o escalonador é executado novamente. Com as filas em um estado de inconsistência, o sistema provavelmente travará. Como consequência, mesmo em um monoprocessador, é melhor que a maior parte do sistema operacional seja reentrante, com estruturas de dados críticas protegidas por mutexes e as interrupções sendo desabilitadas nos momentos em que não puderem ser toleradas.
> 
> 




