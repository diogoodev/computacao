Tópico::
Links::

---
## Tipos

```timestamp 
 25:35
 ```

### Sistemas mono-usuários

Unico usuario
 Um unico usuario usando todos os recursos
Ex: MS-DOS, windows 3.0, Windows 9x, Millenium

### Sistemas multi-usuários

Varias ssessões de usuarios em um computador;
	Os programas e os arquivos ficam no host que gerencia os perifericos que são compartilhados entre os usuarios
Ex: Unix, Windows-NT, Windows 2000, Windows XP

```timestamp 
 26:51
 ```

### Sistemas mono-tarefa (mono-programaveis)

Apenas uma tarefa de cada vez;
	Tudo que tá no computador é alocado para uma unica tarefa
Ex: MS-DOS

### Sistemas multi-tarefas (multi-programaveis)

Varias tarefas simultaneamente;
	Podemos ter tanto tarefas cooperativas, como tarefas prinpitivas
	Cooperativa, cada aplicativo ocupa seu endereço na memoria e recurso do sistema. Cada processo libera de forma vnlutaria o recurso do processador para que outro processo possa rodar.
Ex: Windows NT, Unix, Windows 9x


```timestamp 
 29:28
 ```

### SIstemas em Lote (Batch)

- Os seus jobs fIcavam armazenados em fitas, até serem executados de forma sequencial.
- Os jobs não possuiem interação com o usuarios
- Os jobs tinham sua interação feita de forma manual

```timestamp 
 31:28
 ```

### Sistemas Multi-programáveis de Tempo Compartilhado (timesharing)

Fornecem serviços a diversos usuarios concorrentemente;
Os usarios possuem um terminal e a interação com o porgrama em execução cria a ilusão de exclusividade, mas os recursos na verdade estão sendo compartilhados

O processo realimenta o computador. O tempo depende da aplicação;
Todos os servços concorrem entre si para o uso dos recursos do computador.
É como se tivessemos uma fila com os programas.

### Sistemas Multi-programáveis de Tempo Real

Monitoram processos externos requerem tempos de resposta dentro de limites rigidos;
Ex: experimentos, cientificos, tratamento de imagens medicas, controle de processos, etc.


### Sistemas Multiplos Processadores

Possue 2 ou mais CPUs, interligadas, trabalhando conjuntamente; 
Fortemente acopladas: Assimetricos e simetricos  e francamente acoplados: Sistemas de rede e Sistemas opercinais distribuidos
