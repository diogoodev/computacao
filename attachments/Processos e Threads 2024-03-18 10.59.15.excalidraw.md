---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
Processos e Threads ^iqwkkoow

processo: é uma abstração de um programa 
em execução ^dAjmoBIb

solicitação chega ^jwDeXKNB

servidor ^BO6pHaxe

a pagina esta em cache? ^m0zpDRKI

sim ^wFMHy5ME

não ^xiTL5CLg

solicitação 
enviada de volta ^FS7NjAjY

Solicitação de acesso 
ao disco se inicia ^NwdvWoO0

Os processo ajudam a lidar com diversas solicitações de acesso ao disco
pois do ponto de vista da cpu essa solicitação levaria muito tempo
para ser executada impedindo outros processos de acontecerem.
 ^cT17Ibxb

CPU executa apenas um processo, no curso de 1s ela pode trabalhar
 em vários deles, dando a ilusão de paralelismo ^ynetPHVs

Um processo é apenas uma instância de um programa em execução,
incluindo os valores atuais do contador do programa, 
registradores e variáveis. ^69Xkaq22

processo ^NZvS4IGx

tempo ^Kpfw8sk9

Programa: é algo que pode ser armazenado em disco 
sem fazer nada ^9kD8TAje

processo:  é uma atividade de algum tipo. Ela tem um programa,
uma entrada, uma saída e um estado ^fGYRN1s2

Eventos principais que fazem com que os processos sejam criados: 

    1. Inicialização do sistema. 
    2. Execução de uma chamada de sistema de criação de processo 
    por um processo em execução. 
    3. Solicitação de um usuário para criar um novo processo. 
    4. Início de uma tarefa em lote. ^WyI1ay6F

daemons: processos executados em segundo plano ^4H9Q8Xht

Os processos terminam, normalmente devido a uma das condições a seguir:
    1. Saída normal (voluntária). 
    2. Erro fatal (involuntário). 
    3. Saída por erro (voluntária). 
    4. Morto por outro processo (involuntário). ^7dzvh7Qx

1. Em execução (realmente usando a CPU naquele instante).
2. Pronto (executável, temporariamente parado para deixar outro processo ser executado).
3. Bloqueado (incapaz de ser executado até que al- gum evento externo aconteça). ^AJi6zqfx

Estados em que um processo pode se encontrar: ^Qzw9KhGn

Em execução ^r2EteJT1

pronto ^A3YTZdqj

Bloqueado ^g0HYqrgo

Os processos não são indepentendes ^3oSMh2Mb

Multiprogramação deixa que os processos usem a CPU 
quando ela estaria em outras circunstâncias ociosa ^15t2KnWe

Acrescentar mais memoria, não necessariamente leva uma melhora no desempenho da CPU ^EbzZh1a3

PROCESSOS ^IlwIwopD

Threads ^TJeqoCka

cada processo tem um espaço de endereçamento e um único thread de controle. ^093EQ0WX

Em um cenário ideal  múltiplos threads possuem o espaço de endereçamento compartilhado  ^WfXnrMil

A principal razão para se ter threads é que em muitas aplicações múltiplas atividades
 estão ocorrendo simultaneamente e algumas delas podem bloquear de tempos em tempos ^NJFLxuRm

Threads são mais leves, mais faceis de criar e de destruir do que processos. ^GgAHllC5

Ganho de desempenho em situações com muita computação e entradas e saidas, pois permite 
a sobreposição. ^usW87RQi

Deve ficar claro que ter três processos em separado não funcionaria aqui, pois todos 
os três threads precisam operar no documento. Ao existirem três threads em vez de três
 processos, eles compartilham de uma memória comum e desse modo têm acesso 
ao documento que está sendo editado. Com três processos isso seria impossível ^E958Xkl3

Um projeto no qual cada computação tem um estado salvo e existe algum conjunto 
de even- tos que pode ocorrer para mudar o estado, é chamado de máquina de 
estados finitos ^EzVPOlOq

uma solução: o processo pode- ria ser estruturado com um thread de entrada, 
um de processamento e um de saída. O thread de entrada lê dados para um buffer
de entrada; o thread de processa- mento pega os dados do buffer de entrada, 
processa-os e coloca os resultados no buffer de saída; e o thread de saída escreve esses
resultados de volta para o disc ^TRNh372M

aplicações que precisam processar grandes quantidades de dados ^3yZupmwt


# Embedded files
720ebb6e76344c59774f084cf7425eb25d7e2a29: [[Pasted Image 20240320121623_782.png]]

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.0.25",
	"elements": [
		{
			"type": "text",
			"version": 222,
			"versionNonce": 1666431509,
			"isDeleted": false,
			"id": "iqwkkoow",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -263.6041651668712,
			"y": -743.7734316094987,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 530.77685546875,
			"height": 63.34057617187497,
			"seed": 517217250,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"fontSize": 50.67246093749998,
			"fontFamily": 1,
			"text": "Processos e Threads",
			"rawText": "Processos e Threads",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Processos e Threads",
			"lineHeight": 1.25,
			"baseline": 44
		},
		{
			"type": "arrow",
			"version": 33,
			"versionNonce": 2020367803,
			"isDeleted": false,
			"id": "dtSqoyJBLqSkiCC_RK9Jg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -251.89664913827625,
			"y": -455.4374754163954,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.191071686921305,
			"height": 1.3524034288194002,
			"seed": 304606178,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					37.191071686921305,
					1.3524034288194002
				]
			]
		},
		{
			"type": "text",
			"version": 37,
			"versionNonce": 1499311989,
			"isDeleted": false,
			"id": "dAjmoBIb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -194.58929417589195,
			"y": -470.52204301622174,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 443.73944091796875,
			"height": 50,
			"seed": 637784930,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "processo: é uma abstração de um programa \nem execução",
			"rawText": "processo: é uma abstração de um programa \nem execução",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "processo: é uma abstração de um programa \nem execução",
			"lineHeight": 1.25,
			"baseline": 42
		},
		{
			"type": "arrow",
			"version": 407,
			"versionNonce": 1076427221,
			"isDeleted": false,
			"id": "iS3xeft6iF2cmrEoHFw6k",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -27.626435548377607,
			"y": -365.1673039058676,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.531729819085939,
			"height": 44.90428993614796,
			"seed": 888316286,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947783867,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "jwDeXKNB",
				"gap": 5.064518681278912,
				"focus": 0.08176710813157081
			},
			"endBinding": {
				"elementId": "HGLvAC9_4jsvN1EnYQrHk",
				"gap": 13.642883808219267,
				"focus": -0.10503722442743674
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					2.531729819085939,
					44.90428993614796
				]
			]
		},
		{
			"type": "text",
			"version": 88,
			"versionNonce": 1497495765,
			"isDeleted": false,
			"id": "jwDeXKNB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -106.29660921328514,
			"y": -395.2318225871465,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 169.31979370117188,
			"height": 25,
			"seed": 1371586274,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "iS3xeft6iF2cmrEoHFw6k",
					"type": "arrow"
				},
				{
					"id": "LwHJ7Xu71zXC-zubEoyQN",
					"type": "arrow"
				}
			],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "solicitação chega",
			"rawText": "solicitação chega",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "solicitação chega",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "diamond",
			"version": 166,
			"versionNonce": 1318480635,
			"isDeleted": false,
			"id": "HGLvAC9_4jsvN1EnYQrHk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -130.76871274360263,
			"y": -316.09238755084544,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 247.38793945312503,
			"height": 170,
			"seed": 1876192318,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "iS3xeft6iF2cmrEoHFw6k",
					"type": "arrow"
				},
				{
					"id": "etBPHC16eBFR1Zts9VPHR",
					"type": "arrow"
				},
				{
					"type": "text",
					"id": "m0zpDRKI"
				},
				{
					"id": "Gd4F17uvWdgWshDAtjfga",
					"type": "arrow"
				},
				{
					"id": "_ZpxNHYbfYqpuLAU4OP3f",
					"type": "arrow"
				}
			],
			"updated": 1710947711078,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 187,
			"versionNonce": 1553339957,
			"isDeleted": false,
			"id": "m0zpDRKI",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -48.731672033153416,
			"y": -268.59238755084544,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 83.61988830566406,
			"height": 75,
			"seed": 495241854,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "a pagina\nesta em\ncache?",
			"rawText": "a pagina esta em cache?",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "HGLvAC9_4jsvN1EnYQrHk",
			"originalText": "a pagina esta em cache?",
			"lineHeight": 1.25,
			"baseline": 67
		},
		{
			"type": "text",
			"version": 150,
			"versionNonce": 1881494427,
			"isDeleted": false,
			"id": "BO6pHaxe",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -193.83341000922763,
			"y": -313.8999437031892,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 76.29991149902344,
			"height": 25,
			"seed": 168111550,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "etBPHC16eBFR1Zts9VPHR",
					"type": "arrow"
				}
			],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "servidor",
			"rawText": "servidor",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "servidor",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 346,
			"versionNonce": 821360437,
			"isDeleted": false,
			"id": "etBPHC16eBFR1Zts9VPHR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -116.5334985102042,
			"y": -298.5204150272106,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 63.869069510095464,
			"height": 19.1879681300548,
			"seed": 327887614,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947783868,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "BO6pHaxe",
				"focus": 0.7018974612839392,
				"gap": 1
			},
			"endBinding": {
				"elementId": "HGLvAC9_4jsvN1EnYQrHk",
				"gap": 10.005597577775887,
				"focus": 0.3796468881432472
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					36.88551330566406,
					-17.571911488478577
				],
				[
					63.869069510095464,
					1.6160566415762219
				]
			]
		},
		{
			"type": "arrow",
			"version": 244,
			"versionNonce": 370821269,
			"isDeleted": false,
			"id": "Gd4F17uvWdgWshDAtjfga",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -130.14280358437668,
			"y": -229.44892627862174,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 58.136773417038455,
			"height": 188.95852847387005,
			"seed": 1329697022,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947783868,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "HGLvAC9_4jsvN1EnYQrHk",
				"gap": 1.0000000000000142,
				"focus": 0.9869567419047655
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-58.136773417038455,
					96.75857730199505
				],
				[
					-55.398003885788455,
					188.95852847387005
				]
			]
		},
		{
			"type": "arrow",
			"version": 359,
			"versionNonce": 1095658997,
			"isDeleted": false,
			"id": "_ZpxNHYbfYqpuLAU4OP3f",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 119.28673068890575,
			"y": -224.5219185453067,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 110.86855191704782,
			"height": 156.927782672278,
			"seed": 1426032318,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947783868,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "HGLvAC9_4jsvN1EnYQrHk",
				"gap": 6.925891088159673,
				"focus": -0.8108688774438934
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					89.53256926280412,
					53.49099339680501
				],
				[
					110.86855191704782,
					156.927782672278
				]
			]
		},
		{
			"type": "text",
			"version": 66,
			"versionNonce": 724789467,
			"isDeleted": false,
			"id": "wFMHy5ME",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 221.59945131889737,
			"y": -199.82886826373607,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 27.89996337890625,
			"height": 25,
			"seed": 1470345186,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "sim",
			"rawText": "sim",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "sim",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 62,
			"versionNonce": 1656251989,
			"isDeleted": false,
			"id": "xiTL5CLg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -225.70725034125888,
			"y": -185.22291123248607,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 33.75996398925781,
			"height": 25,
			"seed": 955002338,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "não",
			"rawText": "não",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "não",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 127,
			"versionNonce": 271029627,
			"isDeleted": false,
			"id": "FS7NjAjY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 178.94407106987393,
			"y": -49.453410500064194,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 166.93980407714844,
			"height": 50,
			"seed": 1029864098,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "LwHJ7Xu71zXC-zubEoyQN",
					"type": "arrow"
				}
			],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "solicitação \nenviada de volta",
			"rawText": "solicitação \nenviada de volta",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "solicitação \nenviada de volta",
			"lineHeight": 1.25,
			"baseline": 42
		},
		{
			"type": "arrow",
			"version": 308,
			"versionNonce": 400741301,
			"isDeleted": false,
			"id": "LwHJ7Xu71zXC-zubEoyQN",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 356.70430971733487,
			"y": -30.947734230532944,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 392.5345458984375,
			"height": 348.71673583984375,
			"seed": 893011070,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "6y6Mf0t7F-6PfGhN1VSNT",
				"focus": 0.8636970520345497,
				"gap": 3.7345864371282147
			},
			"endBinding": {
				"elementId": "jwDeXKNB",
				"focus": -0.7719503500242407,
				"gap": 6.126803940385628
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					104.980224609375,
					-152.449462890625
				],
				[
					-287.5543212890625,
					-348.71673583984375
				]
			]
		},
		{
			"type": "text",
			"version": 116,
			"versionNonce": 1798123035,
			"isDeleted": false,
			"id": "NwdvWoO0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -244.87759946235263,
			"y": -18.167582863345444,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 225.8397216796875,
			"height": 50,
			"seed": 482410658,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Solicitação de acesso \nao disco se inicia",
			"rawText": "Solicitação de acesso \nao disco se inicia",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Solicitação de acesso \nao disco se inicia",
			"lineHeight": 1.25,
			"baseline": 42
		},
		{
			"type": "ellipse",
			"version": 113,
			"versionNonce": 202937621,
			"isDeleted": false,
			"id": "5j7MwAyzv5y-6kB2k6raq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -276.82803891547763,
			"y": -47.379435890689194,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 268.384033203125,
			"height": 133.27915954589844,
			"seed": 911422782,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 103,
			"versionNonce": 1328984763,
			"isDeleted": false,
			"id": "6y6Mf0t7F-6PfGhN1VSNT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 114.79354311577237,
			"y": -74.7654985127595,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 241.9107666015625,
			"height": 118.6732177734375,
			"seed": 522227134,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "LwHJ7Xu71zXC-zubEoyQN",
					"type": "arrow"
				}
			],
			"updated": 1710947711078,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 56,
			"versionNonce": 1791961717,
			"isDeleted": false,
			"id": "3e2wHtWSxgZnUOMZAvOif",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -254.29214745581774,
			"y": 171.24628839358724,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.191071686921305,
			"height": 1.3524034288194002,
			"seed": 2141156286,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "cT17Ibxb",
				"focus": 0.5302327046255776,
				"gap": 19.956854706061335
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					37.191071686921305,
					1.3524034288194002
				]
			]
		},
		{
			"type": "text",
			"version": 230,
			"versionNonce": 1290183515,
			"isDeleted": false,
			"id": "cT17Ibxb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -197.14422106283507,
			"y": 170.24097986411175,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 733.3992309570312,
			"height": 100,
			"seed": 1623582050,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "3e2wHtWSxgZnUOMZAvOif",
					"type": "arrow"
				}
			],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Os processo ajudam a lidar com diversas solicitações de acesso ao disco\npois do ponto de vista da cpu essa solicitação levaria muito tempo\npara ser executada impedindo outros processos de acontecerem.\n",
			"rawText": "Os processo ajudam a lidar com diversas solicitações de acesso ao disco\npois do ponto de vista da cpu essa solicitação levaria muito tempo\npara ser executada impedindo outros processos de acontecerem.\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Os processo ajudam a lidar com diversas solicitações de acesso ao disco\npois do ponto de vista da cpu essa solicitação levaria muito tempo\npara ser executada impedindo outros processos de acontecerem.\n",
			"lineHeight": 1.25,
			"baseline": 92
		},
		{
			"type": "arrow",
			"version": 137,
			"versionNonce": 1422660565,
			"isDeleted": false,
			"id": "efxzqvIgFK5nMybWDNbig",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -246.8295383769777,
			"y": 295.3855717458091,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 38.151957788894975,
			"height": 1.8395941621024008,
			"seed": 1018346210,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "ynetPHVs",
				"focus": -0.10691960125538645,
				"gap": 14.013828275247647
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					38.151957788894975,
					1.8395941621024008
				]
			]
		},
		{
			"type": "text",
			"version": 46,
			"versionNonce": 1016037371,
			"isDeleted": false,
			"id": "ynetPHVs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -194.66375231283507,
			"y": 285.02575062891447,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 687.2792358398438,
			"height": 50,
			"seed": 1229803198,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "efxzqvIgFK5nMybWDNbig",
					"type": "arrow"
				}
			],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "CPU executa apenas um processo, no curso de 1s ela pode trabalhar\n em vários deles, dando a ilusão de paralelismo",
			"rawText": "CPU executa apenas um processo, no curso de 1s ela pode trabalhar\n em vários deles, dando a ilusão de paralelismo",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CPU executa apenas um processo, no curso de 1s ela pode trabalhar\n em vários deles, dando a ilusão de paralelismo",
			"lineHeight": 1.25,
			"baseline": 42
		},
		{
			"type": "text",
			"version": 17,
			"versionNonce": 908382517,
			"isDeleted": false,
			"id": "69Xkaq22",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -172.79402061053244,
			"y": 378.30353126213816,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 665.499267578125,
			"height": 75,
			"seed": 2056979646,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Um processo é apenas uma instância de um programa em execução,\nincluindo os valores atuais do contador do programa, \nregistradores e variáveis.",
			"rawText": "Um processo é apenas uma instância de um programa em execução,\nincluindo os valores atuais do contador do programa, \nregistradores e variáveis.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Um processo é apenas uma instância de um programa em execução,\nincluindo os valores atuais do contador do programa, \nregistradores e variáveis.",
			"lineHeight": 1.25,
			"baseline": 67
		},
		{
			"type": "arrow",
			"version": 154,
			"versionNonce": 1211353243,
			"isDeleted": false,
			"id": "yWS3-ierPyJaf0eUErV1v",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -230.52916251358684,
			"y": 386.2532319260391,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 38.151957788894975,
			"height": 1.8395941621024008,
			"seed": 1704086434,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					38.151957788894975,
					1.8395941621024008
				]
			]
		},
		{
			"type": "arrow",
			"version": 150,
			"versionNonce": 1547625109,
			"isDeleted": false,
			"id": "-VNCLWydr4JUrvhrvFr2Q",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -166.38070338191403,
			"y": 783.6663692041611,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 10.57013260690789,
			"height": 293.07964124177624,
			"seed": 33692158,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-10.57013260690789,
					-293.07964124177624
				]
			]
		},
		{
			"type": "arrow",
			"version": 261,
			"versionNonce": 897973563,
			"isDeleted": false,
			"id": "5DbnKzaXvkNcKwalud-XK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -169.74870404712428,
			"y": 780.7675303019837,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 283.470394736842,
			"height": 0.00009637129926431953,
			"seed": 852387710,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					283.470394736842,
					-0.00009637129926431953
				]
			]
		},
		{
			"type": "line",
			"version": 20,
			"versionNonce": 1271908341,
			"isDeleted": false,
			"id": "8VI_VwZhryIezfC06X5Au",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -147.16246736217718,
			"y": 697.1838252588486,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 36.51482833059211,
			"height": 0,
			"seed": 1304296446,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					36.51482833059211,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 22,
			"versionNonce": 1877515739,
			"isDeleted": false,
			"id": "BICFl9RquJgPeFkR8TC2c",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -99.59505960741262,
			"y": 668.2331577968217,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 36.51482833059211,
			"height": 0,
			"seed": 1174804670,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					36.51482833059211,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 22,
			"versionNonce": 1457324373,
			"isDeleted": false,
			"id": "2aiqMcZpIFQ3ciqAKt43t",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -58.54242802846528,
			"y": 628.2331577968217,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 36.51482833059211,
			"height": 0,
			"seed": 1367517566,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					36.51482833059211,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 22,
			"versionNonce": 1382951547,
			"isDeleted": false,
			"id": "iwW02r7mOBCNbpcOwx4I6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -12.226638554781061,
			"y": 586.1278946389269,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 36.51482833059211,
			"height": 0,
			"seed": 248300770,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					36.51482833059211,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 22,
			"versionNonce": 1924927157,
			"isDeleted": false,
			"id": "MnnzxkPPDii2Uc1CJUSiy",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 45.668098287324185,
			"y": 747.1805262178742,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 36.51482833059211,
			"height": 0,
			"seed": 1576204990,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					36.51482833059211,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 22,
			"versionNonce": 836313883,
			"isDeleted": false,
			"id": "XrnMcZnG0ZFDcJpnhTTuj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 87.77336144521892,
			"y": 709.285789375769,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 36.51482833059211,
			"height": 0,
			"seed": 1997240226,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711078,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					36.51482833059211,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 59,
			"versionNonce": 1309831189,
			"isDeleted": false,
			"id": "NZvS4IGx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.695540106348009,
			"x": -249.0420931845456,
			"y": 648.6464203451973,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 83.31990051269531,
			"height": 25,
			"seed": 1901976766,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "processo",
			"rawText": "processo",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "processo",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 37,
			"versionNonce": 647759803,
			"isDeleted": false,
			"id": "Kpfw8sk9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -80.67744988684825,
			"y": 801.3696805220065,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 55.839935302734375,
			"height": 25,
			"seed": 428435234,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "tempo",
			"rawText": "tempo",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "tempo",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 39,
			"versionNonce": 651535733,
			"isDeleted": false,
			"id": "foL7nGSs272_rqdhqICuI",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -219.2312379213877,
			"y": 923.2559238402631,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 66.30319695723682,
			"height": 2.8938906203505894,
			"seed": 1819131390,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "9kD8TAje",
				"focus": -0.18058855700109167,
				"gap": 11.250256990131561
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					66.30319695723682,
					2.8938906203505894
				]
			]
		},
		{
			"type": "text",
			"version": 15,
			"versionNonce": 383342683,
			"isDeleted": false,
			"id": "9kD8TAje",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -141.6777839740193,
			"y": 906.6286944508718,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 531.3993530273438,
			"height": 50,
			"seed": 1568429666,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "foL7nGSs272_rqdhqICuI",
					"type": "arrow"
				}
			],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Programa: é algo que pode ser armazenado em disco \nsem fazer nada",
			"rawText": "Programa: é algo que pode ser armazenado em disco \nsem fazer nada",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Programa: é algo que pode ser armazenado em disco \nsem fazer nada",
			"lineHeight": 1.25,
			"baseline": 42
		},
		{
			"type": "arrow",
			"version": 65,
			"versionNonce": 1615539925,
			"isDeleted": false,
			"id": "SmlRG7c29mrzdjqV5guN_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -209.1141802927535,
			"y": 1008.0862744866664,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 57.65496504934211,
			"height": 2.907445650993509,
			"seed": 1259570366,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					57.65496504934211,
					2.907445650993509
				]
			]
		},
		{
			"type": "text",
			"version": 18,
			"versionNonce": 6526203,
			"isDeleted": false,
			"id": "fGYRN1s2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -134.44068487862455,
			"y": 998.3431398661677,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 639.4392700195312,
			"height": 50,
			"seed": 1723196990,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "processo:  é uma atividade de algum tipo. Ela tem um programa,\numa entrada, uma saída e um estado",
			"rawText": "processo:  é uma atividade de algum tipo. Ela tem um programa,\numa entrada, uma saída e um estado",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "processo:  é uma atividade de algum tipo. Ela tem um programa,\numa entrada, uma saída e um estado",
			"lineHeight": 1.25,
			"baseline": 42
		},
		{
			"type": "text",
			"version": 53,
			"versionNonce": 1493732405,
			"isDeleted": false,
			"id": "WyI1ay6F",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -144.3902742762655,
			"y": 1099.9628408602305,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 700.3391723632812,
			"height": 175,
			"seed": 1230361726,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "w2W_UqKaJPRFhXWsh4PNl",
					"type": "arrow"
				}
			],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Eventos principais que fazem com que os processos sejam criados: \n\n    1. Inicialização do sistema. \n    2. Execução de uma chamada de sistema de criação de processo \n    por um processo em execução. \n    3. Solicitação de um usuário para criar um novo processo. \n    4. Início de uma tarefa em lote.",
			"rawText": "Eventos principais que fazem com que os processos sejam criados: \n\n    1. Inicialização do sistema. \n    2. Execução de uma chamada de sistema de criação de processo \n    por um processo em execução. \n    3. Solicitação de um usuário para criar um novo processo. \n    4. Início de uma tarefa em lote.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Eventos principais que fazem com que os processos sejam criados: \n\n    1. Inicialização do sistema. \n    2. Execução de uma chamada de sistema de criação de processo \n    por um processo em execução. \n    3. Solicitação de um usuário para criar um novo processo. \n    4. Início de uma tarefa em lote.",
			"lineHeight": 1.25,
			"baseline": 167
		},
		{
			"type": "arrow",
			"version": 148,
			"versionNonce": 45956507,
			"isDeleted": false,
			"id": "w2W_UqKaJPRFhXWsh4PNl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -214.52132487231182,
			"y": 1108.9103804976505,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 61.30649499725888,
			"height": 5.82614668930114,
			"seed": 1701661950,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "WyI1ay6F",
				"focus": 0.31967808510374424,
				"gap": 8.82455559878747
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					61.30649499725888,
					5.82614668930114
				]
			]
		},
		{
			"type": "text",
			"version": 98,
			"versionNonce": 15941013,
			"isDeleted": false,
			"id": "4H9Q8Xht",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -108.4405672450155,
			"y": 1332.9977529696057,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 488.5594482421875,
			"height": 25,
			"seed": 2102327842,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "daemons: processos executados em segundo plano",
			"rawText": "daemons: processos executados em segundo plano",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "daemons: processos executados em segundo plano",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 89,
			"versionNonce": 689492539,
			"isDeleted": false,
			"id": "euSst__GNgisKMDqe8hoj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -187.22363607022848,
			"y": 1339.5110478153588,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 57.65496504934211,
			"height": 2.907445650993509,
			"seed": 594666110,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					23.421415179379665,
					2.766897211538435
				],
				[
					57.65496504934211,
					2.907445650993509
				]
			]
		},
		{
			"type": "text",
			"version": 87,
			"versionNonce": 792773365,
			"isDeleted": false,
			"id": "7dzvh7Qx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -104.37953208876553,
			"y": 1394.1093252352302,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 732.7591552734375,
			"height": 125,
			"seed": 1491850302,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "g-jibbtatDn6YepxMDxg2",
					"type": "arrow"
				}
			],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Os processos terminam, normalmente devido a uma das condições a seguir:\n    1. Saída normal (voluntária). \n    2. Erro fatal (involuntário). \n    3. Saída por erro (voluntária). \n    4. Morto por outro processo (involuntário).",
			"rawText": "Os processos terminam, normalmente devido a uma das condições a seguir:\n    1. Saída normal (voluntária). \n    2. Erro fatal (involuntário). \n    3. Saída por erro (voluntária). \n    4. Morto por outro processo (involuntário).",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Os processos terminam, normalmente devido a uma das condições a seguir:\n    1. Saída normal (voluntária). \n    2. Erro fatal (involuntário). \n    3. Saída por erro (voluntária). \n    4. Morto por outro processo (involuntário).",
			"lineHeight": 1.25,
			"baseline": 117
		},
		{
			"type": "arrow",
			"version": 199,
			"versionNonce": 1951978203,
			"isDeleted": false,
			"id": "g-jibbtatDn6YepxMDxg2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -193.8147492875603,
			"y": 1399.5106530343792,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 68.60922937225865,
			"height": 2.5824662260522473,
			"seed": 605679522,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "7dzvh7Qx",
				"focus": 0.6204261051171189,
				"gap": 20.825987826536107
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					28.290067523129665,
					1.5497748157051774
				],
				[
					68.60922937225865,
					2.5824662260522473
				]
			]
		},
		{
			"type": "arrow",
			"version": 227,
			"versionNonce": 947297365,
			"isDeleted": false,
			"id": "c7R-rrT3irmKE4j_9aYqx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -167.34507315210823,
			"y": 1585.1393313646693,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 68.60922937225865,
			"height": 2.5824662260522473,
			"seed": 1304497634,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "Qzw9KhGn",
				"focus": -0.29222552172890315,
				"gap": 13.447430397681387
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					28.290067523129665,
					1.5497748157051774
				],
				[
					68.60922937225865,
					2.5824662260522473
				]
			]
		},
		{
			"type": "text",
			"version": 52,
			"versionNonce": 621789051,
			"isDeleted": false,
			"id": "AJi6zqfx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -106.28938994466822,
			"y": 1627.6979008103172,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 914.3790283203125,
			"height": 75,
			"seed": 771393250,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1. Em execução (realmente usando a CPU naquele instante).\n2. Pronto (executável, temporariamente parado para deixar outro processo ser executado).\n3. Bloqueado (incapaz de ser executado até que al- gum evento externo aconteça).",
			"rawText": "1. Em execução (realmente usando a CPU naquele instante).\n2. Pronto (executável, temporariamente parado para deixar outro processo ser executado).\n3. Bloqueado (incapaz de ser executado até que al- gum evento externo aconteça).",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1. Em execução (realmente usando a CPU naquele instante).\n2. Pronto (executável, temporariamente parado para deixar outro processo ser executado).\n3. Bloqueado (incapaz de ser executado até que al- gum evento externo aconteça).",
			"lineHeight": 1.25,
			"baseline": 67
		},
		{
			"type": "text",
			"version": 63,
			"versionNonce": 1147816373,
			"isDeleted": false,
			"id": "Qzw9KhGn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -85.28841338216819,
			"y": 1576.2545549986853,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 478.93951416015625,
			"height": 25,
			"seed": 2104983294,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "c7R-rrT3irmKE4j_9aYqx",
					"type": "arrow"
				}
			],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Estados em que um processo pode se encontrar:",
			"rawText": "Estados em que um processo pode se encontrar:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Estados em que um processo pode se encontrar:",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "ellipse",
			"version": 23,
			"versionNonce": 1166022683,
			"isDeleted": false,
			"id": "tHt8rtPG7bAzifiBmx_K8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -47.370390378696015,
			"y": 1809.2245596102302,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 322.54774305555543,
			"height": 48.68645562065967,
			"seed": 1277893538,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "5f-RMA495Q6pgPps2V7ES",
					"type": "arrow"
				},
				{
					"id": "GS9slFDpC25A8108nEJ68",
					"type": "arrow"
				}
			],
			"updated": 1710947711079,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 46,
			"versionNonce": 1682000661,
			"isDeleted": false,
			"id": "kxakiqRvBB7ymXv8mxy1Q",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -158.9434698057793,
			"y": 2027.2993073315843,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 258.6467827690971,
			"height": 82.15833875868066,
			"seed": 175945378,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "3nC0jN91f6-gwQ1YOnTKe",
					"type": "arrow"
				},
				{
					"id": "x8hyxSJ5jsETwUz_soQkD",
					"type": "arrow"
				},
				{
					"type": "text",
					"id": "g0HYqrgo"
				}
			],
			"updated": 1710947711079,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 28,
			"versionNonce": 1939627195,
			"isDeleted": false,
			"id": "g0HYqrgo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -79.51546897776744,
			"y": 2055.8311174772825,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 99.89988708496094,
			"height": 25,
			"seed": 383712098,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Bloqueado",
			"rawText": "Bloqueado",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "kxakiqRvBB7ymXv8mxy1Q",
			"originalText": "Bloqueado",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "ellipse",
			"version": 32,
			"versionNonce": 1752244341,
			"isDeleted": false,
			"id": "wyvSkcmEwnSwciKMp7vMU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 212.29066105359556,
			"y": 2003.970382092869,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 375.2913411458332,
			"height": 101.4300537109375,
			"seed": 1310677986,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "5f-RMA495Q6pgPps2V7ES",
					"type": "arrow"
				},
				{
					"id": "GS9slFDpC25A8108nEJ68",
					"type": "arrow"
				},
				{
					"id": "3nC0jN91f6-gwQ1YOnTKe",
					"type": "arrow"
				}
			],
			"updated": 1710947711079,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 51,
			"versionNonce": 1795624283,
			"isDeleted": false,
			"id": "5f-RMA495Q6pgPps2V7ES",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 219.39081296331779,
			"y": 2032.370786281237,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 89.25849066840277,
			"height": 165.3310818142361,
			"seed": 1672991970,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "wyvSkcmEwnSwciKMp7vMU",
				"focus": -0.8266557704559852,
				"gap": 6.504558905235271
			},
			"endBinding": {
				"elementId": "tHt8rtPG7bAzifiBmx_K8",
				"focus": -0.04438141461472228,
				"gap": 9.251186528919966
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-62.886691623263914,
					-67.95817057291652
				],
				[
					-89.25849066840277,
					-165.3310818142361
				]
			]
		},
		{
			"type": "arrow",
			"version": 42,
			"versionNonce": 1992247765,
			"isDeleted": false,
			"id": "GS9slFDpC25A8108nEJ68",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 281.26310028970664,
			"y": 1843.710779228286,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 82.15847439236103,
			"height": 157.21666124131934,
			"seed": 1503089854,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "tHt8rtPG7bAzifiBmx_K8",
				"focus": -0.9148205993002709,
				"gap": 10.207793583528513
			},
			"endBinding": {
				"elementId": "wyvSkcmEwnSwciKMp7vMU",
				"focus": -0.2355089496103466,
				"gap": 4.296044074246296
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					82.15847439236103,
					52.74366590711793
				],
				[
					77.08685980902777,
					157.21666124131934
				]
			]
		},
		{
			"type": "arrow",
			"version": 70,
			"versionNonce": 831973205,
			"isDeleted": false,
			"id": "3nC0jN91f6-gwQ1YOnTKe",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 100.29977773942508,
			"y": 2074.5534559716925,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 119.0910352238927,
			"height": 47.672119140625,
			"seed": 255411170,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947783870,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "kxakiqRvBB7ymXv8mxy1Q",
				"gap": 1.9549686119916032,
				"focus": -0.8462529373201346
			},
			"endBinding": {
				"elementId": "wyvSkcmEwnSwciKMp7vMU",
				"focus": 0.8244250546202785,
				"gap": 2.544455759654113
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					66.34730149993439,
					45.04721583471837
				],
				[
					119.0910352238927,
					-2.624903305906628
				]
			]
		},
		{
			"type": "arrow",
			"version": 73,
			"versionNonce": 1766405301,
			"isDeleted": false,
			"id": "x8hyxSJ5jsETwUz_soQkD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -29.113011906473815,
			"y": 1832.5534848489456,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 92.30129665798607,
			"height": 185.7911929551019,
			"seed": 383638590,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947783870,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "kxakiqRvBB7ymXv8mxy1Q",
				"gap": 15.080502254083811,
				"focus": -0.4005788104757492
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-92.30129665798607,
					89.25849066840283
				],
				[
					-66.08945593048603,
					185.7911929551019
				]
			]
		},
		{
			"type": "text",
			"version": 37,
			"versionNonce": 885109403,
			"isDeleted": false,
			"id": "r2EteJT1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 55.037378718526156,
			"y": 1821.4096182039802,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 125.11985778808594,
			"height": 25,
			"seed": 8328034,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Em execução",
			"rawText": "Em execução",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Em execução",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 54,
			"versionNonce": 928815253,
			"isDeleted": false,
			"id": "A3YTZdqj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 357.3672940831094,
			"y": 2038.4326623663064,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 61.25993347167969,
			"height": 25,
			"seed": 1544816994,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "pronto",
			"rawText": "pronto",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "pronto",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 236,
			"versionNonce": 1824958267,
			"isDeleted": false,
			"id": "Q9MYcrqutvTLPrfVnVSYP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -145.76592841587902,
			"y": 2199.337456631556,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 68.60922937225865,
			"height": 2.5824662260522473,
			"seed": 2043759230,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					28.290067523129665,
					1.5497748157051774
				],
				[
					68.60922937225865,
					2.5824662260522473
				]
			]
		},
		{
			"type": "text",
			"version": 50,
			"versionNonce": 633781749,
			"isDeleted": false,
			"id": "3oSMh2Mb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -32.8387778724898,
			"y": 2195.2370830196187,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 359.5395812988281,
			"height": 25,
			"seed": 2121393406,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Os processos não são indepentendes",
			"rawText": "Os processos não são indepentendes",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Os processos não são indepentendes",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 33,
			"versionNonce": 226756571,
			"isDeleted": false,
			"id": "15t2KnWe",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -50.40375683883596,
			"y": 2244.440808981157,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 549.7393188476562,
			"height": 50,
			"seed": 559142242,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Multiprogramação deixa que os processos usem a CPU \nquando ela estaria em outras circunstâncias ociosa",
			"rawText": "Multiprogramação deixa que os processos usem a CPU \nquando ela estaria em outras circunstâncias ociosa",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Multiprogramação deixa que os processos usem a CPU \nquando ela estaria em outras circunstâncias ociosa",
			"lineHeight": 1.25,
			"baseline": 42
		},
		{
			"type": "arrow",
			"version": 238,
			"versionNonce": 42284885,
			"isDeleted": false,
			"id": "qF2ECxvkNCPomc_iLc2_d",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -142.16300273685295,
			"y": 2255.418757519111,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 68.60922937225865,
			"height": 2.5824662260522473,
			"seed": 901059682,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					28.290067523129665,
					1.5497748157051774
				],
				[
					68.60922937225865,
					2.5824662260522473
				]
			]
		},
		{
			"type": "arrow",
			"version": 240,
			"versionNonce": 1024218235,
			"isDeleted": false,
			"id": "SJFlNgbRcnqnK-mMWeZwO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -121.73312482002234,
			"y": 2364.0514313775093,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 68.60922937225865,
			"height": 2.5824662260522473,
			"seed": 422906466,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					28.290067523129665,
					1.5497748157051774
				],
				[
					68.60922937225865,
					2.5824662260522473
				]
			]
		},
		{
			"type": "text",
			"version": 117,
			"versionNonce": 669877429,
			"isDeleted": false,
			"id": "EbzZh1a3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -15.777855396528253,
			"y": 2360.2793381277916,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 881.259033203125,
			"height": 25,
			"seed": 207211938,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Acrescentar mais memoria, não necessariamente leva uma melhora no desempenho da CPU",
			"rawText": "Acrescentar mais memoria, não necessariamente leva uma melhora no desempenho da CPU",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Acrescentar mais memoria, não necessariamente leva uma melhora no desempenho da CPU",
			"lineHeight": 1.25,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 68,
			"versionNonce": 992087323,
			"isDeleted": false,
			"id": "IlwIwopD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -257.5454335215282,
			"y": -567.3897162648752,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 226.5664520263672,
			"height": 47.75802487043194,
			"seed": 1098466878,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"fontSize": 38.20641989634555,
			"fontFamily": 1,
			"text": "PROCESSOS",
			"rawText": "PROCESSOS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "PROCESSOS",
			"lineHeight": 1.25,
			"baseline": 33
		},
		{
			"type": "text",
			"version": 61,
			"versionNonce": 161818133,
			"isDeleted": false,
			"id": "TJeqoCka",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -127.92103448306668,
			"y": 2467.0517051650513,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 213.15208435058594,
			"height": 65.72810246394214,
			"seed": 761450878,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"fontSize": 52.582481971153705,
			"fontFamily": 1,
			"text": "Threads",
			"rawText": "Threads",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Threads",
			"lineHeight": 1.25,
			"baseline": 46
		},
		{
			"type": "arrow",
			"version": 250,
			"versionNonce": 725070267,
			"isDeleted": false,
			"id": "lwJqx9FqffdOXZNmfOL6O",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -193.35432718763852,
			"y": 2594.9849268106013,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 68.60922937225865,
			"height": 2.5824662260522473,
			"seed": 918871803,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "093EQ0WX",
				"focus": -0.4691016021662874,
				"gap": 5.271596631156626
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					28.290067523129665,
					1.5497748157051774
				],
				[
					68.60922937225865,
					2.5824662260522473
				]
			]
		},
		{
			"id": "093EQ0WX",
			"type": "text",
			"x": -119.47350118422318,
			"y": 2584.7171348261422,
			"width": 791.0791625976562,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 66285883,
			"version": 35,
			"versionNonce": 178363253,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "lwJqx9FqffdOXZNmfOL6O",
					"type": "arrow"
				}
			],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"text": "cada processo tem um espaço de endereçamento e um único thread de controle.",
			"rawText": "cada processo tem um espaço de endereçamento e um único thread de controle.",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 17,
			"containerId": null,
			"originalText": "cada processo tem um espaço de endereçamento e um único thread de controle.",
			"lineHeight": 1.25
		},
		{
			"type": "arrow",
			"version": 257,
			"versionNonce": 510640731,
			"isDeleted": false,
			"id": "ufUkDlB8SjSEq5iLTtv5H",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -188.04263291102745,
			"y": 2656.1867333028777,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 68.60922937225865,
			"height": 2.5824662260522473,
			"seed": 1100441461,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "WfXnrMil",
				"focus": -0.30418177165057464,
				"gap": 10.328391937878962
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					28.290067523129665,
					1.5497748157051774
				],
				[
					68.60922937225865,
					2.5824662260522473
				]
			]
		},
		{
			"id": "WfXnrMil",
			"type": "text",
			"x": -109.1050116008899,
			"y": 2650.7422406204128,
			"width": 898.97900390625,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 81185749,
			"version": 84,
			"versionNonce": 321414357,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "ufUkDlB8SjSEq5iLTtv5H",
					"type": "arrow"
				}
			],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"text": "Em um cenário ideal  múltiplos threads possuem o espaço de endereçamento compartilhado ",
			"rawText": "Em um cenário ideal  múltiplos threads possuem o espaço de endereçamento compartilhado ",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 17,
			"containerId": null,
			"originalText": "Em um cenário ideal  múltiplos threads possuem o espaço de endereçamento compartilhado ",
			"lineHeight": 1.25
		},
		{
			"id": "NJFLxuRm",
			"type": "text",
			"x": -109.21064311130658,
			"y": 2721.0656862584337,
			"width": 884.0791015625,
			"height": 50,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 128195067,
			"version": 55,
			"versionNonce": 1570553595,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "Q9uMwSALfF8YtmCt9XFit",
					"type": "arrow"
				}
			],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"text": "A principal razão para se ter threads é que em muitas aplicações múltiplas atividades\n estão ocorrendo simultaneamente e algumas delas podem bloquear de tempos em tempos",
			"rawText": "A principal razão para se ter threads é que em muitas aplicações múltiplas atividades\n estão ocorrendo simultaneamente e algumas delas podem bloquear de tempos em tempos",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 42,
			"containerId": null,
			"originalText": "A principal razão para se ter threads é que em muitas aplicações múltiplas atividades\n estão ocorrendo simultaneamente e algumas delas podem bloquear de tempos em tempos",
			"lineHeight": 1.25
		},
		{
			"type": "arrow",
			"version": 284,
			"versionNonce": 1724842549,
			"isDeleted": false,
			"id": "Q9uMwSALfF8YtmCt9XFit",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -184.41262590767104,
			"y": 2733.4068644292142,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 68.60922937225865,
			"height": 2.5824662260522473,
			"seed": 918877851,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "NJFLxuRm",
				"focus": -0.03894141516940565,
				"gap": 6.592753424105808
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					28.290067523129665,
					1.5497748157051774
				],
				[
					68.60922937225865,
					2.5824662260522473
				]
			]
		},
		{
			"type": "arrow",
			"version": 317,
			"versionNonce": 1933649819,
			"isDeleted": false,
			"id": "SSKJKHO9NBSPLwwjRJggt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -182.35683093815018,
			"y": 2831.1952922887963,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 68.60922937225865,
			"height": 2.5824662260522473,
			"seed": 1030071701,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "GgAHllC5",
				"focus": -0.5092049565286249,
				"gap": 6.8497839754182905
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					28.290067523129665,
					1.5497748157051774
				],
				[
					68.60922937225865,
					2.5824662260522473
				]
			]
		},
		{
			"id": "GgAHllC5",
			"type": "text",
			"x": -106.89781759047318,
			"y": 2819.9594037063503,
			"width": 775.0191650390625,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 2075004699,
			"version": 132,
			"versionNonce": 981136277,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "SSKJKHO9NBSPLwwjRJggt",
					"type": "arrow"
				}
			],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"text": "Threads são mais leves, mais faceis de criar e de destruir do que processos.",
			"rawText": "Threads são mais leves, mais faceis de criar e de destruir do que processos.",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 17,
			"containerId": null,
			"originalText": "Threads são mais leves, mais faceis de criar e de destruir do que processos.",
			"lineHeight": 1.25
		},
		{
			"type": "arrow",
			"version": 331,
			"versionNonce": 1972337723,
			"isDeleted": false,
			"id": "6Zjo69UONg8VZ1mkg8GCY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -167.70649926857305,
			"y": 2903.0408831884456,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 68.60922937225865,
			"height": 2.5824662260522473,
			"seed": 1944149819,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					28.290067523129665,
					1.5497748157051774
				],
				[
					68.60922937225865,
					2.5824662260522473
				]
			]
		},
		{
			"id": "usW87RQi",
			"type": "text",
			"x": -70.67597514255655,
			"y": 2890.626070373017,
			"width": 933.4390258789062,
			"height": 50,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 56468501,
			"version": 155,
			"versionNonce": 275397851,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"text": "Ganho de desempenho em situações com muita computação e entradas e saidas, pois permite \na sobreposição.",
			"rawText": "Ganho de desempenho em situações com muita computação e entradas e saidas, pois permite \na sobreposição.",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 42,
			"containerId": null,
			"originalText": "Ganho de desempenho em situações com muita computação e entradas e saidas, pois permite \na sobreposição.",
			"lineHeight": 1.25
		},
		{
			"id": "E958Xkl3",
			"type": "text",
			"x": -73.5695298300565,
			"y": 3005.6412070917672,
			"width": 903.3390502929688,
			"height": 100,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1763783317,
			"version": 18,
			"versionNonce": 805884501,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "TOoFLGF3y5PZWJQl915_G",
					"type": "arrow"
				}
			],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"text": "Deve ficar claro que ter três processos em separado não funcionaria aqui, pois todos \nos três threads precisam operar no documento. Ao existirem três threads em vez de três\n processos, eles compartilham de uma memória comum e desse modo têm acesso \nao documento que está sendo editado. Com três processos isso seria impossível",
			"rawText": "Deve ficar claro que ter três processos em separado não funcionaria aqui, pois todos \nos três threads precisam operar no documento. Ao existirem três threads em vez de três\n processos, eles compartilham de uma memória comum e desse modo têm acesso \nao documento que está sendo editado. Com três processos isso seria impossível",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 92,
			"containerId": null,
			"originalText": "Deve ficar claro que ter três processos em separado não funcionaria aqui, pois todos \nos três threads precisam operar no documento. Ao existirem três threads em vez de três\n processos, eles compartilham de uma memória comum e desse modo têm acesso \nao documento que está sendo editado. Com três processos isso seria impossível",
			"lineHeight": 1.25
		},
		{
			"type": "arrow",
			"version": 387,
			"versionNonce": 1331947899,
			"isDeleted": false,
			"id": "TOoFLGF3y5PZWJQl915_G",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -152.6428267532795,
			"y": 3012.5378643857885,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 58.871924684758625,
			"height": 1.9622137075257342,
			"seed": 728453461,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947711079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "E958Xkl3",
				"focus": 0.24693000032556525,
				"gap": 20.201372238464387
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					25.855741351254665,
					0.3326524198714651
				],
				[
					58.871924684758625,
					1.9622137075257342
				]
			]
		},
		{
			"id": "EzVPOlOq",
			"type": "text",
			"x": -72.17564962172321,
			"y": 3150.7421999303087,
			"width": 842.0191040039062,
			"height": 75,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 920411989,
			"version": 49,
			"versionNonce": 72367483,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "jMYC0sKgOUZhR5Id4cai3",
					"type": "arrow"
				}
			],
			"updated": 1710947719613,
			"link": null,
			"locked": false,
			"text": "Um projeto no qual cada computação tem um estado salvo e existe algum conjunto \nde even- tos que pode ocorrer para mudar o estado, é chamado de máquina de \nestados finitos",
			"rawText": "Um projeto no qual cada computação tem um estado salvo e existe algum conjunto \nde even- tos que pode ocorrer para mudar o estado, é chamado de máquina de \nestados finitos",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 67,
			"containerId": null,
			"originalText": "Um projeto no qual cada computação tem um estado salvo e existe algum conjunto \nde even- tos que pode ocorrer para mudar o estado, é chamado de máquina de \nestados finitos",
			"lineHeight": 1.25
		},
		{
			"type": "arrow",
			"version": 403,
			"versionNonce": 660885,
			"isDeleted": false,
			"id": "jMYC0sKgOUZhR5Id4cai3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -136.26281116423107,
			"y": 3163.695098970618,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 62.52329187225838,
			"height": 5.78351988263239,
			"seed": 101939035,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1710947778797,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "EzVPOlOq",
				"focus": -0.4401692078551884,
				"gap": 1.5638696702494599
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					25.855741351254665,
					0.3326524198714651
				],
				[
					62.52329187225838,
					5.78351988263239
				]
			]
		},
		{
			"id": "MeMESmcc7MrcUHY6ETN94",
			"type": "image",
			"x": 11.944793086609934,
			"y": 3249.5504681594753,
			"width": 519.4078776041666,
			"height": 309.9914388884283,
			"angle": 0,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1713797851,
			"version": 64,
			"versionNonce": 276167093,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1710947783379,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "720ebb6e76344c59774f084cf7425eb25d7e2a29",
			"scale": [
				1,
				1
			]
		},
		{
			"id": "TRNh372M",
			"type": "text",
			"x": -86.14000509047321,
			"y": 3624.748913797496,
			"width": 920.259033203125,
			"height": 125,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 927269307,
			"version": 74,
			"versionNonce": 1297232085,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1710947938134,
			"link": null,
			"locked": false,
			"text": "uma solução: o processo pode- ria ser estruturado com um thread de entrada, \num de processamento e um de saída. O thread de entrada lê dados para um buffer\nde entrada; o thread de processa- mento pega os dados do buffer de entrada, \nprocessa-os e coloca os resultados no buffer de saída; e o thread de saída escreve esses\nresultados de volta para o disc",
			"rawText": "uma solução: o processo pode- ria ser estruturado com um thread de entrada, \num de processamento e um de saída. O thread de entrada lê dados para um buffer\nde entrada; o thread de processa- mento pega os dados do buffer de entrada, \nprocessa-os e coloca os resultados no buffer de saída; e o thread de saída escreve esses\nresultados de volta para o disc",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 117,
			"containerId": null,
			"originalText": "uma solução: o processo pode- ria ser estruturado com um thread de entrada, \num de processamento e um de saída. O thread de entrada lê dados para um buffer\nde entrada; o thread de processa- mento pega os dados do buffer de entrada, \nprocessa-os e coloca os resultados no buffer de saída; e o thread de saída escreve esses\nresultados de volta para o disc",
			"lineHeight": 1.25
		},
		{
			"id": "3yZupmwt",
			"type": "text",
			"x": -103.14065613213984,
			"y": 3583.6716432896833,
			"width": 650.5992431640625,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1286969013,
			"version": 48,
			"versionNonce": 1956564245,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "QvNY8_amxb8k7OiyILpAS",
					"type": "arrow"
				}
			],
			"updated": 1710947948965,
			"link": null,
			"locked": false,
			"text": "aplicações que precisam processar grandes quantidades de dados",
			"rawText": "aplicações que precisam processar grandes quantidades de dados",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 17,
			"containerId": null,
			"originalText": "aplicações que precisam processar grandes quantidades de dados",
			"lineHeight": 1.25
		},
		{
			"id": "QvNY8_amxb8k7OiyILpAS",
			"type": "arrow",
			"x": -162.92475443943152,
			"y": 3598.8634564407253,
			"width": 47.469319661458314,
			"height": 1.2437193142454817,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 1442455099,
			"version": 28,
			"versionNonce": 1439588981,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1710947948967,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					47.469319661458314,
					-1.2437193142454817
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": {
				"elementId": "3yZupmwt",
				"focus": 0.3518796068831126,
				"gap": 12.314778645833371
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1e1e1e",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "solid",
		"currentItemStrokeWidth": 2,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 258.3197739706815,
		"scrollY": -3120.290875467418,
		"zoom": {
			"value": 0.7500000000000001
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"gridColor": {
			"Bold": "#C9C9C9FF",
			"Regular": "#EDEDEDFF"
		},
		"currentStrokeOptions": null,
		"previousGridSize": null,
		"frameRendering": {
			"enabled": true,
			"clip": true,
			"name": true,
			"outline": true
		}
	},
	"files": {}
}
```
%%