Tópico::  #estrutura_de_dados  #algoritmos_de_seleção 
Links::

---
Este algoritmo funciona construindo um array classificado no início da lista. Ele inicia o array classificado com o primeiro elemento. Em seguida, ele inspeciona o próximo elemento e o troca de volta na matriz classificada até que esteja em uma posição classificada e assim por diante.

Um algoritmo de classificação por inserção inicia a classificação no início da lista, o que significa que o primeiro elemento já está classificado.

Para este algoritmo, você desejará usar um loop `while` . Este loop precisa de duas condições:
	Primeiro, ele não deve ultrapassar o início do array (acessado com `j`).
	Segundo, o loop não deve ser executado após encontrar um valor menor que o valor atual.
