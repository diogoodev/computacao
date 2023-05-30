Tópico::
Links:: [[011-1-7 Fundamentos de Lógica de Programação]]

---
## Textos

-  [[Slides - Aula 3]]
- [[Apostila de Lógica]]



## Desvios Multicondicionais em [[Fluxogramas]]

**Exercício 01:**

| SALARIO     | IR     | SALLIQ | EXPRESSÃO       | V ou F?   |
| ----------- | ------ | ------- | ----------------- | -------- |
| R$ 100,00   | 0,00   | 100,00 | SALLIQ >= 100 | V            |
| R$ 200,00   | 10,00 | 190,00 | SALLIQ < 190    | F            |
| R$ 300,00   | 15,00 | 285,00 | SALLIQ == SALARIO - IR | V   |


**Exercício 02:** Sabendo que A=3, B=7 e C=4, informe se as expressões abaixo são verdadeiras ou falsas.

• ( F ) (A+C) >B  
• ( V ) B >= (A+2)  
• ( V ) C == B – A  
• ( F ) (B + A) < = C  
• ( F ) (C+A) > B  
• ( F ) (A+C) != B  
• ( V ) B != (A+2)

**Exercício 03:** Sabendo que A=5, B=4 e C=3 e D=6, informe se as expressões abaixo são verdadeiras ou falsas.  

• ( V ) (A > C) AND (C <= D)   5>3
• ( V ) (A+B) > 10 OR (A+B) = (C+D)   9 > 10 OR 9 =9
• ( V ) (A>=C) AND (D >= C) 5>= 3 AND 6>=3


**Problema das Férias 01**: Minha esposa e eu todo ano planejamos férias, mas  tem um problema que sempre atrapalha a gente: ou não temos tempo, ou  então às vezes falta dinheiro. Só podemos viajar se tivermos tempo e dinheiro. Considere as variáveis temp e din representando o nosso tempo e  dinheiro. Qual conectivo devemos colocar no fluxograma?  

![[Expressões Lógicas na Programação 2023-05-30 11.33.55.excalidraw]]

**Problema das Férias 02**:  Minha esposa e eu todo ano planejamos férias, mas 
tem  um  problema  que  sempre  atrapalha  a  gente:  ou  não  temos  tempo,  ou então  às  vezes  falta  dinheiro.  Mas,  esse  ano,  se  for  mês  de  Julho  ou Dezembro vamos viajar com certeza. Considere a variável mes. Qual conectivo devemos colocar no fluxograma ?

![[Expressões Lógicas na Programação 2023-05-30 11.37.21.excalidraw]]

  
**Problema das Férias 03**: Minha esposa e eu todo ano planejamos férias, mas  
tem um problema que sempre atrapalha a gente: ou não temos tempo, ou  
então às vezes falta dinheiro. Mas, em 2024, nos economizamos para viajar  
em qualquer mês, exceto Setembro, e se não estiver frio. Considere as  
variáveis mes, frio. Qual conectivo devemos colocar no fluxograma ?

![[Expressões Lógicas na Programação 2023-05-30 11.40.23.excalidraw]]

## Introdução ao Portugol



### Exercícios

1 – Faça um programa em Portugol que imprima todos os números entre 1 e 100 que são múltiplos de 3 e 5 ao mesmo tempo.

2 - Faça um programa em Portugol que imprima todos os números entre 1 e 100 que são múltiplos de 3 ou de 5.

3 – Faça um programa em Portugol que leia 3 números do usuário e diga qual deles é o maior. Considere que todos os números da entrada são diferentes.

4 - Escrever um programa em Portugol que encontre as raízes de uma equação de 2o grau, dada no seguinte formato: ax2 + bx + c. Solicitar ao usuários os valores dos coeficientes: a, b, c. Logo após informar as raízes.

Dica 1: inclua biblioteca Matemática
Dica 2: Veja como funcionam as funções mat.potencia() e mat.raiz ()