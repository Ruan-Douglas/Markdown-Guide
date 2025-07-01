# **Bloco de Código**
Uma função muito útil na linguagem *Markdown* é o uso de blocos de código ou códigos em linha para representar algoritmos. Vamos conhecer um pouco sobre eles.

## Código em Linha
O código em linha é uma opção mais direta e simples de representar um código, podendo ser inserido no meio de uma frase ou explicação.

### Sintaxe
Para usar essa funcionalidade usamos a crase \` antes e depois do trecho, para destacá-lo e também evitar possíveis renderizações em *Markdown*.

### Exemplo:
```
Eu gostaria de mais informações sobre o comando `df = pd.read.csv(arquivo.csv)`
```
### Resultado:
Eu gostaria de mais informações sobre o comando `df = pd.read.csv(arquivo.csv)`

O texto entre crases fica destacado e com uma fonte monoespaçada.

## Bloco de Código
Há também a opção para os casos em que queremos incluir blocos de código completos. Nesse caso, a sintaxe é um pouco diferente.

### Sintaxe
Para blocos de código, usamos 3 crases ``` antes e depois do trecho, destacando toda aquela área.

### Exemplo:
Veja um exemplo de código em **Python**

\`\`\`

num = int(input('Digite um número: '))

if num % 2 == 0:

   print(f'O valor {num} é PAR')

else:

   print(f'O valor {num} é ÍMPAR')

print('Fim do Programa')


\`\`\`
### Resultado:
```
num = int(input('Digite um número: '))
if num % 2 == 0:
    print(f'O valor {num} é PAR')
else:
    print(f'O valor {num} é ÍMPAR')
print('Fim do Programa')
```
**Dica:** Para manter a indentação correta, escreva o código como faria normalmente em um editor. O Markdown irá preservar o espaçamento.

Como podemos ver, as duas maneiras, tanto em linha quanto em bloco, são muito úteis para representar códigos em nosso arquivo.