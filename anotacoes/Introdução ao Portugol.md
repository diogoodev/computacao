Tópico::
Links:: [[011-1-7 Fundamentos de Lógica de Programação]]

---
> [!todo]
> - [ ] ⏳ 2023-06-04 Refazer os exercicios da aula
> - [ ] ⏳ 2023-06-05 Fazer atividade do forum

# Textos
- [[Slides - Licenciatura em Computação - Aula 4]]

## Revisando
![[Portugol]]

## Como é Executado um Programa em Portugol?
Todo programa em Portugol é executado de forma sequencial;  
- A linha 1 é executada, depois a linha 2, a linha 3, etc...  
*- Desvios condicionais* e *Laços de repetição*, por exemplo, podem alterar essa ordem de execução;  
*- Desvios condicionais* decidem sobre a execução de um bloco de código; 
- Laços de repetição fazem que determinada parte de um código  seja executada novamente, de acordo com um critério de parada;

## Laços de Repetição
- **enquanto** – repete um bloco de código enquanto uma condição é satisfeita(repetição com teste no início);  
```pascal
enquanto ( condição ) { //faça  
comandos;  
} //fim enquanto
```

**- faça ... enquanto** – executa um bloco de código e testa ao final, se a  
condição final for satisfeita, repete a execução do código (repetição com teste  no final);  
```pascal
faça { //faça  
comandos;  
} enquanto ( condição )
```

**- para (arg1; arg2; arg3)** – possui 3 argumentos/parâmetros: arg1 é o inicializador, executado apenas 1 vez; arg2 é a condição de execução do  loop testada a cada iteração; arg3 é o incremento, também executado a  cada iteração (repetição contada).  

```pascal
Para (inicializa ; ( condição ); incremento){  
comandos;  
}//fim para
```

###  Comando de Seleção Múltipla

escolha (variável){ caso 'opc': instrução } – de acordo com o valor  
de 'variável', o comando de seleção múltipla encaminha a execução de apenas um caso específico dentre vários possíveis;  
- O protótipo desse comando é o seguinte:  

```css
escolha (variavel){
caso 'opc1':  
\\instrucoes  
pare
Caso 'opc2':  
\\instrucoes  
pare  
}
```

- O argumento do comando aceita somente números inteiros ou caracteres;  

```css
escolha (var){
caso 1:  
\\instrucoes  
pare
Caso 2:  
\\instrucoes  
pare  
} 

```

```css
escolha (var){
caso 'a':  
\\instrucoes  
pare
Caso 'b':  
\\instrucoes  
pare  
}
```

- [[Exercícios Complementares]]