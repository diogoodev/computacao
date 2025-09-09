Tópico:: #linux 
Links:: https://www.youtube.com/watch?v=gXpmaVq4myU

---
Primeiro precisamos baixar  um sistema de arquivos usando o `debootstrap` :
```
//se não tiver instalado
apt-get update
apt-get install debootstrap
//baixando o fylesistem do debian versão stable
debootstrap stable /mnt/debian/ http://deb.debian.org/debian
```

Agora usando os namespaces do linux para realizar o isolamento do sistema e a montagem do container.

```
unshare --mount --pid --net --uts --ipc --user --map-root-user --fork chroot /mnt/debian/ /bin/bash/
```

Esse comando é utilizado no Linux para criar um novo espaço de nomes (namespace) isolado para os recursos especificados. Isso permite executar um processo ou um conjunto de processos em um ambiente isolado do restante do sistema. Vamos entender cada opção:

    unshare: Comando que cria um novo espaço de nomes (namespace) isolado.

    --mount: Isola o espaço de montagem (mount namespace). Isso significa que os pontos de montagem (sistema de arquivos) dentro do namespace serão separados dos pontos de montagem do sistema principal. Isso permite que o processo em execução dentro do namespace tenha sua própria hierarquia de sistema de arquivos, independente do sistema principal.

    --pid: Isola o espaço de processo (PID namespace). Isso significa que o processo em execução dentro do namespace terá sua própria árvore de processos, e ele verá apenas os processos que fazem parte do mesmo namespace.

    --uts: Isola o espaço de identificação do sistema (UTS namespace). Isso permite que o processo dentro do namespace tenha seu próprio nome de host e informações do núcleo do sistema independentes do sistema principal.

    --net: Isola o espaço de rede (network namespace). Isso significa que o processo dentro do namespace terá sua própria pilha de rede, interfaces de rede, tabelas de roteamento e regras de firewall. Dessa forma, o processo poderá ter uma configuração de rede independente do sistema principal.

    --ipc: Isola o espaço de comunicação interprocessual (IPC namespace). Isso permite que o processo dentro do namespace tenha sua própria fila de mensagens, segmentos de memória compartilhada e semáforos, independentes do sistema principal.

    --user: Isola o espaço de usuário (user namespace). Isso permite que o processo dentro do namespace tenha suas próprias identidades de usuário e grupos, independentes do sistema principal.

    --map-root-user: Mapeia o usuário root do namespace isolado para o usuário root do sistema principal. Isso é útil para permitir privilégios de superusuário dentro do namespace isolado, mesmo que o usuário real no sistema principal não seja root.

    --fork: Após criar o novo namespace, esse parâmetro faz com que o processo corrente se bifurque (fork) em um novo processo. O processo pai continua sua execução normal, enquanto o processo filho assume o novo namespace isolado.

A parte chroot /mnt/debian/ /bin/bash/ é um comando que executa um novo processo dentro do ambiente raiz de um sistema de arquivos isolado (chroot jail). O comando chroot é usado para alterar o diretório raiz para um diretório diferente do diretório raiz do sistema, criando assim um ambiente isolado para a execução de comandos.

Vamos entender cada parte do comando:

    chroot: É o comando em si, que é utilizado para alterar o diretório raiz do sistema para o diretório especificado.

    /mnt/debian/: É o diretório que será definido como o novo diretório raiz. Todos os caminhos dentro do ambiente chroot serão resolvidos relativamente a este diretório. Portanto, qualquer referência a / dentro do ambiente chroot se refere a /mnt/debian/, não ao diretório raiz do sistema principal.

    /bin/bash/: É o caminho para o executável que será executado dentro do ambiente chroot. Neste caso, o shell Bash (bash) está sendo executado. Isso permitirá que o usuário interaja com o ambiente chroot através do shell Bash, como se estivesse executando o Bash em um sistema autônomo com /mnt/debian/ como seu diretório raiz.

O uso do chroot é comum para criar ambientes isolados e seguros para executar aplicativos ou realizar tarefas de manutenção em sistemas Linux. Isso é especialmente útil para testar programas em um ambiente controlado ou para reparar sistemas quando o sistema principal não está funcionando corretamente.