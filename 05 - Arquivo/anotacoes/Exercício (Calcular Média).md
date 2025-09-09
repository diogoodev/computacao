Tópico::
Links:: [[Algoritmos e Lógica de Programação]]

---

```c
programa
{
	
	funcao inicio()
	{// Escrever  um  programa  em  Portugol  que  leia  três  números 
	// dados  pelo  usuário  e  em  seguida  apresente  a  média  desses números.

		real n1, n2, n3, soma, media
		escreva("Insira o primeiro numero: ")
		leia(n1)
		escreva("Insira o segundo numero: ")
		leia(n2)
		escreva("Insira o terceiro numero: ")
		leia(n3)
		soma = n1 + n2 + n3
		media = soma / 3
		escreva("O resultado da media dos tres numeros é ", media)
		se (media < 5)
		{
		escreva("Você foi reprovodo")
		}senao{
		escreva("Você foi aprovado")
		}
	}
}

```