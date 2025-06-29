# **Listas em Markdown**

A linguagem *Markdown* oferece 3 tipos de listas que podemos utilizar de acordo com nossa preferência ou necessidade.

São elas: 
* **Listas Numeradas**
* **Listas Demarcadas**
* **Listas de tarefas**

A seguir, iremos demonstrar como usar cada uma delas.

## Listas Numeradas
São utilizadas quando a ordem dos itens importa.

### Sintaxe
Para criar uma lista numerada usamos o `1. ` no começo do primeiro item e vai assim por diante.

### Exemplos:
```
1. Item A
2. Item B
3. Item C
```
### Resultado:
1. Item A
2. Item B
3. Item C

**Dica 1**: Podemos também criar *__sublistas__* apenas dando espaço 3 vezes e iniciando mais uma lista.
#### Exemplo:
```
1. Item A
2. Item B
   1. Item 1
   2. Item 2
   3. Item 3
3. Item C
```
#### Resultado:
1. Item A
2. Item B
   1. Item 1
   2. Item 2
   3. Item 3
3. Item C

**Dica 2**: Se você está fazendo uma sequência em uma lista colocando, por exemplo, 1, 2, 3 e etc, caso venha a errar o número e no lugar do desejado seja colocado outro, o Markdown entende automaticamente e renderiza como correto, mas *__não é uma boa prática colocar os números em desordem de forma proposital__*.

#### Exemplo:
```
1. Item A
2. Item B
6. Item C
0. Item D
```
#### Resultado:
1. Item A
2. Item B
6. Item C
0. Item D

Como podem ver, errei, onde deveria ser o *item 3* e *Item 4* eu coloquei o número 6 e o 0 respectivamente e mesmo assim o *Markdown* renderizou a sequência automaticamente, corrigindo a numeração visualmente.

## Listas Demarcadas
Quando a ordem dos itens não importa.

### Sintaxe
Podemos usar `*`, `-` ou `+` antes do item para criar uma lista e incluí-lo.

### Exemplos:
```
* Item A
* Item B
   * Item 1
   * Item 2
   * Item 3
* Item C
```
### Resultado:
* Item A
* Item B
   * Item 1
   * Item 2
   * Item 3
* Item C

Como podemos ver, a **_dica 1_** das listas numeradas também vale para listas demarcadas, onde dando 3 espaços podemos criar sublistas.

## Listas de Tarefas
Quando precisamos marcar ou registrar que algo já foi realizado ou nos lembrar de coisas que ainda precisam ser feitas, usamos as listas de tarefas.

### Sintaxe
Para criarmos usamos `- [ ]` antes do item para incluí-lo na lista e acrescentamos um `x` entre os `[ ]` para marcá-lo como concluído.

### Exemplos:
```
- [x] Item A
- [ ] Item B
   - [ ] Item 1
   - [ ] Item 2
   - [ ] Item 3
- [ ] Item C
```
### Resultado:
- [x] Item A
- [ ] Item B
   - [ ] Item 1
   - [ ] Item 2
   - [ ] Item 3
- [ ] Item C

Podemos observar que a **Dica 1** também serve para a lista de tarefas, apesar de não ser tão usual.

Dica: podemos ainda acrescentar um `~~` antes e depois do item da lista concluída para melhor visualização.

### Exemplo:
```
- [x] ~~Item A~~
- [x] ~~Item B~~
- [ ] Item C
```
### Resultado:
- [x] ~~Item A~~
- [x] ~~Item B~~
- [ ] Item C

Agora é com você! Experimente criar suas próprias listas e testar todas essas variações.
