Tópico::
Links:: [[Algoritmos e Lógica de Programação]]

---

Escreva um algoritmo para calcular reajustes salariais e imprimir
salário reajustado.

a) 25% para aqueles que ganham até 1 salário mínimo;

b) 50% para aqueles que ganham até 3 salários mínimos;

c) 10% para aqueles que ganham acima de 3 salários mínimos;


```c
programa
{
	
	funcao inicio()
	{
		real salario, salarioMinimo, salarioReajustado
		escreva("Olá inisira o seu salario\n")
		leia(salario)
		
		salarioMinimo = 1240.00
		se( salario <= salarioMinimo){
			
			salarioReajustado = (salario * 0.25
) + salario
			escreva("\nSeu salario reajustado é: \n", salarioReajustado )
			
		}senao se( salario <= (3*salarioMinimo)){
			
			salarioReajustado = (salario * 0.50) + salario
			escreva("\nSeu salario reajustado é: \n", salarioReajustado )
			
		}senao se ( salario > (3*salarioMinimo)){
			
			salarioReajustado = (salario * 0.10) + salario
			escreva("\nSeu salario reajustado é: \n", salarioReajustado )
		}
	}
}

```