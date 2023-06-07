Tópico::
Links::

---

![[Operadores Lógicos]]

```c
programa
{
	
	funcao inicio()
	{
	cadeia nome
	inteiro frequencia, nota1, nota2, nota3, nota4
	real media
		escreva("Olá Mundo")
		escreva("Digite seu nome: ")
		leia(nome)

		escreva("Digite sua frequência:")
		leia(frequencia)

		escreva("Digite suas notas:")
		leia(nota1, nota2, nota3, nota4)

		media = (nota1 + nota2 + nota3 + nota4) / 4

		se ((media <= 7) ou (frequencia <= 75))
		{
			escreva(nome, " foi reprovado!")

		}senao{

			escreva(nome, " foi aprovado!")
		}
	}
}

```


Usando o operador NOT

```c
programa
{
	
	funcao inicio()
	{
	cadeia nome
	inteiro frequencia, nota1, nota2, nota3, nota4
	real media
		escreva("Olá Mundo")
		escreva("Digite seu nome: ")
		leia(nome)

		escreva("Digite sua frequência:")
		leia(frequencia)

		escreva("Digite suas notas:")
		leia(nota1, nota2, nota3, nota4)

		media = (nota1 + nota2 + nota3 + nota4) / 4

		se (nao(media >= 7) ou nao(frequencia >= 75))
		{
			escreva(nome, " foi reprovado!")

		}senao{

			escreva(nome, " foi aprovado!")
		}
	}
}

```