llTópico:: #sistemasoperacionais
Links::

---
## Anotações

### Notas Principais

- Slides da aula  [[SO-Aula2_ArquiteturaDeSO.pdf]]

### Questões-Chave

- (Insira aqui as questões-chave que surgiram durante a aula.)

### Resumo

- Arquitetura monolítica: qualquer componente do núcleo pode acessar os demais componentes, áreas de memória ou mesmo dispositivos periféricos diretamente, pois não há barreiras impedindo esses acessos
- Arquitetura de Micronúcleo( cliente-servidor): 
	- Retira do núcleo todo o código de alto nível
	-  O resto do código seria transferido para programas
	- Mais flexibilidade
	-  Apresenta maior robustez, pois caso um serviço falhe, somente ele será afetado, devido ao confinamento de memória entre os serviços.
		- exemplo de S.O: Minix 3

- Arquitetura em Camadas: 
	- Dividida em camadas mais baixas, intermediaria e superiores.
	- Camadas mais baixa realiza a interface com o hardware
	- Camada Intermediaria: prover níveis de abstração
	- Camadas superior: interface do núcleo para aplicações
	- Pode ser lenta se tiver muitas camadas
	- Pode ser difícil definir cada camada
		- exemplo de S.O:  Multics
- Arquitetura de  Maquina Virtual:
	- Camada intermediaria entre o SO e o hardware - gerencia as maquinas virtuais
	- Pode existir diversas maquinas virtuais independentes
	- Possui uma um copia do hardware
	- Cada maquina virtual pode ter um SO diferente
	- Cada maquina virtual fica completamente isolada


