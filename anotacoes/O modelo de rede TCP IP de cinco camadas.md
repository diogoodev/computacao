Tópico::
Links::

---
Cada camada é como se fosse diferentes aspectos da entrega de um pacote de encomenda.  A  Physical Layer seria o caminhão de entrega e as estradas, Data Link seria como os caminhões passam de um cruzamento para o outro,  a camada de Rede identifica quais estradas devem ser usadas do endereço A ao endereço B. A camada de transporte garante que o motorista saiba bater na sua porta e dizer que o pacote chegou, a camada de aplicação é o conteúdo do pacote em si.

-  Physical Layer (10 Base T, 802.11, Bits)
	Representa  os dispositivos físicos que interconectam computadores
	-> Especificações dos Cabos de rede e dos conectores
	-> Especificações de como os sinais são enviados através dessas conexões
- Data Link (enlance de dados) (Ethernet, Wi-Fi, Frames, Mac Address,)
	Também conhecida como  interface de rede ou camada de acesso à rede.
	-:> Nessa camada é que definimos uma maneira comum de interpretar os sinas vindos da camada física, para que os dispositivos possam se comunicar
	-> Ethernet: Define um protocolo responsável por levar os dados para os nós em uma mesma rede ou link.
- Network Layer (Rede ou Internet)(IP, Datagram, IP adress)
	Permite que diferentes redes se comuniquem entre si através de dispositivos conhecidos como roteadores.
	->Internetwork: Um conjunto de redes conectadas por roteadores é uma interligação de redes, a mais conhecida é a internet.
	-> A camada de rede é responsável por enviar dados através de um conjunto de redes.
	-> IP ou Internet Protocol: É o protocolo mais comum usado na camada de rede. É responsável por enviar os dodos de um nó para o outro.

- Transport (Transporte) (TCP/UDP, Segment, Port #''s)
	A camada de rede irá fazer o transporte de dados entre dois nós individuais, a camada de transporte organiza esses dados e indica quais programs de cliente e servidor devem receber esses dados.
	->TCP ou Transmission Control Protocol: é a protocolo mais conhecido na quarta camada. É os responsável por garantir que os dados cheguem aos aplicativos corretos em execução nos nós.
	-> UDP ou User Datagram Protocol: A diferença entre UDP E TCP é que o TCP oferece mecanismos para ques dados sejam entregues de formas confiáveis, enquanto o UDP não tem esses mecanismos.

- Application (Aplicação) ( HTTP, SMTP, etc.., Messages) 
	Existem muitos protocolos diferentes nessa comada, e cada protocolo é especifico de uma aplicação. Os protocolos para navegar na web ou receber emails são os mais comuns

| Camada           | Protocolos e Conceitos               | Descrição                                                                                      |
|------------------|-------------------------------------|-----------------------------------------------------------------------------------------------|
| Physical Layer   | 10 Base T, 802.11, Bits             | Representa os dispositivos físicos que interconectam computadores. Especificações dos Cabos de rede e dos conectores. Especificações de como os sinais são enviados através dessas conexões. |
| Data Link        | Ethernet, Wi-Fi, Frames, Mac Address | Também conhecida como interface de rede ou camada de acesso à rede. Nessa camada é que definimos uma maneira comum de interpretar os sinais vindos da camada física, para que os dispositivos possam se comunicar. Ethernet define um protocolo responsável por levar os dados para os nós em uma mesma rede ou link. |
| Network Layer    | IP, Datagram, IP Address            | Permite que diferentes redes se comuniquem entre si através de dispositivos conhecidos como roteadores. Internetwork: Um conjunto de redes conectadas por roteadores é uma interligação de redes, a mais conhecida é a internet. A camada de rede é responsável por enviar dados através de um conjunto de redes. IP ou Internet Protocol é o protocolo mais comum usado na camada de rede e é responsável por enviar os dados de um nó para o outro. |
| Transport        | TCP/UDP, Segment, Port #'s          | A camada de transporte irá fazer o transporte de dados entre dois nós individuais. A camada de transporte organiza esses dados e indica quais programas de cliente e servidor devem receber esses dados. TCP ou Transmission Control Protocol é o protocolo mais conhecido na quarta camada. É responsável por garantir que os dados cheguem aos aplicativos corretos em execução nos nós. UDP ou User Datagram Protocol: A diferença entre UDP e TCP é que o TCP oferece mecanismos para que os dados sejam entregues de forma confiável, enquanto o UDP não tem esses mecanismos. |
| Application      | HTTP, SMTP, etc.., Messages         | Existem muitos protocolos diferentes nessa camada, e cada protocolo é específico de uma aplicação. Os protocolos para navegar na web ou receber emails são os mais comuns. |


Outro Modelo de rede é OSI:  https://en.wikipedia.org/wiki/OSI_model