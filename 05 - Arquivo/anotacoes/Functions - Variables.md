Tópico:: Variáveis e funções
Links::

---

# Aula 0 - Criando Código com Python
 - [[Notas da aula]]

---


## Creating Code with Python

- O VS Code é um tipo especial de editor de texto chamado compilador. Na parte superior, você notará um editor de texto e, na parte inferior, verá um terminal onde você pode executar comandos.
- No terminal, você pode executar o código hello.py para começar a programar.
- No editor de texto acima, você pode digitar print("hello, world"). Este é um programa canônico famoso que quase todos os programadores escrevem durante o processo de aprendizado.
- Na janela do terminal, você pode executar comandos. Para executar este programa, você precisará mover o cursor para a parte inferior da tela, clicar na janela do terminal e, em seguida, digitar um segundo comando. Ao lado do sinal de dólar ($), digite python hello.py e pressione a tecla Enter no seu teclado.
- Lembre-se, os computadores realmente só entendem zeros e uns. Portanto, quando você executa python hello.py, o Python interpretará o texto que você criou em hello.py e o traduzirá para zeros e uns que o computador possa entender.
- O resultado da execução do programa python hello.py é hello, world.
- Parabéns! Você acabou de criar seu primeiro programa.

## Functions (Funções)

- Funções são verbos ou ações que o computador ou a linguagem de programação já sabe como executar.
- No seu programa hello.py, a função print sabe como imprimir na janela do terminal.
- A função print recebe argumentos. Neste caso, "hello, world" são os argumentos que a função print recebe.

## Bugs (Erros)

- Bugs são uma parte natural da programação. São erros, problemas para você resolver! Não desanime! Isso faz parte do processo de se tornar um ótimo programador.
- Imagine em nosso programa hello.py que digitamos acidentalmente print("hello, world" e não percebemos o parêntese final ) exigido pelo compilador. Se eu cometer este erro de propósito, o compilador apresentará um erro na janela do terminal!
- Muitas vezes, as mensagens de erro informarão sobre o erro e fornecerão pistas sobre como corrigi-lo. No entanto, muitas vezes o compilador não será tão detalhado.

## Melhorando Seu Primeiro Programa em Python

- Podemos personalizar o seu primeiro programa Python.
- No nosso editor de texto hello.py, podemos adicionar outra função. `input` é uma função que recebe uma mensagem como argumento. Podemos editar nosso código para dizer:
  ```
  input("Qual é o seu nome? ")
  print("hello, world")
  ```
  Esta edição, por si só, não permitirá que o programa imprima o que o usuário digitou. Para isso, precisaremos apresentá-lo às variáveis.

## Variáveis

- Uma variável é apenas um contêiner para um valor dentro do seu programa.
- No seu programa, você pode introduzir sua própria variável editando-o para ler:
  ```
  nome = input("Qual é o seu nome? ")
  print("hello, world")
  ```
  Observe que o sinal de igual ''=''` no meio de `nome = input("Qual é o seu nome? ")` tem um papel especial na programação. Esse sinal de igual literalmente atribui o que está à direita para o que está à esquerda. Portanto, o valor retornado por `input("Qual é o seu nome? ")` é atribuído a `nome`.
- Se você editar o seu código da seguinte forma, notará um erro:
  ```
  nome = input("Qual é o seu nome? ")
  print("hello, nome")
  ```
  O programa retornará `hello, nome` na janela do terminal, independentemente do que o usuário digitar.
- Editando ainda mais nosso código, você poderia digitar:
  ```
  nome = input("Qual é o seu nome? ")
  print("hello,")
  print(nome)
  ```
  O resultado na janela do terminal seria:
  ```
  Qual é o seu nome? David
  hello
  David
  ```
  Estamos chegando mais perto do resultado que pretendemos!
- Você pode aprender mais sobre os tipos de dados em Python na documentação da linguagem.

## Comentários

- Comentários são uma maneira para os programadores acompanhar o que estão fazendo em seus programas e até informar outras pessoas sobre suas intenções para um bloco de código. Em resumo, são notas para você e outras pessoas que verão seu código!
- Você pode adicionar comentários ao seu programa para poder ver o que seu programa está fazendo. Você pode editar o seu código da seguinte forma:
  ```
  # Pergunte o nome do usuário
  nome = input("Qual é o seu nome? ")
  print("hello,")
  print(nome)
  ```
- Comentários também podem servir como uma lista de tarefas para você.

## Pseudocódigo

- O pseudocódigo é um tipo importante de comentário que se torna um tipo especial de lista de tarefas, especialmente quando você não sabe como realizar uma tarefa de programação. Por exemplo, no seu código, você pode editá-lo para dizer:
  ```
  # Pergunte o nome do usuário
  nome = input("Qual é o seu nome? ")

  # Imprima hello
  print("hello,")

  # Imprima o nome digitado
  print(nome)
  ```
Aqui está o texto traduzido para o português e organizado em formato Markdown:

## Melhorando Seu Primeiro Programa em Python

- Podemos melhorar ainda mais nosso código da seguinte maneira:
  ```
  # Pergunte o nome do usuário
  nome = input("Qual é o seu nome? ")

  # Imprima hello e o nome inserido
  print("hello, " + nome)
  ```
- Acontece que algumas funções recebem vários argumentos.
- Podemos usar uma vírgula `,` para passar vários argumentos editando nosso código da seguinte maneira:
  ```
  # Pergunte o nome do usuário
  nome = input("Qual é o seu nome? ")

  # Imprima hello e o nome inserido
  print("hello,", nome)
  ```
- A saída no terminal, se digitarmos "David", seria "hello, David". Sucesso.

## Strings e Parâmetros

- Uma string, conhecida como "str" em Python, é uma sequência de texto.
- Voltando um pouco em nosso código para o seguinte, havia um efeito visual de ter o resultado aparecendo em várias linhas:
  ```
  # Pergunte o nome do usuário
  nome = input("Qual é o seu nome? ")
  print("hello,")
  print(nome)
  ```
- As funções recebem argumentos que influenciam seu comportamento. Se olharmos a documentação do print, você notará que podemos aprender muito sobre os argumentos que a função print recebe.
- Ao olhar essa documentação, você aprenderá que a função print inclui automaticamente um trecho de código end='\n'. Esse \n indica que a função print criará automaticamente uma quebra de linha quando executada. A função print recebe um argumento chamado "end" e o padrão é criar uma nova linha.
- No entanto, podemos fornecer um argumento para "end" nós mesmos, de modo que uma nova linha não seja criada!
- Podemos modificar nosso código da seguinte maneira:
  ```
  # Pergunte o nome do usuário
  nome = input("Qual é o seu nome? ")
  print("hello,", end="")
  print(nome)
  ```
- Ao fornecer "end=""", estamos substituindo o valor padrão de "end" para que ele nunca crie uma nova linha após essa primeira instrução print. Fornecendo o nome como "David", a saída na janela do terminal será "hello, David".
- Parâmetros, portanto, são argumentos que podem ser passados para uma função.
- Você pode aprender mais na documentação do Python sobre o print.

## Um pequeno problema com as aspas

- Observe como adicionar aspas como parte de sua string é desafiador.
- print("hello,"friend"") não funcionará e o compilador emitirá um erro.
- Em geral, existem duas abordagens para corrigir isso. Primeiro, você pode simplesmente trocar as aspas por aspas simples.
- Outra abordagem mais comumente usada seria o código print("hello, \"friend\""). As barras invertidas dizem ao compilador que o caractere seguinte deve ser considerado uma aspa na string e evitam um erro do compilador.

## Formatando Strings

- Provavelmente, a maneira mais elegante de usar strings seria a seguinte:
  ```
  # Pergunte o nome do usuário
  nome = input("Qual é o seu nome? ")
  print(f"hello, {nome}")
  ```
- Observe o "f" em print(f"hello, {nome}"). Esse "f" é um indicador especial para o Python tratar essa string de uma maneira especial, diferente das abordagens anteriores que ilustramos nesta aula. Espere usar frequentemente esse estilo de strings neste curso.

## Mais sobre Strings

- Você nunca deve esperar que o usuário coopere como pretendido. Portanto, você precisará garantir que a entrada do usuário seja corrigida ou verificada.
- Acontece que nas strings incorporadas existe a capacidade de remover espaços em branco de uma string.
- Usando o método "strip" em "nome" como "nome = nome.strip()", ele removerá todos os espaços em branco à esquerda e à direita da entrada do usuário. Você pode modificar seu código para:
  ```
  # Pergunte o nome do usuário
  nome = input("Qual é o seu nome? ")

  # Remova os espaços em branco da string
  nome = nome.strip()

  # Imprima o resultado
  print(f"hello, {nome}")
  ```
- Executando este programa, independentemente de quantos espaços você digitar antes ou depois do nome, ele removerá todos os espaços em branco.
- Usando o método "title", ele converterá o nome do usuário para letras maiúsculas no início de cada palavra:
  ```
  # Pergunte o nome do usuário
  nome = input("Qual é o seu nome? ")

  # Remova os espaços em branco da string
  nome = nome.strip()

  # Coloque a primeira letra de cada palavra em maiúscula
  nome = nome.title()

  # Imprima o resultado
  print(f"hello, {nome}")
  ```
- Neste ponto, você pode estar muito cansado de digitar "python" repetidamente na janela do terminal. Você pode usar a seta para cima do seu teclado para recuperar os comandos de terminal mais recentes que você fez.
- Observe que você pode modificar seu código para ser mais eficiente:
  ```
  # Pergunte o nome do usuário
  nome = input("Qual é o seu nome? ").strip().title()

  # Imprima o resultado
  print(f"hello, {nome}")
  ```
- Isso cria o mesmo resultado que o código anterior.
- Podemos ir ainda mais longe!
  ```
  # Pergunte o nome do usuário, remova os espaços em branco da string e coloque a primeira letra de cada palavra em maiúscula
  nome = input("Qual é o seu nome? ").strip().title()

  # Imprima o resultado
  print(f"hello, {nome}")
  ```
- Você pode aprender mais sobre strings na documentação do Python sobre "str".

## Inteiros ou int

- Em Python, um número inteiro é referido como "int".
- No mundo da matemática, estamos familiarizados com os operadores +, -, *, / e %. Esse último operador % ou operador de módulo pode não ser muito familiar para você.
- Você não precisa usar a janela do editor de texto em seu compilador para executar código Python. No seu terminal, você pode executar apenas "python". Você verá ">>>" no terminal. Você

 pode então executar código ao vivo e interativo. Você pode digitar 1+1 e ele calculará isso. Este modo não será comumente usado durante este curso.
- Abrindo o VS Code novamente, podemos digitar "code calculator.py" no terminal. Isso criará um novo arquivo no qual criaremos nossa própria calculadora.
Primeiro, podemos declarar algumas variáveis.

```python
x = 1
y = 2

z = x + y

print(z)
```

Naturalmente, quando executamos "python calculator.py", obtemos o resultado na janela do terminal de 3. Podemos tornar isso mais interativo usando a função "input".

```python
x = input("Qual é o valor de x? ")
y = input("Qual é o valor de y? ")

z = x + y

print(z)
```

Executando este programa, descobrimos que a saída está incorreta, sendo "12". Por que isso pode ser?

Antes, vimos como o sinal de "+" concatena duas strings. Como a entrada do teclado do seu computador entra no compilador como texto, ela é tratada como uma string. Portanto, precisamos converter essa entrada de uma string para um inteiro. Podemos fazer isso da seguinte forma:

```python
x = input("Qual é o valor de x? ")
y = input("Qual é o valor de y? ")

z = int(x) + int(y)

print(z)
```

O resultado agora está correto. O uso de `int(x)` é chamado de "casting", onde um valor é temporariamente alterado de um tipo de variável (neste caso, uma string) para outro (aqui, um inteiro).

Podemos melhorar ainda mais nosso programa da seguinte forma:

```python
x = int(input("Qual é o valor de x? "))
y = int(input("Qual é o valor de y? "))

print(x + y)
```

Isso ilustra que você pode executar funções em funções. A função mais interna é executada primeiro e, em seguida, a externa é executada. Primeiro, a função "input" é executada. Em seguida, a função "int".
Você pode aprender mais na documentação do Python sobre "int".

## Float Basics

Um valor de ponto flutuante é um número real que contém um ponto decimal, como 0.52.

Você pode alterar seu código para suportar números de ponto flutuante da seguinte forma:

```python
x = float(input("Qual é o valor de x? "))
y = float(input("Qual é o valor de y? "))

print(x + y)
```

Essa alteração permite que o usuário insira 1.2 e 3.4 para obter um total de 4.6.

Vamos imaginar, no entanto, que você queira arredondar o total para o inteiro mais próximo. Olhando a documentação do Python para a função "round", você verá que os argumentos disponíveis são "round(number[n, ndigits])". Os colchetes indicam que algo opcional pode ser especificado pelo programador. Portanto, você pode usar "round(n)" para arredondar um dígito para o inteiro mais próximo. Alternativamente, você pode codificar da seguinte forma:

```python
# Obter a entrada do usuário
x = float(input("Qual é o valor de x? "))
y = float(input("Qual é o valor de y? "))

# Criar um resultado arredondado
z = round(x + y)

# Imprimir o resultado
print(z)
```

A saída será arredondada para o inteiro mais próximo.

E se quisermos formatar a saída de números longos? Por exemplo, em vez de ver "1000", você pode desejar ver "1,000". Você pode modificar seu código da seguinte forma:

```python
# Obter a entrada do usuário
x = float(input("Qual é o valor de x? "))
y = float(input("Qual é o valor de y? "))

# Criar um resultado arredondado
z = round(x + y)

# Imprimir o resultado formatado
print(f"{z:,}")
```

Embora seja bastante criptico, o código "print(f"{z:,}") cria um cenário em que o valor de "z" terá vírgulas, fazendo com que o resultado pareça "1,000" ou "2,500".

## Mais sobre Números de Ponto Flutuante

Como podemos arredondar valores de ponto flutuante? Primeiro, modifique seu código da seguinte forma:

```python
# Obter a entrada do usuário
x = float(input("Qual é o valor de x? "))
y = float(input("Qual é o valor de y? "))

# Calcular o resultado
z = x / y

# Imprimir o resultado
print(z)
```

Quando digitamos 2 como valor de "x" e 3 como valor de "y", o resultado "z" é 0.6666666666, parecendo ir para o infinito como poderíamos esperar.

Vamos imaginar que queremos arredondar isso para baixo. Podemos modificar nosso código da seguinte forma:

```python
# Obter a entrada do usuário
x = float(input("Qual é o valor de x? "))
y = float(input("Qual é o valor de y? "))

# Calcular o resultado e arredondar
z = round(x / y, 2)

# Imprimir o resultado
print(z)
```

Como poderíamos esperar, isso arredondará o resultado para as duas casas decimais mais próximas.

Também podemos usar o "f-string" para formatar a saída da seguinte forma:

```python
# Obter a entrada do usuário
x = float(input("Qual é o valor de x? "))
y = float(input("Qual é o valor de y? "))

# Calcular o resultado
z = x / y

# Imprimir o resultado
print(f"{z:.2f}")
```

Esse código "f-string" criptico exibirá o mesmo resultado que nossa estratégia anterior de arredondamento.

Você pode aprender mais na documentação do Python sobre números de ponto flutuante.

## Def

Não seria legal criar nossas próprias funções?

Vamos voltar ao nosso código final "hello.py" digitando "code hello.py" na janela do terminal. Seu código inicial deve ser assim:

```python
# Pedir ao usuário seu nome, remover espaços em branco da string e colocar a primeira letra de cada palavra em maiúscula
name = input("Qual é o seu nome? ").strip().title()

# Imprimir a saída
print(f"Olá, {name}")
```

Podemos melhorar nosso código para criar nossa própria função especial que diz "olá" para nós!

Apague todo o código em nosso editor de texto e vamos começar do zero:

```python
name = input("Qual é o seu nome? ")
hello()
print(name)
```

Tentar executar este código gerará um erro. Afinal, não há nenhuma função definida chamada "hello".

Podemos criar nossa própria função chamada "hello" da seguinte forma:

```python
def hello():
    print("Olá")
```

```python
name = input("Qual é o seu nome? ")
hello()
print(name)
```

Observe que tudo abaixo de "def hello()" está indentado. O Python é uma linguagem de indentação. Ele usa a indentação para entender o que faz parte da função acima. Portanto, tudo na função "hello" deve estar indentado. Quando algo não está indentado, ele é tratado como se não fizesse parte da função "hello". Executando "python hello.py" na janela do terminal, você verá que a saída não é exatamente como você pode querer.

Podemos melhorar ainda mais nosso código:

```python
def hello(to):
    print("Olá,", to)

name = input("Qual é o seu nome? ")
hello(name)
```

Aqui, nas primeiras linhas, você está criando sua função "hello". Desta vez, no entanto, você está dizendo ao compilador que esta função recebe um único parâmetro: uma variável chamada "to". Portanto, quando você chama "hello(name)", o computador passa "name" para a função "hello" como "to". É assim que passamos valores para funções. Muito útil! Executando "python hello.py" na janela do terminal, você verá que a saída está muito mais próxima do ideal apresentado anteriormente nesta aula.

Podemos alterar nosso código para adicionar um valor padrão para "hello":

```python
def hello(to="mundo"):
    print("Olá,", to)

name = input("Qual é o seu nome? ")
hello(name)

# Saída sem passar os argumentos esperados
hello()
```

Teste o código por si mesmo. Observe como o primeiro "hello" se comportará como você espera e o segundo "hello", que não recebeu um valor, irá por padrão imprimir "Olá, mundo".

Não precisamos ter nossa função no início de nosso programa. Podemos movê-la para baixo, mas precisamos informar ao compilador que temos uma função principal e uma função separada "hello".

```python
def main():
    name = input("Qual é o seu nome? ")
    hello(name)
    hello()

def hello(to="mundo"):
    print("Olá,", to)

```

Isso, por si só, criará um erro de alguma forma. Se executarmos "python hello.py", nada acontecerá! O motivo disso é que nada neste código está realmente chamando a função principal e dando vida ao nosso programa.

A seguinte pequena modificação chamará a função principal e restaurará nosso programa para funcionar corretamente:

```python
def main():
    name = input("Qual é o seu nome? ")
    hello(name)
    hello()

def hello(to="mundo"):
    print("Olá,", to)

main()
```

## Retornando Valores

Você pode imaginar muitos cenários em que não deseja apenas que uma função execute uma ação, mas também que retorne um valor de volta para a função principal. Por exemplo, em vez de simplesmente imprimir o cálculo de x + y, você pode querer que uma função retorne o valor desse cálculo para outra parte do seu programa. Essa "devolução" de um valor é o que chamamos de valor de retorno.

Voltando ao nosso código "calculator.py" digitando "code calculator.py". Apague todo o código lá. Rework o código da seguinte forma:

```python
def main():
    x = int(input("Qual é o valor de x? "))
    print("O quadrado de x é", square(x))

def square(n):
    return n * n

main()
```

Efetivamente, "x" é passado para "square". Em seguida, o cálculo de "x * x" é retornado de volta para a função principal.